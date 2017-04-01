## 机器学习基石第三讲笔记

先回顾下第二讲，用一句话总结就是：算法A通过观察数据集合（linear separable）D和假设集合(perceptrons)H去得到一个更好的假设g

![](http://static.obeobe.com/image/blog-image/machine-learning-foundations-3-0.png)

第三讲主要介绍各种机器方法，角度有4个：

1. 根据输出空间y的不同
2. 根据输出y标签的不同
3. 根据



## 从输出y的角度

- 从输出 Y 的角度看机器学习，Y 只有两个答案选一个，就叫 BINARY CLASSIFICATION
- 从输出 Y 的角度看机器学习，Y 有多个答案选一个，就叫 MULTICLASS CLASSIFICATION
- 从输出 Y 的角度看机器学习，Y 为一个实数，就叫 REGRESSION
- 从输出 Y 的角度看机器学习，Y 为一个结构序列，就叫 STRUCTURED LEARNING

总结下：从输出 y 的角度看机器学习，如果 y 是两类，那就是 Binary Classification；如果 y 是 k 类，那就是 Multiclass Classification；如果 y 是一个实数，那就是 Regression；如果 y 是一种结构关系，那就是 Structured Learning



## 从输出y的标签看

- 从输入的数据 YN 的角度看机器学习，如果每个 XN 都有明确对应的 YN，这就叫监督式学习（SUPERVISED LEARNING）
- 从输入的数据 YN 的角度看机器学习，如果每个 XN 都没有标示 YN，这就叫非监督式学习（UNSUPERVISED LEARNING）
- 从输入的数据 YN 的角度看机器学习，如果 XN 只有部分有标示 YN，这就叫半监督式学习（SEMI-SUPERVISED LEARNING）
- 从输入的数据 YN 的角度看机器学习，如果 YN 是很难确知描述的，只能在机器作出反应时使用处罚及奖励的方式让机器知道对或错，这就叫增强式学习（REINFORCEMENT LEARNING）



![](http://static.obeobe.com/image/blog-image/machine-learning-foundations-3-8.png)

![](http://static.obeobe.com/image/blog-image/machine-learning-foundations-3-9.png)

从输入的数据 Yn 的角度看机器学习，如果明确告知每个 Yn，那就是监督式学习；如果没有告知任何 Yn，那就是非监督式学习；如果只有部份 Yn 的数据，那就是半监督式学习；如果是用奖励、处罚的方式来告知 Yn，那就是增强式学习



## 从喂给机器数据的角度看

- 从喂数据给机器的角度看机器学习，一次喂进全部数据，这就叫 BATCH LEARNING
- 从喂数据给机器的角度看机器学习，可以再慢慢喂进新数据，这就叫 ONLINE LEARNING
- 从喂数据给机器的角度看机器学习，机器可以问问题，然后从问题的答案再喂进数据，这就叫 ACTIVE LEARNING

从喂数据给机器的角度看机器学习，如果一次喂进所有数据，就叫 Batch Learning；如果后续可以再慢慢喂进数据，就叫 Online Learning；如果机器可以问问题来喂进数据，就叫 Active Learning。



## 从输入x的角度看

- 从输入 X 的角度看机器学习，如果 X 的特征很明确定义，这就叫 CONCRETE FEATURE
- 从输入 X 的角度看机器学习，如果 X 的特征是用最基础未人为整理过的，这就叫 RAW FEATURE
- 从输入 X 的角度看机器学习，如果 X 的特征是抽象的像是编号这样的数据，这就叫 ABSTRACT FEATUR

从输入 X 的角度看机器学习，如果 X 是明确定义的，那就是 Concrete Feature；如果 X 是未经人为定义过的，那就是 Raw Feature；如果 X 是抽象的编号，那就是 Abstract Feature



## 总结

从输出 y 的角度看机器学习、从输入的数据 Yn 的角度看机器学习、从喂数据给机器的角度看机器学习、从输入 X 的角度看机器学习都会有许多不同的机器学习方法，但重要的是了解哪些是核心，其他机器学习方法也都是从这些核心发展而来



![](http://static.obeobe.com/image/blog-image/machine-learning-foundations-3-19.png)





参考：[林軒田教授機器學習基石 MACHINE LEARNING FOUNDATIONS 第三講學習筆記](http://blog.fukuball.com/lin-xuan-tian-jiao-shou-ji-qi-xue-xi-ji-shi-machine-learning-foundations-di-san-jiang-xue-xi-bi-ji/)

