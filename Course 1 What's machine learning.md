## Course 1 What's machine learning?



### 一、机器学习的定义



* 早期将机器定义为：

  Field of study that gives computers the ability to learn without being explicitly programmed.

* 标准的机器学习定义为：

  如果一个计算机程序针对某类任务T的用P衡量的性能根据经验E来自我完善。那么我们称这个计算机程序在从经验E中学习，针对某类任务T，它的性能用P来衡量。

* 这里定义了机器学习的三个指标：经验(E)，任务(T)和效果(P)

* 经验(Experience)是机器学习的来源，例如**观察多次邮件的分类**

* 任务(Task)是机器学习的最终目的，例如**实现对垃圾邮件的分类**

* 性能(Performance)则是机器学习优良的衡量标准，例如**分类的准确率**



<img src="C:\Users\eliochiu\AppData\Roaming\Typora\typora-user-images\image-20210715183735974.png" alt="image-20210715183735974" style="zoom: 25%;" />



### 二、 机器学习的分类



机器学习主要分为有监督学习(Supervised Learning) 和无监督学习(Unsupervised Learning)

* 有监督学习：是利用已知类别的样本（即有标记的样本 labeled sample，已知其相应的类别），调整分类器的参数，训练得到一个最优模型，使其达到所要求性能。通俗来讲，有监督学习的目的是要利用部分的已分类、有标记的样本来训练模型，用它学到的特征，对还未分类、未贴标签的样本进行分类。例如回归分析（对连续值的预测）和分类（对离散值的预测）

* 无监督学习：实现没有分类、没有标签的数据集的分类，从中获取一定的结构。例如聚类运算。

* 二者的区别：有监督学习只利用有标记的数据集训练，无监督学习只利用未标记的数据集训练。

  

<img src="C:\Users\eliochiu\AppData\Roaming\Typora\typora-user-images\image-20210715183633267.png" alt="image-20210715183633267" style="zoom: 25%;" />

<img src="C:\Users\eliochiu\AppData\Roaming\Typora\typora-user-images\image-20210715183659761.png" alt="image-20210715183659761" style="zoom: 25%;" />