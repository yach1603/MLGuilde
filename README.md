# MLGuilde
这个是用于机器学习导引的课程论文的实验代码。

主要包含MyLR.ipynb一个文件。

# 代码环境
python 3.6.8

numpy 1.19.4

pandas 1.0.5

scikit-learn 0.23.2

# 代码模块
## sigmodFormatrix(Xb,betas)
输入：Xb为矩阵、betas为参数向量

输出：一个对数几率向量

功能：结合给定的样本和参数向量，求对应的每个X对应的对数几率

## sigmodFormatrix2(Xb,betas)
输入：Xb为矩阵、betas为参数向量
输出：分类类别向量
功能：结合给定的样本和参数向量，预测每个X对应所属的类别

## sigmod(Xi,betas)
输入：Xi为第i个样本、betas为参数向量

输出：对应的类别值

功能：结合给定的样本和参数向量，预测对应所属的类别

## normalize(x)
输入：X为样本矩阵

输出：矩阵

功能：对所有特征值进行归一化处理

## LinearLogsiticRegression.fit(self,X,y,alpha = 0.01,accuracy = 0.00001)
输入：样本特征X，样本标记向量y，步长alpha，收敛阀值accuracy

输出：参数向量

功能：使用梯度下降法结合损失函数求最优参数

## LinearLogsiticRegression.JFunc(self,X,y)
输入：样本特征X，样本标记向量y

输出：经验损失值

功能：根据当前的参数计算模型预测的结果与实际值之间的经验损失值

## LinearLogsiticRegression.predict(self,X)
输入：样本特征X

输出：预测结果向量

功能：根据当前的参数计算模型预测的结果

## LinearLogsiticRegression.score(X_test,y_test)
输入：测试集样本特征X，测试集样本标记向量y

输出：预测结果的精确率

功能：结合当前模型参数,对测试集进行预测并计算结果的精确率

# 实验结果
根据每次运行时重新划分的数据集所得到的结果都会不一样.
