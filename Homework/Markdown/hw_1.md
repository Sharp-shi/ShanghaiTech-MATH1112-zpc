# <center> hw_1 </center> 

## 练习 1.8 

### (1) 下面两个线性方程组的未知元数量均大于方程的数量, 把它们化成阶梯形方程组, 从而判断它们是否为确定的. 

(a) 

$\begin{cases} 2x + 3y - z &= -5, \\ 3x - y + 4z &= 6; \end{cases}$ 

**解:**

$$\begin{cases}
2x + 3y - z = -5 \\
11y - 11z = -27
\end{cases}$$

$\therefore$  不确定

(b)

$ \begin{cases} x + 2y - z + w &= -3, \\ 4x - 3y + 2z + 3w &= 4, \\ 2x - 7y + 4z + w &= 8. \end{cases}$

**解:**

$$\begin{cases}
x + 2y - z + w = -3 \\
11y - 6z + w = -16 \\
0 = -2
\end{cases}$$

$\therefore$  不确定



### (3) 举例说明方程的数量大于或等于未知元的数量时，方程组可以是无解，有很多解，或只有唯一解。

**解:** 无解:
$$\begin{cases}
x + y = 2 \\
2x + y = 3 \\
x + 2y = 0
\end{cases}$$

多解：
$$\begin{cases}
x + y = 2 \\
2x + 2y = 4 \\
3x + 3y = 6
\end{cases}$$

唯一解：
$$\begin{cases}
x + y = 2 \\
2x + y = 3 \\
x + 2y = 3
\end{cases}$$



## 练习 1.10 

### (1) 判断下列方程组是否是确定的（即是否有解且解是唯一的）：

$$\begin{cases}
x - 3y + 4z = -4 \\
3x - 7y + 7z = -8 \\
-4x + 6y - z = 7
\end{cases}$$

**解:** 

$$\begin{cases} 
x - 3y + 4z = -4 \\ 
2y - 5z = 4 \\ 
0 = 1 
\end{cases}$$
$$\therefore$$ 不确定

### (2) 对 (1) 中线性方程组相伴的齐次线性方程组讨论其解。

**解:** 

$$\begin{cases} 
x - 3y + 4z = 0 \\ 
3x - 7y + 7z = 0 \\ 
-4x + 6y - z = 0 
\end{cases}
\Rightarrow
\begin{cases} 
x - 3y + 4z = 0 \\ 
2y - 5z = 0 
\end{cases}$$
$$\therefore$$ 有无穷解



### (3) 如果方程组 (1.1) 是确定的，证明它相伴的齐次线性方程组 (1.3) 只有零解。举例说明反之不对。

**解:**  证明: 设 (1.1) 的解为 $s_1, \ldots, s_n$。  
若 (1.3) 存在非零解 $\xi_1, \ldots, \xi_n$，由定理 1.9.(3)  
$s_1 + \xi_1, \ldots, s_n + \xi_n$ 为 (1.1) 的解，与 (1.1) 是确定的矛盾。  
所以 (1.3) 只有零解。

举例: 原方程组

$$\begin{cases} 
x  = 1 \\ 
x  = 3 
\end{cases}$$

齐次方程组
$$\begin{cases} 
x  = 0 \\ 
x  = 0 
\end{cases}$$只有零解，原方程组无解



## 练习 1.14  判断下列线性方程组是否有解，在有解时求出它的解：

(1)
$$\begin{cases}
x_1 + x_2 - 3x_3 = -1 \\
2x_1 + x_2 - 2x_3 = 1 \\
x_1 + x_2 + x_3 = 3 \\
x_1 + 2x_2 - 3x_3 = 1
\end{cases}$$

**解:** 

$$\left( \begin{array}{cccc}
1 & 1 & -3 & -1 \\
2 & 1 & -2 & 1 \\
1 & 1 & 1 & 3 \\
1 & 2 & -3 & 1
\end{array} \right) 
\Rightarrow 
\left( \begin{array}{cccc}
1 & 1 & -3 & -1 \\
0 & 1 & -4 & -3 \\
0 & 0 & 1 & 1 \\
0 & 0 & 0 & 1
\end{array} \right)$$
$$\therefore$$ 无解



(2)
$$\begin{cases}
\lambda x_1 + x_2 + x_3 = 1 \\
x_1 + \lambda x_2 + x_3 = 1 \\
x_1 + x_2 + \lambda x_3 = 1
\end{cases}$$

**解:** 

$$\begin{cases}
\lambda = 1 & \text{无穷解} \\
\lambda = 0 & x_1 = x_2 = x_3 = \frac{1}{2} \\
\lambda = -2 & \text{无解} \\
\lambda \neq 0, 1, -2 & x_1 = x_2 = x_3 = \frac{1}{\lambda + 2}
\end{cases}$$



(3)
$$\begin{cases}
x + 5y - 2z = -7 \\
-3x + y + 9z - 5w = 9 \\
4x - 8y - z + 7w = 0
\end{cases}$$

