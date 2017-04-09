## 机器学习基石第5讲笔记

机器学习的问题到目前可以拆解为两个

1. 我們希望 Eout 跟 Ein 是很接近的
2. 我们希望Ein尽可能的小

目前我们正在从数学上证明Eout 跟 Ein 的接近程度，前面一节我们已经得到了一个不等式

![](http://static.obeobe.com/image/blog-image/Machine-Learning-Foundations-5-6.png)

本节所有的内容就是在讲述怎么能够将M缩小到一个小的数，于是引出了两个概念

1. 成长函数（growth function）
2. break point

成长函数就是将(x1,x2,…,xn)最大分类可能的函数，break point则是指下一个输入出现的时候，Dichotomies 组合不再是指数成长的那个点



## 总结

机器学习可能的两个核心问题是 Ein 近似于 0，且 Eout 跟 Ein 要接近。PLA 无限多的线我们可以转换成 Effective Number of Lines 也就是转换成 Effective Numbers of Hypotheses，M 无限集合也就转为 mH 的有限集合，然后观察 break point 的出现，让我们可以知道假设集合不会是一个指数型成长的情况，如此依照霍夫丁不等式所说的，我们就可以让机器学习的理论有充分的证明为可行了。



参考：

[林軒田教授機器學習基石 MACHINE LEARNING FOUNDATIONS 第五講學習筆記](http://blog.fukuball.com/lin-xuan-tian-jiao-shou-ji-qi-xue-xi-ji-shi-machine-learning-foundations-di-wu-jiang-xue-xi-bi-ji/)