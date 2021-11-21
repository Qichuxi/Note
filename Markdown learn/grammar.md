# hello world\
# 一级标题
## 二级标题
### 三级标题
### 段落
这是第一段

这是第二段，两端之间记得空行。

### 分割线
三条横线表示分割线

---

分割以下

### 加粗，斜体和删除线,还有高亮

**这是加粗**

*这是斜体*

~~这是删除线~~

==这是高亮==

快捷键记录： 选中文本 Ctrl + B 给文本加粗
            Ctrl + I 给文本变斜体

### 列表

* 无序列表
  * 嵌套下的无序列表
  * 再来一个

注意嵌套下的列表要打两个空格

1. 有序列表1
   1.嵌套的有序列表
   2.嵌套2

2. 有序列表3

任务列表

- [x] 已经完成的事 1
- [x] 已经完成的事 2
- [ ] 未完成的事

快捷键：缩进
Ctrl + [ 向左 另一个 向右

### 引用和代码
> 这样子引用别人说的话
> by 。。。。

行内如何引用，这样子写 `行内代码` 

代码块语法

``` python
print("hello world")
```

### 超链接和图片
[超链接名称](链接地址)
![图片提示语](图片地址)

（注意，以上填网络地址）

本地建立链接

[other](other.md)
![提示语](本地链接)
![07wallpaper](1.jpg)
这是本目录添加

如何添加不同目录下的图片

![07example](../../picture/1.jpg)
貌似不太行

### 剪切板图片插入
复制图片，然后Ctrl + Alt + V 就可以将图片自动保存到当前目录并正确黏贴到Markdown文件中
![剪切板插入图片](image/2021-11-17-22-58-07.png)

### 表格

| 表头 | 表头 |
| ---- | ---- |
| 内容 | 内容 |
| 内容 | 内容 |

拓展功能

| 表头 | 表头 |
| ---- | ---- |
| 内容 | 内容 |
|^     | 内容 |

(好像不太行)


快捷键 自动对齐表格： Shift + Alt + F

### 注释

快捷键 Ctrl + \
将当前行注释掉
<!--你看不见我-->
<!--多行注释

就像这样-->

VScode每一次修改代码都会重新渲染一遍，如果数学公式较多，分成多个文件，避免单文件过大，

## 数学公式支持

行内公式：
首位$

单位圆 $x^2+y^2=1$

公式块：
$$
\begin{cases}
x=\rho\cos\theta\\
y=\rho\sin\theta\\
\end{cases}
$$
**注意不要在公式内使用中文**

### 上标和下标

上标 ^
下标 _

### 分式

较小的行内分数 $\frac{1}{2}$

展示型的分式 $\displaystyle\frac{x+1}{x-1}$

### 根式
开平方 $\sqrt{2}$

开$n$次方 $\sqrt[n]{2}$

### 空格

数学公式中的空格和换行会被忽略

紧贴 $a\!b$

没有空格 $ab$

小空格 $a\,b$

中等空格 $a\;b$

大空格 $a\ b$

quad 空格 $a\quad b$

两个quad空格 $a\qquad b$

### 累加，累乘和积分

累加 $\sum_{k=1}^n\frac{{1}}{k} \quad \displaystyle\sum_{k=1}^n\frac{1}{k^2}$

累乘 $\prod_{k=1}^n\frac{l}{k} \quad \displaystyle\prod_{k=1}^n\frac{1}{k}$

积分 $\displaystyle \int_0^1x{\rm d}x \quad \iint_{D_{xy}} \quad \iiint_{\Omega_{xyz}}$

### 用括号修饰

圆括号 $\displaystyle \left( \right)$

放括号 $\displaystyle \left[\sum_{k=1}^{n}\frac{1}{k^2} \right]^2$

花括号 $\displaystyle \left\{ \right\}$

尖括号 $\displaystyle \left\langle\sum_{i=1}^{n}x \right\rangle\^2$

### 多行算式对齐
居中：

$$
\begin{aligned}
xxxxx &=yyyyy\\
&=cccccc\\
\end{aligned}
$$

左对齐：换成$

### 方程组

$$
\begin{cases}
k_{11}x_1+k_{12}x_2+\cdots+k_{1n}x_n=b_1 \\
k_{21}x_1+k_{22}x_2+\cdots+k_{2n}x_n=b_2 \\
\cdots \\
k_{n1}x_1+k_{n2}x_2+\cdots+k_{nn}x_n=b_n \\
\end{cases}
$$

### 矩阵

$$
\begin{pmatrix}
1 & 1 &