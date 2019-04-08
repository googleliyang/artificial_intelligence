## 学习人工智能需要开启记忆模式！

*Any knowledge point is not missed*



## 开发步骤



*获处特机模*



## 距离度量

大公司足够了，同类型书籍比的话

欧曼(城市街区距离)切汉马，标闵杰， 巴氏系数



![distance](images/distance.png)



## Workflow



1. 机器学习流程

   ![Xnip2019-04-03_22-18-56](images/Xnip2019-04-03_22-18-56.png)



## Tip

1. KNN

   - (K临近算法)是用来解决高纬度问题，实现降纬， k 值越大 容易 **低拟合**, 小容易 **过拟合**

   - 缺点:

     - ![Xnip2019-04-03_22-51-37](images/Xnip2019-04-03_22-51-37.png)

2. K树检索

   - TODO 画圆那里

3. 拟合

   - 过拟合特点: 训练样本准，测试集不准

   - 欠拟合特点: 训练，测试集都不准

4. 维灾难: 欠拟合 -> 过拟合

   1. 信息增益越大，则这个条件的影响越大

5. 维度：数据特征(csv数据文件, lable), 样本: 数据

6. 二维叫平面，超过三维叫超平面

7. 每增加一个特征便增加一维

8. 评价模型在训练集和测试集的表现 "拟合"

9. 维灾难，随着维度地增加分类器的性能逐渐上升，达到某点后维度开始降低

10. 决策树之熵，熵越低越密集

11. 箱形图（Bot-plot）,盒须图, 显示数据分散情况的图

    ![Xnip2019-04-05_12-25-28](/Users/ly/Desktop/python_/ai_rem/images/Xnip2019-04-05_12-25-28.png)


## Keywords

```
sklearn  
```



## Photo



### 1.熵（用H表示）值计算

![Xnip2019-04-05_21-14-37](/Users/ly/Desktop/python_/ai_rem/images/Xnip2019-04-05_21-14-37.png)



###2. 



## Mathematics



1. 正态分布： 又叫高斯分布，两边低，中间高： 未完

2. 常用符号 B, E(求和)，ln, log， (自查补全)

3. 方差，标准差

   ```
   方差是各个数据分别与其平均数之差的平方的和的平均数(方差（Variance）用来度量随机变量和其数学期望（即均值）之间的偏离程度)
   
   标准差是方差的算术平方根。σ表示
   
   
   ```

4. 数学符号学习

   ```
   f([x1, x2, x3, x4..]) = Y # f 表示经过funtion对x1..x4特征的运算，得出某个(ppt回归)值	
   ```


![Xnip2019-04-05_13-21-19](/Users/ly/Desktop/python_/ai_rem/images/Xnip2019-04-05_13-21-19.png)

4. Ln, 与 le

   以2为底，记作lb， 单位bit
   以e为底，记作ln， 单位nat

