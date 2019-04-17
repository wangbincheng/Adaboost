# Adaboost
AdaBoost对房价进行预测

AdaBoost.py ：利用sklearn 中自带的波士顿房价数据集，比较AdaBoost回归，决策树回归，KNN回归的效果

AdaBoost分类效果.py：使用 sklearn 中的 make_hastie_10_2 函数生成二分类数据。

显示效果：

弱分类器的错误率最高，只比随机分类结果略好，准确率稍微大于 50%。决策树模型的错误率明显要低很多。而 AdaBoost 模型在迭代次数超过 25 次之后，错误率有了明显下降，经过 125 次迭代之后错误率的变化形势趋于平缓。

AdaBoost分类.py: 使用 AdaBoost 算法对泰坦尼克号乘客的生存做预测，和决策树模型对比准确率
