# 使用支持向量机SVM进行虚假新闻检测

SVM是一个机器学习模型，仅根据帖子描述和其他元数据来预测描述新闻事件的推文真假，ML模型将是一个文本分类器，它不会处理图像。

可用于训练ML模型的数据包括来自2015年MediaEval挑战赛的推特数据集。这些社交媒体上的大部分帖子都描述了一些事件，比如飓风桑迪和波士顿马拉松爆炸案。

这个ML模型的成功度量是f1分数(准确性)。这个分数是0到1之间的值，数值越大表示精度和查全率越好。

# #结果
-具有CountVectorizer的线性支持向量机SVM(精度:0.82)
-带TF-IDF矢量的线性支持向量机SVM(精度:**0.88**)
# #引用

**MediaEval 2015** - [http://www.multimediaeval.org/mediaeval2015/verifyingmultimediause/](http://www.multimediaeval.org/mediaeval2015/verifyingmultimediause/)