**解:**  $$\left( \begin{array}{ccccc}
1 & 5 & -2 & 0 & -7 \\
-3 & 1 & 9 & -5 & 9 \\
4 & -8 & -1 & 7 & 0
\end{array} \right) 
\Rightarrow 
\left( \begin{array}{ccccc}
1 & 5 & -2 & 0 & -7 \\
0 & 16 & 3 & -5 & -12 \\
0 & 0 & 7 & -1 & -4
\end{array} \right)$$

$$\therefore$$ 无穷解



## 练习 1.15  

## 在平面上引进直角坐标系，求：

### (1) 直线 $a_1 x + b_1 y + c_1 = 0$ 和 $a_2 x + b_2 y + c_2 = 0$ 的交点；

**解:** 

$$\left( \begin{array}{cc} 
a_1 & b_1 & -c_1 \\ 
a_2 & b_2 & -c_2 
\end{array} \right)$$

$$x = \frac{b_1 c_2 - b_2 c_1}{a_1 b_2 - b_1 a_2}$$
$$y = \frac{a_2 c_1 - a_1 c_2}{a_1 b_2 - b_1 a_2}$$

所以交点为 $\left( \frac{b_1 c_2 - b_2 c_1}{a_1 b_2 - b_1 a_2}, \frac{a_2 c_1 - a_1 c_2}{a_1 b_2 - b_1 a_2} \right)$



## 练习 1.21  利用命题 1.16 或命题 1.17 求解下列方程组：

### (1)
$$\begin{cases}
5x_1 + 7x_2 = 3 \\
2x_1 + 4x_2 = 1
\end{cases}$$

$$\therefore$$  $$x_1 = \frac{12 - 7}{20 - 14} = \frac{5}{6}$$
  $$x_2 = \frac{5 - 6}{20 - 14} = -\frac{1}{6}$$



### (2)
$$\begin{cases}
x_1 + 3x_2 + x_3 = 4 \\
-x_1 + 2x_3 = 1 \\
3x_1 + x_2 = 1
\end{cases}$$

$$\therefore$$  $$x_1 = \frac{1 \times (0 - 2) + 1 \times (0 - 1) + 3 \times 6}{-2 - 1 + 1 \times 8 }= -\frac{1}{15}$$
$$x_2 = \frac{1 \times (0 - 2) + 1 \times (0 - 1) + 3 \times 6}{-2 - 1 + 1 \times 8}= \frac{6}{5}$$
$$x_3 = \frac{1 \times (0 - 1) + 1 \times (3 - 4) + 3 \times 3}{15} = \frac{7}{15}$$





## 习题 1.5

### 1. 求实系数二次多项式 $f(x)$ 使得 $f(1) = 8$, $f(-1) = 2$, $f(2) = 14$.

**解：**设 $f(x) = ax^2 + bx + c$ ($a \neq 0$)

$$\begin{cases}
f(1) = a + b + c = 8 \\
f(-1) = a - b + c = 2 \\
f(2) = 4a + 2b + c = 14
\end{cases}$$

解得：
$$\begin{cases}
a = 1 \\
b = 3 \\
c = 4
\end{cases}$$

$$\therefore$$  $$f(x) = x^2 + 3x + 4$$



### 2. 求实系数三次多项式 $f(x)$ 使得 $f(-2) = 1$, $f(-1) = 3$, $f(1) = 13$, $f(2) = 33$.

**解：**设 $f(x) = ax^3 + bx^2 + cx + d$ ($a \neq 0$)

$$\begin{cases} 
f(-2) = -8a + 4b - 2c + d = 1 \\
f(-1) = -a + b - c + d = 3 \\
f(1) = a + b + c + d = 13 \\
f(2) = 8a + 4b + 2c + d = 33 
\end{cases}$$

解得：
$$\begin{cases}
a = 1 \\
b = 3 \\
c = 4 \\
d = 5
\end{cases}$$

$$\therefore$$  $$f(x) = x^3 + 3x^2 + 4x + 5$$



### 3. 计算下列行列式：

 (2)
$$\begin{vmatrix}
\cos \alpha & -\sin \alpha \\
\sin \alpha & \cos \alpha
\end{vmatrix}$$

**解：**原式 = $\cos^2 \alpha + \sin^2 \alpha = 1$



 (4)
$$\begin{vmatrix}
3 & 2 & 1 \\
4 & 5 & 6 \\
-2 & 1 & 5
\end{vmatrix}$$

**解：**原式 = $3 \times (25 - 6) - 4 \times (10 - 1) - 2 \times (12 - 5)$  

$= 3 \times 19 - 4 \times 9 - 2 \times 7$  
$= 57 - 36 - 14 = 7$



 (6)
$$\begin{vmatrix}
1 & 0 & 1+i \\
0 & 1 & i \\
1-i & -i & 1
\end{vmatrix}$$($i$为虚数单位，即 $i^2 = -1$)

**解：**原式 = $1 \times (1 - 1) + (1 - i)(-1 - i)$  

$= -1 - i + i - 1$  
$= $ -2

