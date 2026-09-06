# 神经网络与深度学习：案例与实践（第一版）

**2022 年版配套代码 · PaddlePaddle · 8 章实践**

[章节代码](#章节代码) · [配套课程](#配套课程) · [问题反馈](https://github.com/nndl/practice-in-paddle/issues) · [第二版 PyTorch 实现](https://github.com/nndl/nndl-practice) · [系列主站](https://nndl.ai/)

本仓库保留《神经网络与深度学习：案例与实践》第一版的 PaddlePaddle 代码，供第一版读者与飞桨学习者使用。**第二版改用 PyTorch，扩展为 10 章，新增图神经网络、大语言模型与智能体，入口为 [nndl-practice](https://github.com/nndl/nndl-practice)。**

## 本书内容

本书是《神经网络与深度学习》（蒲公英书）的配套实践篇。每章结合模型解读与案例实践：先从零实现模型和算法，再用飞桨提供的 API 完成实际任务，在数据处理、训练和评价中理解原理。

适合有 Python 基础、希望动手学习深度学习的读者。可结合理论书阅读，也可按下方目录选择感兴趣的章节。

## 章节代码

| 章 | 代码入口 |
|---|---|
| 1 | [实践基础](chap1实践基础/) |
| 2 | [机器学习概述](chap2机器学习概述/) |
| 3 | [线性模型](chap3线性模型/) |
| 4 | [前馈神经网络](chap4前馈神经网络/) |
| 5 | [卷积神经网络](chap5卷积神经网络/) |
| 6 | [循环神经网络](chap6循环神经网络/) |
| 7 | [网络优化与正则化](chap7网络优化与正则化/) |
| 8 | [注意力机制](chap8注意力机制/) |

## 使用代码

```bash
git clone https://github.com/nndl/practice-in-paddle.git
cd practice-in-paddle
```

使用 Jupyter Notebook 打开对应章节中的 `.ipynb` 文件，按 Notebook 内的环境与数据准备说明运行。[数据集说明](dataset/README.md)提供配套数据入口。第一版环境与第二版不同，请按所用版本的说明准备依赖。

## 配套课程

- [《神经网络与深度学习》视频课程](https://aistudio.baidu.com/aistudio/education/group/info/25876)：邱锡鹏主讲。
- [《案例与实践》视频课程与在线实训](https://aistudio.baidu.com/aistudio/education/group/info/25793)：飞桨研发工程师讲解实践内容。
- [飞桨 AI Studio](https://aistudio.baidu.com/aistudio/index)：课程与在线 Notebook 平台。

## 提问与反馈

第一版代码问题请提交到[本仓库 Issues](https://github.com/nndl/practice-in-paddle/issues)，注明章节、Notebook、PaddlePaddle 与 Python 版本、复现步骤和报错。学习交流可前往[系列讨论区](https://github.com/nndl/nndl-discussion/discussions)。

[第二版电子书与代码](https://github.com/nndl/nndl-practice) · [理论书第一版资料](https://github.com/nndl/nndl/tree/main/legacy/nndl-v1) · [系列选书路径](https://nndl.ai/reading-path/)
