---
layout: article
title: 二维容器vector的初始化
---

### 二维容器vector的初始化

直接看一下二维容器初始化代码：

~~~
vector<vector<int>> table(size1, vector<int>(size2, value));
~~~

声明一个名为table的容器，其元素为vector的容器；size1为vector容器个数，即一维大小；size2为vector容器大小，即为二维大小，value为初始化数值。

##### 推广 三维

~~~ 
vector<vector<vector<int>>> cube(size1, vector<vector<int>>(size2, vector<int>(size3, value)));
~~~

这里size1为二维vector容器个数，size2为一维vector容器个数，size3则为一维vector容器元素个数，value为初始化数值。