# numpy [教程]([https://www.numpy.org.cn/article/basics/understanding_numpy.html#%E4%BB%80%E4%B9%88%E6%98%AF-numpy](https://www.numpy.org.cn/article/basics/understanding_numpy.html#什么是-numpy))

## 什么是numpy

​	主要是用于多维数组的计算

+ 和c++数组操作基本机制，数组下标也是从0开始 通过numpy. **注意有点** 加方法 

  然后可以使用类似于matlab中数组方法取数组中的某一部分，提取多维数组的行/列

  ```python
  import numpy as np
  x=np.zeros(5)
  print(x)
  y=np.ones([2,4])
  print(y)
  z=np.random.random(2)
  print(z)
  x1=np.array([[2,3],[1,4]])
  print(x1)
  y1=np.array([[2,2],[1,1]])
  print(y1)
  print(x1[1][1])
  print(x1[:,1])//第二列
  a=x1*y1
  print(a)
  b=x1.dot(y1)
  print(b)
  ```

  

##numpy数组

大部分和python本身的数组操作类似

​     