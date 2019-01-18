# 初衷

---

![](https://p1.ssl.qhmsg.com/dr/270_500_/t01498c7b69f6323278.jpg?size=375x472)

传统机器学习和数据科学方面的书前前后后也看了不少中外版本，Jordan、Hastie、Bishop、周志华等大拿的名著很多人也是耳熟能详，但个人最喜欢的还是李航博士的《统计学习方法》和Simon Rogers的《机器学习基础教程》，两位大拿的书都不厚，所以在有限篇幅把问题写清楚更考验作者的水平，李航博士的EM算法写的很透，是自己看过所有版本里最好的，在传统机器学习理论里很多人更看重svm算法，而低估了EM算法，个人认为EM算法更重要，因为它是一种更通用的计算框架，不仅在传统机器学习，在深度学习和强化学习都起到很重要的作用。另外，Rogers的书貌似国内很多人提的不多，但他写的线性模型是看过的书里写的最透的，不少人觉得线性模型太简单，其实里面东西是很多的，深入下去其实也没那么简单，之前看到过一个华裔学生整理的线性模型pdf足足有102页，另外Rogers写的贝叶斯方法及推理也很棒，特别是里面的公式推导。

![](https://p.ssl.qhimg.com/dmsmfl/120_75_/t016c6de1c7c7fcf6db.png?size=591x400&phash=6897457096129765387)

另外，Julia语言是目前接触的科学计算语言里最喜欢的，优点太多了，首先写出来的代码看起来就舒服，嗯，代码颜值高，学过Matlab、R和Python的同学如果学Julia的话会看到很多相似的地方，不过学习过程其实不像官方说的如Python一样简单（个人也没觉得Python简单）。去年底，Julia自12年开始开发经过6年发展终于出了1.0版，所以自己打算用Julia简单写李航博士书里的算法，除一些很基础的包外，尽量不调用第三方包写核心算法，水平有限，能写几个写几个，从目前写的几个来看，Julia的速度优势太明显了，这还是没有对代码进行优化的情况下！