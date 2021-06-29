markdown常用语法
[TOC]
# 分割线

---

789
# 加粗、斜体、删除、高亮
**重点加粗**
*斜体*
~~删除线~~
==高亮==

快捷键
> 加粗 ctrl + b
> 斜体 ctrl + i

# 列表
* 无序列表
    * 嵌套无序列表
    * 嵌套无序列表

1. 有序列表1
   1. 嵌套有序列表1
   2. 嵌套有序列表2
2. 有序列表2
3. 有序列表3
   
任务列表
- [x] 已经完成的事1
- [x] 已经完成的事2
- [ ] 未完成的事1
- [ ] 未完成的事2

# 缩进
缩进快捷键  
> ctrl + [ 
> ctrl + ]

# 行内代码
这是`行内代码`的写法

```cpp
printf("hello world!\n");
```
有行数的行内代码
```cpp{.line-numbers}
int a;
int b;
int c=a+b;
printf("%d\n",c);
return 0;
```
# 超链接和图片
[pixiv-むう](https://www.pixiv.net/users/5048314)
![zhihu](https://pic2.zhimg.com/80/v2-c35303b43639b37a18b8893e906d7435_720w.png)

使用image paste 快捷键
>ctrl + alt + v


![use image paste](image/2021-06-09-20-54-13.png)

# 表格
| 表头 | 表头 |
| ---- | ---- |
| 内容 | 内容 |
| 内容 | 内容 |

#注释

<!-- 注释 -->
<!-- 多行
注释 -->

注释、反注释快捷键
>ctrl + /
# 公式
## 上下标
上标 $x^2+y^{2}=1$
下标 $x_2+y_{2}=1$
## 分式
分数$\frac{1}{2}$
展示型分式$\displaystyle\frac{x-1}{x+1}$
## 开方
开平方$\sqrt(2)$
开n次方$\sqrt[n]{2}$
## 空格
紧贴 $a\!b$
无空格 $ab$
小空格 $a\,b$
中空格 $a\;b$
大空格 $a\ b$
quad空格 $a\quad b$
两个quad空格 $a\qquad b$
## 累加、累乘、积分
### 累加 
$\sum_{k=1}^n\frac{1}{k}\quad \displaystyle\sum_{k=1}^n\frac{1}{k}$

### 累乘 
$\prod_{k=1}^n\frac{1}{k}\quad \displaystyle\prod_{k=1}^n\frac{1}{k}$

### 积分 
$\displaystyle \int_0^1x{\rm dx}\quad \displaystyle\iint_{D_{xy}}\quad \displaystyle\iiint_{\Omega_{xyz}}$
## 括号
### 圆括号 
$\displaystyle \left(\sum_{k=1}^n\frac{1}{k}\right)$
### 方括号 
$\displaystyle \left[\sum_{k=1}^n\frac{1}{k}\right]$
### 花括号 
$\displaystyle \left\{\sum_{k=1}^n\frac{1}{k}\right\}$
<!-- 花括号需多加\ -->
### 尖括号 
$\displaystyle \left\langle\sum_{k=1}^n\frac{1}{k}\right\rangle$
## 多行对齐
### 居中
$$
\begin{aligned}
y&=(x+5)^2-(x+1)^2 \\
&=(x^2+10x+25)-(x^2+2x+1) \\
&=8x+24 \\
\end{aligned}
$$

### 左对齐
$
\begin{aligned}
y&=(x+5)^2-(x+1)^2 \\
&=(x^2+10x+25)-(x^2+2x+1) \\
&=8x+24 \\
\end{aligned}
$
## 方程组
$$
\begin{cases}
k_{11}x_1+k_{12}x_2+\cdots+k_{1n}x_n=b_1 \\
k_{21}x_1+k_{22}x_2+\cdots+k_{2n}x_n=b_2 \\
\cdots \\
k_{n1}x_1+k_{n2}x_2+\cdots+k_{nn}x_n=b_n \\
\end{cases}
$$
## 矩阵
### 圆角矩阵
$$
\begin{pmatrix}
1&1&\cdots&1\\
1&1&\cdots&1\\
\vdots & \vdots & \ddots & \vdots \\
1 & 1 & \cdots & 1 \\
\end{pmatrix}
$$

### 方角矩阵
$$
\begin{bmatrix}
1&1&\cdots&1\\
1&1&\cdots&1\\
\vdots & \vdots & \ddots & \vdots \\
1 & 1 & \cdots & 1 \\
\end{bmatrix}
$$
## 行列式
$$
\begin{vmatrix}
1&1&\cdots&1\\
1&1&\cdots&1\\
\vdots & \vdots & \ddots & \vdots \\
1 & 1 & \cdots & 1 \\
\end{vmatrix}
$$

## 特殊字符
![特殊字符](https://pic2.zhimg.com/80/v2-842b02c54dd7d8e0571609414e79bdc1_720w.png)

## 公式编号与引用
$$
x+1 \tag{1-1}
$$


由公式$(1-1)$

## 零碎的重要语法
点乘 $\cdot$, 叉乘 $\times$, 异或 $\otimes$, 直和 $\oplus$, 加减 $\pm$, 复合 $\circ$.
小于等于 $\leq$, 大于等于 $\geq$, 不等 $\neq$, 恒等 $\equiv$, 约等 $\approx$, 等价 $\cong$, 相似 $\sim$, 相似等于 $\simeq$, 点等 $\doteq$.
逻辑与 $\land$, 逻辑或 $\lor$, 逻辑非 $\lnot$, 蕴涵 $\to$, 等价 $\leftrightarrow$.
因为 $\because$, 所以 $\therefore$, 存在 $\exist$, 任意 $\forall$.
左小箭头 $\leftarrow$, 右小箭头 $\rightarrow$, 左大箭头 $\Leftarrow$, 右大箭头 $\Rightarrow$, 右长箭头 $\xrightarrow[fgh]{abcde}$.
属于 $\in$, 包含于 $\subset$, 真包含于 $\subseteq$, 交 $\cap$, 并 $\cup$, 空集 $\empty$
短向量 $\vec{x}$, 长向量 $\overrightarrow{AB}$, 上横线 $\overline{p}$.
无限 $\infty$, 极限 $\lim$, 微分 ${\rm d}$, 偏导 $\partial$, 点求导 $\dot{y}$, 点二阶导 $\ddot{y}$, 变化量 $\Delta$, 梯度 $\nabla$.
横省略 $\cdots$, 竖省略 $\vdots$, 斜省略 $\ddots$.
常见函数 $\sin$, $\cos$, $\tan$, $\arcsin$, $\arccos$, $\arctan$, $\ln$, $\log$, $\exp$.

# VSCode 快捷键
## 原生快捷键
1. 通用操作
`Ctrl + C`, 复制当前文本
`Ctrl + V`, 粘贴当前文本
`Ctrl + Z`, 撤销
`Ctrl + Shift + Z`, 反撤销
`Shift + Alt + F`, 整理代码
`Ctrl + /`, 将当前行注释 / 反注释, 当多行文本被选中时, 将多行文本注释
2. 光标操作
`Ctrl + ← `将光标向左移动一个单词
`Ctrl + → `将光标向右移动一个单词
`Ctrl + Alt + ↑`, 向上加入一个光标
`Ctrl + Alt + ↓`, 向下加入一个光标
`Ctrl + Alt + U`, 撤销上次光标操作
3. 界面移动
`Ctrl + ↑ `向上移动当前界面
`Ctrl + → `向下移动当前界面
4. 选中操作
`Shift + ← `向左选中 / 反选中一个字符(重要)
`Shift + →` 向右选中 / 反选中一个字符(重要)
`Ctrl + Shift + ← `向左选中 / 反选中一个单词(重要)
`Ctrl + Shift + → `向右选中 / 反选中一个单词(重要)
`Ctrl + D`当前有选中文本时, 将下一个与其相同的文本加入选中 (重要)
5. 文本行操作
`Ctrl + C`当前无选中文本时, 复制当前行
`Shift + Alt + ↑ `向上复制当前行, 当多行文本被选中时, 向上复制多行 (重要)
`Shift + Alt + ↓` 向下复制当前行, 当多行文本被选中时, 向下复制多行 (重要)
`Alt + ↑ `向上移动当前行, 当多行文本被选中时, 将当前多行文本向上移动 (重要)
`Alt + ↓` 向下移动当前行, 当多行文本被选中时, 将当前多行文本向下移动 (重要)


## 插件增加的快捷键
1. Markdown 语法
`Ctrl + B`当前有选中文本时, 将文本加粗
`Ctrl + I`当前有选中文本时, 将文本变为斜体
`Ctrl + M` 进入数学公式模式 (加入美元符)
2. 图片粘贴
`Ctrl + Alt + V` 粘贴剪贴板图片 (本地)
`Ctrl + Alt + V `粘贴剪贴板图片 (图床)
3. 光标操作
`Ctrl + Alt + U` 将多选光标变为单选
4. 选中操作
`Shift + Alt + ←` 向左复制当前选中文本 (重要)
`Shift + Alt + →` 向右复制当前选中文本 (重要)
`Alt + ←` 向左移动当前选中文本一个字符(重要)
`Alt + →` 向右移动当前选中文本一个字符(重要)
`Ctrl + Alt + ←` 向左移动当前选中文本一个单词(重要)
`Ctrl + Alt + →` 向右移动当前选中文本一个单词(重要)
5. 计算器功能
`Ctrl + Shift + Alt + E` 计算当前选中表达式, 用等号连接并输出
`Ctrl + Shift + Alt + R` 计算当前选中表达式, 并替换当前选中表达式
`Ctrl + Shift + Alt + D` 定义当前选中表达式, 无输出

只要选择一段公式表达式文本，然后按下快捷键 `Ctrl ＋ Shift + E` 就看得出计算结果 需要python
$\sin{\frac{\pi}{2}}$

