# hqdsg
svm是英文support vector machine的缩写，字面意思就是支持向量的机器，svm是一种算法，这个算法只与支持向量有关，在二维中就是为了找到一条直线
使得支持向量到这条直线的距离最大。按照我的理解就像是找两个点之间的中线一样，通过特征分隔开具有不同特征的个体。二维上是分隔的线，三维空间中可
以是立方体的面之类的。总之SVM就是找分隔的线或者是面。

鸢尾花分类在两个特征的时候只有两维，也是找分隔的线，决策函数决定在拟合这个分隔线上的点是否可取，是寻找分隔线的标准
惩罚系数决定取错点后偏移更改的幅度，惩罚系数越大，要求越苛刻，得到的结果越准确。

鸢尾花分类也是通过训练模型核函数不断更改权重也就是分隔线的各个坐标点，最后用实际测试数据来判断准确率。
