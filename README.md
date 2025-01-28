# TinyLLM

## 仓库介绍
本项目主要针对计算性能较弱、内存较少的环境进行训练、微调、部署大语言模型。首先通过从零开始构建大语言模型了解大语言模型的相关发展，并评估相关性能；其次，通过以更底层的语言如C、CPP在计算性能较弱的环境下部署大语言模型。最后，在真实场景下部署并测试大语言模型。


本项目主要以下几个目的：
- 了解、熟悉大语言模型，并能够从零预训练和微调出能够使用的大语言模型（一般为中英文）。

- 熟悉如何评估大语言模型，通过评估指标熟悉大语言的相关性能。

- 通过评估指标，比较不同的模型参数，模型框架所带来的性能差异，深入理解相关架构带来的好处。

- 利用底层语言如C、C++等方式实现部署代码，使其能够在计算性能更弱的环境下部署运行。

## 仓库内容

### 1 从零开始的大语言模型

### 2 大语言模型不同架构的对比

### 3 底层语言实现大语言模型



## 参考资料
1. 参数较小的大语言模型仓库：
    - [DLLXW/baby-llama2-chinese](https://github.com/DLLXW/baby-llama2-chinese)
    - [charent/Phi2-mini-Chinese](https://github.com/charent/Phi2-mini-Chinese)
    - [charent/ChatLM-mini-Chinese](https://github.com/charent/ChatLM-mini-Chinese/)
    - [Tongjilibo/build_MiniLLM_from_scratch](https://github.com/Tongjilibo/build_MiniLLM_from_scratch)
    - [zhanshijinwat/Steel-LLM](https://github.com/zhanshijinwat/Steel-LLM)

2. 大语言模型经典技术\[暂定\]：
    - OPT
    - BERT
    - T5
    - Llama
    - ChatGLM
    - Qwen
    - DeepSeek(MOE)
    - ......

3. 底层大语言模型仓库：
    - [karpathy/llama2.c](https://github.com/karpathy/llama2.c)
    - [abetlen/llama-cpp-python](https://github.com/abetlen/llama-cpp-python)
    - [li-plus/chatglm.cpp](https://github.com/li-plus/chatglm.cpp)