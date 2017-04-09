## 机器学习基石第7讲

回顾之前讲的，总结起来就是：

1. 好的假设集合（H），dvc小
2. 好的资料集（D），N足够大
3. 好的演算法（A），Ein足够小

![](http://static.obeobe.com/image/blog-image/Machine-Learning-Foundations-7-3.png)



## 简单 v.s 复杂

机器学习最关心的两个基本问题是：

1. Ein和Eout要足够接近
2. Ein要足够小

![](http://beader.me/mlnotebook/section2/images/model_complexity_curve.png)

随着dvc的上升，Ein不断降低，而Ω（模型复杂度）项不断上升，他们的上升与下降的速度在每个阶段都是不同的，因此我们能够寻找一个二者兼顾的，比较合适的d∗vc，用来决定应该使用多复杂的模型。

反过来，如果我们确定了dvc，而且想要保住ϵ=0.1，置信度1−δ=90%，那需要多少笔N呢？我们需要N≈10,000dvc笔数据，但 VC Bound 事实上是一个极为宽松的 bound，因为它对于任何演算法A，任何分布的数据，任何目标函数f都成立，所以经验上，常常认为**N≈10dvc**就可以有不错的结果。