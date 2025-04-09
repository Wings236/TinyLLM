# 数据部分

数据部分主要有两个部分：
- 数据集下载与清洗
- 数据集预处理

## 数据搜集列表
数据集主要为开源数据集

- 维基百科：[pleisto/wikipedia-cn-20230720-filtered](https://huggingface.co/datasets/pleisto/wikipedia-cn-20230720-filtered)
- 

huggingface国内下载方式：[参考](https://hf-mirror.com/)

```bash
pip install -U huggingface_hub
export HF_ENDPOINT=https://hf-mirror.com
# 模型下载示例
huggingface-cli download --resume-download gpt2 --local-dir gpt2
# 数据集下载示例
huggingface-cli download --repo-type dataset --resume-download wikitext --local-dir wikitext
```

其中，镜像网站还提供一个下载工具：[hfd](https://gist.github.com/padeoe/697678ab8e528b85a2a7bddafea1fa4f)。hfd 是镜像站开发的 huggingface 专用下载工具，基于成熟工具 aria2，可以做到稳定高速下载不断线。

```bash
# 下载hf
wget https://hf-mirror.com/hfd/hfd.sh
chmod a+x hfd.sh
export HF_ENDPOINT=https://hf-mirror.com
# 下载模型
./hfd.sh gpt2
# 下载数据集
./hfd.sh wikitext --dataset
```


## 数据预处理流程


## 其他