5. 线性函数

   

   ![Xnip2019-04-08_21-21-06](/Users/ly/Desktop/python_/ai_rem/images/Xnip2019-04-08_21-21-06.png)

   y=ax函数(a为常数且以a>0，a≠1)叫做指数函数

   ![Xnip2019-04-08_21-36-16](/Users/ly/Desktop/python_/ai_rem/images/Xnip2019-04-08_21-36-16.png)

   ![Xnip2019-04-08_21-38-23](/Users/ly/Desktop/python_/ai_rem/images/Xnip2019-04-08_21-38-23.png)

   

   6. 方差，标准差为方差的算术平方根

      ​	如果只是要描述样本数据间的[离散程度](https://www.baidu.com/s?wd=%E7%A6%BB%E6%95%A3%E7%A8%8B%E5%BA%A6&tn=SE_PcZhidaonwhc_ngpagmjz&rsv_dl=gh_pc_zhidao)，则样本方差计算公式中的除数应为"n”。

      ![Xnip2019-04-08_23-25-00](/Users/ly/Desktop/python_/ai_rem/images/Xnip2019-04-08_23-25-00.png)

   

   7. 符号

   ​      var X的方差,记为D(X),Var(X)或DX 

   ​     大写的Δ是用来表示变化量的符号。 而小写*δ*通常在高等数学中用于表示变量或者   符号

   <https://blog.csdn.net/dlhlSC/article/details/72847273>

   

## ISSUE

1. AUC 由来

   如下矩阵便是混淆矩阵

   ![Xnip2019-04-03_23-15-14](images/Xnip2019-04-03_23-15-14.png)



​	ROC 曲线 受试者工作特征*曲线*，便是由诸多样本数据变化上图1线，生成多个混淆矩阵计算TPR 和 FPR ，生成, x, y 坐标，所画出的曲线

​	







1. 回归率，f系数的作用, B 发音

   ```
   # 有时候我们对精确率和召回率并不是一视同仁，引入一个你参数 来度量二者关系，B > 1 召回率更有影响，B=1 时，影响一致(F1) ，含有度量参数 B 的 F1 记为 FB
   ```

   ![Xnip2019-04-03_22-33-01](images/Xnip2019-04-03_22-33-01.png)

   ​		

![Screen Shot 2019-04-03 at 9.54.15 PM](images/Screen Shot 2019-04-03 at 9.54.15 PM.png)





3. 标签与特征

   *当没有标签的时候，则可以把相似的数据归为一类，再根据分类定点推广，或异常检测(消费分析，突然大笔消费等)，这是聚类算法*

   ![Xnip2019-04-05_12-53-40](/Users/ly/Desktop/python_/ai_rem/images/Xnip2019-04-05_12-53-40.png)





4. 复杂度 阶指幂对

5. K树的检索(阿里面试如何实现很多维度下的快速检索)

   ```
   knn 算法指定k值后，使用 k树的检索，查找这 k 个点，可以降低高纬度，在以x(x1, x2), x1 找到节点后，需要回溯到根节点(判断是否与线有相交，如有说明可能有更近的点，因为 x2 变量的缘故，这也是回溯的原因)
   ```



   ![Xnip2019-04-05_15-42-38](/Users/ly/Desktop/python_/ai_rem/images/Xnip2019-04-05_15-42-38.png)


6. 决策树熵画图

   *左侧，只是赋予等值，右边为熵的计算公式。右侧正态分布图，当概率值p值为0，和 1 时，熵为0/1因为确定发生*

   ![Xnip2019-04-05_21-19-49](/Users/ly/Desktop/python_/ai_rem/images/Xnip2019-04-05_21-19-49.png)



7. K-means 算法中间过程质心变化没理解

![Xnip2019-04-07_21-26-46](/Users/ly/Desktop/python_/ai_rem/images/Xnip2019-04-07_21-26-46.png)

8 区别还是不很清楚，CH SC系数



9 公式含义

![Xnip2019-04-08_22-31-25](/Users/ly/Desktop/python_/ai_rem/images/Xnip2019-04-08_22-31-25.png)



## Others

![Xnip2019-04-03_23-36-16](images/Xnip2019-04-03_23-36-16.png)







## TODO



1. 算法图解
2. [中国平安](https://www.zybuluo.com/rianusr/note/1315377)  [中国平安](https://www.jianshu.com/u/16236007e0b0?utm_campaign=hugo&utm_medium=reader_share&utm_content=user&utm_source=weixin-friends)
3. 机器学习周志华，机器学习李航(每日读，纸质书购买)
4. 面经当做交流，以及day1作业
5. 像无数枝叶的知识点，进行xmind画图，是不适合完全展开的
6. 对问题的本质还是每个人建立一套自己的理解比较好
7. 不管怎么说，自己都要给自己一个结果
8. 既然是最后那就认真走完
9. 学习算法步骤
   - 算法，时间&空间复杂度，优点，缺点，公式，算出来的值大小是好还是坏, 函数中的应用，再加 xmind