
# 题目描述

这是一道模板题。

给出一个 $n\times m$ 的零矩阵 $A$，你需要完成如下操作：

- `1 x y k`：表示元素 $A_{x,y}$ 自增 $k$；
- `2 a b c d`：表示询问左上角为 $(a,b)$，右下角为 $(c,d)$ 的子矩阵内所有数的和。

# 输入格式

输入的第一行有两个正整数 $n,m$；  
接下来若干行，每行一个操作，直到文件结束。

# 输出格式

对于每个 `2` 操作，输出一个整数，表示对于这个操作的回答。

# 样例

#### 样例输入
```plain
2 2
1 1 1 3
1 2 2 4
2 1 1 2 2
```
#### 样例输出
```plain
7
```

# 数据范围与提示

对于 $10\%$ 的数据，$n=1$；  
对于另 $10\%$ 的数据，$m=1$；  
对于全部数据，$1\le n,m\le 2^{12},1\le x,a,c\le n,1\le y,b,d\le m,|k|\le 10^5$，保证操作数目不超过 $3\times 10^5$，且询问的子矩阵存在。
			