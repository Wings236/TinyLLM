# TinyLLM

## 项目介绍
本项目扎根于计算资源有限的前提下去思考大语言模型的种种环节，包括大语言模型的生产(数据集搜集、模型搭建、模型训练等)和大语言模型的部署(模型量化，剪枝，蒸馏等加速推理、基于硬件设备的底层计算优化)。对大语言模型的性能进行测评，包括输出性能和计算性能。

本项目主要有以下几个模块：
- 大语言模型生产模块：了解、熟悉大语言模型，包括数据采集，模型结构搭建，模型训练等，训练大语言模型。

- 大语言模型评估模块：熟悉评估大语言模型，通过评估指标了解大语言模型的相关性能，包括推理性能和计算性能，另一方面，也通过评估指标看到不同架构的大语言模型的性能差异。

- 大语言模型推理模块：一方面通过对模型进行量化、剪枝和蒸馏方式在保持或略微减少性能的基础上压缩模型大小，加速推理；另一方面，利用底层语言如ONNX、TensorRT、C/C++等技术对大语言模型针对性优化，使其能够加速推理。

## 项目计划计划

1. 大语言模型的生产
2. 大语言模型的评估
3. 大语言模型的部署与推理

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

2. 大语言模型经典架构：
    - OPT
    - BERT
    - T5
    - Llama
    - ChatGLM
    - Qwen
    - DeepSeek
    - MOE
    - NSA

3. 底层语言大语言模型仓库：
    - [karpathy/llama2.c](https://github.com/karpathy/llama2.c)
    - [abetlen/llama-cpp-python](https://github.com/abetlen/llama-cpp-python)
    - [li-plus/chatglm.cpp](https://github.com/li-plus/chatglm.cpp)

4. 从零开始构建大语言模型：
   - [stanford-CS336](https://github.com/stanford-cs336)
   - [LLMs-from-scratch](https://github.com/rasbt/LLMs-from-scratch)
   - [LLMs-from-scratch_中文版](https://github.com/skindhu/Build-A-Large-Language-Model-CN)
