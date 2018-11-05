# sklearn库

## 一、sklearn库介绍

sklearn是一个基于Python的第三方模块，
它集成了一些常用的机器学习算法，在进行机器学习任务时，
并不需要实现算法，只需要简单的调用其中提供的模块就能完成大多数的任务。

## 二、sklearn库安装

**注意：** 需要事先安装Numpy、Scipy和matplotlib依赖库，因为sklearn库是在它们的基础上开发而成的。
* Numpy（Numerical Python）是一个开源的Python科学计算库
* Scipy库是sklearn库的基础，是基于Numpy的一个集成了多种数学算法和函数的Python模块
* metplotlib是基于Numpy的一套Python工具包，提供了大量的数据绘图工具

**参考下载地址：** http://www.lfd.uci.edu/~gohlke/pythonlibs/#

### 安装顺序
Numpy >>> Scipy >>> matplotlib >>> sklearn

### 安装方法（Windows系统）

1. cmd命令行进入到python所在目录

2. 依次输入以下命令进行安装

```
python -m pip install numpy
python -m pip install scipy
python -m pip install matplotlib
python -m pip install scikit-learn
```

3. cmd命令行进入到python，输入以下代码检测，如果能够成功引入则安装成功

```
import numpy
import matplotlib
import sklearn
```

## 三、sklearn标准数据集及基本功能

### 数据集总览
![overview of datasets](../Images/datasets_overview.png)

### 数据集详细介绍

* 波士顿房价数据集

包含506组数据，每条数据包含房屋及房屋周围的详细信息。
其中包括城镇犯罪率、一氧化氮浓度、住宅平均房间数等。
因此，波士顿房价数据集能够应用到 **回归** 问题上。


