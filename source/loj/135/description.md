
# 题目描述

这是一道模板题。

给定一个大小为 $N \times M$ 的零矩阵，直到输入文件结束，你需要进行若干个操作，操作有两类：

 - `1 a b c d x`，表示将左上角为 $(a,b)$，右下角为 $(c,d)$ 的子矩阵全部加上 $x$；

 - `2 a b c d`，表示询问左上角为 $(a,b)$，右下角为 $(c,d)$ 为顶点的子矩阵的所有数字之和。

# 输入格式

第一行两个正整数 ，其中 $n,m$ 分别表示矩阵的行数与列数。

接下来若干行直到文件结束，均代表你需要进行的操作。

# 输出格式

对于每个 `2` 操作，输出一行代表查询的结果。

# 样例

#### 样例输入
```plain
4 4
1 1 1 3 3 2
1 2 2 4 4 1
2 2 2 3 3
```
#### 样例输出
```plain
12
```

# 数据范围与提示

对于 $10\%$ 的数据，$1 \le n,m \le 16$，操作不超过 $200$ 个；  
对于 $60\%$ 的数据，$1 \le n,m \le 512$；  
对于 $100\%$ 的数据，$1 \le n,m \le 2048,\lvert x \rvert \le 500$，操作不超过 $2\times 10^5$ 个，保证运算过程中及最终结果均不超过 $64$ 位带符号整数类型的表示范围，并且修改与查询的子矩阵存在。
			