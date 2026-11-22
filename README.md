# 基于多层感知机（MLP）的手写数字识别

## 项目简介
纯 Python + NumPy 实现的多层感知机，**不使用 PyTorch / TensorFlow 等深度学习框架**。
前向传播、反向传播、梯度下降全部手写，底层矩阵运算交给 NumPy 加速。

数据集为 MNIST（60000 张训练图 + 10000 张测试图，28×28 灰度手写数字 0~9）。

## 项目结构

```dtx
your-handwritten/
├── dataset
│   ├── t10k-images-idx3-ubyte
│   ├── t10k-labels-idx1-ubyte
│   ├── train-images-idx3-ubyte
│   └── train-labels-idx1-ubyte
├── lib
    ├── data_loader.py
│   ├── evaluate.py
│   ├── losses.py
│   ├── model.py
│   ├── optimizer.py
│   └── preprocess.py
├── README.md
├── requirements.txt
└── train.py
```
