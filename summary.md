###Manhattan distance vs Mahalanobis distance
欧式距离定义为$$\sqrt{(x_1-x_2)^2+(y_1-y_2)^2+...+(y_n1-y_n2)^2}$$
曼哈顿距离定义为$$|x_1-x_2|+|y_1-y_2| $$
###LSA(SVD)
####SVD奇异值分解
将$M\times N$的矩阵分解成三个$M\times R$,$R\times R$,$R\times N$的矩阵。但是有时原始$M\times N$的矩阵太大，可以采取以下操作简化计算：
1 在$M\times R$矩阵中取前$K$列。
2 在$R\times R$矩阵中取对角线的$K$个元素。
3 在$R\times N$矩阵中取前$K$行。
这三个矩阵的乘积类似于原始矩阵。

####LSA模型
LSA模型全程(Latent semantic Analysis),也称作Latent Semantic Indexing)
