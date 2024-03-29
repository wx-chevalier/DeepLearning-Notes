# ReLU 函数

ReLU（rectified linear unit）函数提供了一个很简单的非线性变换。给定元素 $x$，该函数定义为：

$$
\operatorname{ReLU}(x)=\max (x, 0)
$$

![ReLU 对比](https://assets.ng-tech.icu/item/20230416205129.png)

显然，当输入为负数时，ReLU 函数的导数为 0；当输入为正数时，ReLU 函数的导数为 1。尽管输入为 0 时 ReLU 函数不可导，但是我们可以取此处的导数为 0。
