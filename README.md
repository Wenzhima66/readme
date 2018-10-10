# 代码中的说明
---
## 1. 依赖项
--
- Python 3.6
- Numpy 1.14
- Pytorch 0.4
- Opencv 2.4
- VisualStudio 2013, CUDA8.0, cudnn6.0.
## 2. 文件结构

    | -- code
        | -- gen_data_csv.py
        | -- dataset.py
        | -- models.py
        | -- validation.py
        | -- train_net.py
        | -- test_net.py
    | -- data
        | -- guangdong_round1_test_a_20180916
        | -- guangdong_round1_test_b_20181009
        | -- guangdong_round1_train2_20180916
    | -- data_preprocess
    | -- submit
## 3. 引用

### 预训练模型

- [imagenet]
- [http://data.lip6.fr/cadene/pretrainedmodels/inceptionv4-8e4777a0.pth](http://data.lip6.fr/cadene/pretrainedmodels/inceptionv4-8e4777a0.pth)
### 训练模型

- [Inception-v4, Inception-ResNet and the Impact of Residual Connections on Learning]
- [https://arxiv.org/abs/1602.07261](https://arxiv.org/abs/1602.07261)
### 模型说明

        我们以Inception-V4网络模型为主干，训练我们预处理之后的图像
## 4 说明




