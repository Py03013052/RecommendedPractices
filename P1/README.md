## Practice 1

**Data Analysis**(15)：Statistics, regression and visualization

* Deadline: 2021.05.03

## Problem

John V. Guttag. Introduction to Computation and Programming Using Python: With Application to Understanding Data(Second Edition). MIT Press, 2016. 

**21.5 Statistical Measures Don't, Tell the Whole Story**（Page411-412） 
  
In 1973, the statistician F.J. Anscombe published a paper containing the table below. It contains the <x, y> coordinates of the points in each of four data sets.

|x |y|x|y|x|y|x|y|
| ---- |:------:| :------:| :------:|  :------:| :------:| :------:|  ----:|
|10.0|	8.04 |	10.0|	9.14 |	10.0 	|7.46	|8.0    |6.58|
|8.0| 	6.95 |	8.0 |	8.14 |	8.0     |6.77	|8.0    |5.76|
|13.0| 	7.58 |	13.0|	8.74 |	13.0    |12.74	|8.0    |7.71|
|9.0|	8.81 |	9.0 |	8.77 |	9.0     |7.11	|8.0    |8.84|
|11.0| 	8.33 |	11.0|	9.26|	11.0    |7.81	|8.0    |8.47|
|14.0| 	9.96 |	14.0|	8.10 |	14.0    |8.84	|8.0    |7.04|
|6.0|	7.24 |	6.0 |	6.13 |	6.0     |6.08	|8.0 	|5.25|
|4.0| 	4.26 |	4.0 |	3.10| 	4.0     |5.39	|19.0 	|12.5|
|12.0|	10.84| 	12.0| 	9.13| 	12.0    |8.15	|8.0 	|5.56|
|7.0| 	4.82 | 	7.0 |	7.26| 	7.0     |6.42	|8.0 	|7.91|
|5.0| 	5.68 | 	5.0 | 	4.74| 	5.0     |5.73	|8.0 	|6.89|

## 要求(10分)：

使用Jupyter Notebook实现 
  
* 1 读取数据文件及使用List,Dict表达数据分析对象(3)：数据文件[Anscombe.csv](./Anscombe.csv)(自己编码,不可使用软件包)
  * **提示**： 抽象被分析的数据，使用适当的**数据结构**定义数据对象变量

* 2 统计指标计算和输出(3分)：
    * 计算均值、方差和相关系数统计指标（2分， 自己编码，不使用软件包)；
    * 使用字符输出统计结果表格(1分，自己编码，不使用软件包) 

参考输出结果表格
```
─────────────────────────────────────────────────
  No   x-avg  x-pvar  y-avg  y-pvar   pearson_r  
─────────────────────────────────────────────────
  1     9.0    10.0    7.5    3.75     0.816 
  2     9.0    10.0    7.5    3.75     0.816 
  3     9.0    10.0    7.5    3.75     0.816 
  4     9.0    10.0    7.5    3.75     0.817 
─────────────────────────────────────────────────
``` 
* 3 线性回归和图形输出(2分): **线性回归**(1分,可使用Numpy或Scipy)；多图输出（1分,使用Matplotlib）

   参考输出图
   
   ![数据点图和回归曲线](Anscombe.png)

* 4 小结(2)：设计中遇到的问题、解决过程, 工作体会

## 提交：

* 1 电邮：cmh@seu.edu.cn 
  * 主题：学号-姓名-1
  * 附件：程序文件压缩包：**学号-姓名-1.zip**

* 2 截至时间：2021.05.03
  *  截至时间后可补交，补交得分<=6. (2020.06.21)

## 参考：

* [List,Dict and Data Table(Files)](http://nbviewer.ipython.org/github/PySEE/home/tree/S2021/notebook/Unit1-5-Files.ipynb)

* [PLOTTING USING MATPLOTLIB](http://nbviewer.ipython.org/github/PySEE/home/tree/S2021/notebook/Unit2-1-PLOTTING-USING-MATPLOTLIB.ipynb)

* [UNDERSTANDING EXPERIMENTAL DATA](http://nbviewer.ipython.org/github/PySEE/home/tree/S2020/notebook/Unit2-2-UNDERSTANDING_EXPERIMENTAL_DATA.ipynb)

* [LIES_DAMNED_LIES_AND_STATISTICS](http://nbviewer.ipython.org/github/PySEE/home/tree/S2021/notebook/Unit2-3-LIES_DAMNED_LIES_AND_STATISTICS.ipynb)




