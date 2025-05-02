# TinyLLM

## 仓库介绍
本项目主要针对计算性能较弱、内存较少的环境进行训练、微调、部署大语言模型。首先通过从零开始构建大语言模型了解大语言模型的相关发展，并评估相关性能；其次，通过以更底层的语言如C、CPP在计算性能较弱的环境下部署大语言模型。最后，在真实场景下部署并测试大语言模型。


本项目主要以下几个目的：
- 了解、熟悉大语言模型，并能够从零预训练和微调出能够使用的大语言模型（一般为中英文）。

- 熟悉如何评估大语言模型，通过评估指标熟悉大语言的相关性能。

- 通过评估指标，比较不同的模型参数，模型框架所带来的性能差异，深入理解相关架构带来的好处。

- 利用底层语言如C、C++等方式实现部署代码，使其能够在计算性能更弱的环境下部署运行。

## 仓库内容

### 1. 从零开始的大语言模型

TODO List:
- [ ] 数据集的搜集、清洗与构建。
- [ ] 任务的确定与模型的构建。
- [ ] 训练框架确定与模型训练。
- [ ] 模型评估。

### 2. 大语言模型不同架构的对比

比较不同的大语言模型架构之间所带来的性能上的差异与偏好。

### 3. 大语言模型推理

通过推理层面的优化，使得大语言模型能够更小且更快的方式进行推理计算。


## 参考资料
1. 参数较小的大语言模型仓库：
    - [jzhang38/TinyLlama](https://github.com/jzhang38/TinyLlama)
      - 参数量：1.1B，记录更新时间：2024-02-04
    - [DLLXW/baby-llama2-chinese](https://github.com/DLLXW/baby-llama2-chinese) 
      - 参数量：500M-1B, 记录更新时间：2024-05-21
    - [charent/Phi2-mini-Chinese](https://github.com/charent/Phi2-mini-Chinese) 
      - 参数量：200M, 记录更新时间：2024-07-11
    - [Tongjilibo/build_MiniLLM_from_scratch](https://github.com/Tongjilibo/build_MiniLLM_from_scratch) 
      - 参数量：200M, 记录更新时间：2025-03-23
    - [jingyaogong/minimind](https://github.com/jingyaogong/minimind) 
      - 参数量：26M，记录更新时间：2025-04-27
    - (欢迎添加)...

2. 大语言模型经典架构：
    - OPT
    - BERT
    - T5
    - Llama
    - ChatGLM
    - Qwen
    - DeepSeek
    - MOE
    - ......

3. 底层语言大语言模型仓库：
    - [karpathy/llama2.c](https://github.com/karpathy/llama2.c)
    - [abetlen/llama-cpp-python](https://github.com/abetlen/llama-cpp-python)
    - [li-plus/chatglm.cpp](https://github.com/li-plus/chatglm.cpp)
    - ...