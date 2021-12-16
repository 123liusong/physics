

[TOC]

### 1

![image-20211215230637493](C:\Users\sean\AppData\Roaming\Typora\typora-user-images\image-20211215230637493.png)

`解：`设杆的左端为坐标原点$O$，$x$轴沿直杆方向．带电直杆的电荷线密度为$\lambda=q / L$，在$x$处取一电荷元$\mathrm{d} q=\lambda \mathrm{d} x=q \mathrm{~d} x / L$，它在$P$点的场强：
$$
\mathrm{d} E=\frac{\mathrm{d} q}{4 \pi \varepsilon_{0}(L+d-x)^{2}}=\frac{q \mathrm{~d} x}{4 \pi \varepsilon_{0} L(L+d-x)^{2}}
$$
总场强为   

$$
E=\frac{q}{4 \pi \varepsilon_{0} L} \int_{0}^{L} \frac{\mathrm{d} x}{(L+d-x)^{2}}=\frac{q}{4 \pi \varepsilon_{0} d(L+d)}
$$
方向沿*x*轴，即杆的延长线方向．

### 2

![image-20211216100213688](C:\Users\sean\AppData\Roaming\Typora\typora-user-images\image-20211216100213688.png)
$$
\begin{cases}
  E_{外}=\frac{q}{4 \pi \varepsilon_{0} r^{2}},& \quad\left(r>R\right)  \\
  E_{内}=0,&\quad\left(r<R\right)
\end{cases}
$$

`解：`电场$E$分布：

> $\oint \vec{E} \cdot d \vec{s}=E\cdot4\pi r^{2}=q_{内}/\varepsilon _{0}$

$$
E=\begin{cases}
0,& \quad\left(r<R_{1}\right)\\
\frac{Q_{1}}{4 \pi \varepsilon_{0} r^{2}},& \quad\left(R_{1}<r<R_{2}\right)\\
\frac{Q_{1}+Q_{2}}{4 \pi \varepsilon_{0} r^{2}},& \quad\left(r>R_{2}\right)
\end{cases}
$$
电势$V$分布：

> $V=\int_{r}^{\infty} E d r$

$r<R_{1}$时，
$$
V_{1}=\int_{r}^{R_{1}}E_{1}dr+\int_{R_{1}}^{R_{2}}E_{2}dr+\int_{R_{2}}^{\infty }E_{3}dr=\frac{Q_{1}}{4 \pi \varepsilon_{0} R_{1}}+\frac{Q_{2}}{4 \pi \varepsilon_{0} R_{2}}
$$

$R_{1}<r<{R_{2}}$时，
$$
V_{2}=\int_{r}^{R2}E_{2}dr+\int_{R_{2}}^{\infty}E_{3}dr=\frac{Q_{1}}{4 \pi \varepsilon_{0} r}+\frac{Q_{2}}{4 \pi \varepsilon_{0} R_{2}}
$$
$r<R_{2}$时，
$$
V_{3}=\int_{r}^{\infty}E_{3}dr=\frac{Q_{1}+Q_{2}}{4 \pi \varepsilon_{0} r}
$$

### 3

![image-20211216104731029](C:\Users\sean\AppData\Roaming\Typora\typora-user-images\image-20211216104731029.png)

`解：`电荷分布：


金属球表面Q；金属球壳内表面$-Q$，外表面$3Q$。

$E$分布：做半径为$r$的高斯球面

> $\oint \vec{E} \cdot d \vec{s}=E\cdot4\pi r^{2}=q_{内}/\varepsilon _{0}$

$$
E=\begin{cases}
0,& \quad\left(r<R_{1}\right)\\
\frac{Q}{4 \pi \varepsilon_{0} r^{2}},& \quad\left(R_{1}<r<R_{2}\right)\\
0,& \quad\left(R_{2}<r<R_{3}\right)\\
\frac{3Q}{4 \pi \varepsilon_{0} r^{2}},&\quad\left(r>R_{3}\right)
\end{cases}
$$
$V$分布：

> $V=\int_{r}^{\infty} E d r$

$r<R_{1}$时，
$$
V_{1}=\int_{R_{1}}^{R_{2}} \frac{Q}{4 \pi \varepsilon_{0} r^{2}} d r+\int_{R_{3}}^{\infty}\frac{Q}{4 \pi \varepsilon_{0} r^{2}}==\frac{Q}{4 \pi \varepsilon_{0}}\left(\frac{1}{R_{1}}-\frac{1}{R_{2}}\right)+\frac{3 Q}{4 \pi \varepsilon_{0} R_{3}}
$$
$R_{1}<r<R_{2}$时，
$$
V_{2}=\int_{r}^{R_{2} } \frac{Q}{4 \pi \varepsilon_{0} r^{2}} d r+\int_{R_{3}}^{\infty} \frac{3 Q}{4 \pi \varepsilon_{0} r^{2}} d r=\frac{Q}{4 \pi \varepsilon_{0}}\left(\frac{1}{r}-\frac{1}{R_{2}}\right)+\frac{3 Q}{4 \pi \varepsilon_{0} R_{3}}
$$
$R_{2}<r<R_{3}$时，
$$
V_{3}=\int_{R_{3}}^{\infty} \frac{3 Q}{4 \pi \varepsilon_{0} r^{2}} d r=\frac{3 Q}{4 \pi \varepsilon_{0} R_{3}}
$$
$r<R_{3}$时，
$$
V_{4}=\int_{r}^{\infty} \frac{3 Q}{4 \pi \varepsilon_{0} r^{2}} d r=\frac{3 Q}{4 \pi \varepsilon_{0}r}
$$

### 4

> 无限长直载流导线：$B=\mu_{0} I/2 \pi a$
>
> 圆形载流导线（圆心处）：$B=\mu_{0} I/2 R$

<img src="https://pic4.zhimg.com/80/v2-e055e52c2a167052c6e261d47e716243_720w.jpg" alt="img" style="zoom:67%;" /><img src="https://pic3.zhimg.com/80/v2-846eeec4f0ffea4e5cf8362898abf80a_720w.jpg" alt="img" style="zoom:67%;" />

<img src="https://pic2.zhimg.com/80/v2-f10fa248e5f362d2189aa5337d49dcad_720w.jpg" alt="img" style="zoom:67%;" /><img src="https://pic3.zhimg.com/80/v2-803aa480fe0b126fcb95b6c822aedf36_720w.jpg" alt="img" style="zoom:67%;" />

### 5

> 安培定理：$\oint_{L}^{} B\cdot dl=B\cdot 2\pi r=\mu_{0}\sum I$

##### `1 载流柱壳`

`解：`作半径为$r$的圆形环路

![image-20211216110412561](C:\Users\sean\AppData\Roaming\Typora\typora-user-images\image-20211216110412561.png)
$$
\begin{align*}
\left ( r<R_{1} \right ),&&\sum I_{1}=0,&&B_{1}=0 
\\\left ( R_{1}<r<R_{2} \right ),&&\sum I_{2}=\frac{r^{2}-R_{1}}{R_{2}^{2}-R_{1}^{2}} I ,&&B_{2}=\frac{\mu_{0} I}{2 \pi} \frac{r^{2}-R_{1}^{2}}{R_{2}^{2}-R_{1}^{2}} \frac{1}{r}
\\\left ( r>R_{2} \right ),&&\sum I_{3}=I,&& B_{3}=\frac{\mu_{0} I}{2 \pi r}
\end{align*}
$$

内外壁：$B_{内}=0$	$B_{外}=\mu_{0}I/2\pi R_{2}$

##### `2 同轴电缆`

`解：`作半径为$r$的圆形环路

![image-20211216111401303](C:\Users\sean\AppData\Roaming\Typora\typora-user-images\image-20211216111401303.png)
$$
\begin{matrix}
\left ( r<R_{1}  \right ) ,&&\sum I_{1}=I\frac{ r^{2}}{R_{1}^{2}} ,&&B_{1}=\frac{\mu_{0} I}{2 \pi R_{1}^{2}} r
\\\left ( R_{1}<r<R_{2} \right ) ,&&\sum I_{2}=I,&&B_{2}=\frac{\mu_{0} I}{2 \pi  r}
\\\left ( R_{2}<r<R_{3} \right ) ,&&\sum I_{3}=I-\frac{r^{2}-R_{2}^{2}}{R_{3}^{2}-R_{2}^{2}} I,&&B_{2}=\frac{\mu_{0} I}{2 \pi  r}\cdot\frac{R_{3}^{2}-r^{2}}{R_{3}^{2}-R_{2}^{2}}
\\\left ( r>R_{3} \right ),&&\sum I_{4}=I-I=0,&&B=0
\end{matrix}
$$

### 6

`例16-2`有一无限长载流直导线，电流$i=i_{0}\sin\omega t$，求与之共面放置的共面矩形线圈 $abcd$中产生的感应电动势的大小。（$l_{1}$、$l_{2}$、$h$为已知量）

<img src="C:\Users\sean\AppData\Roaming\Typora\typora-user-images\image-20211215230821003.png" alt="image-20211215230821003" style="zoom:33%;" />

`解：`

> 电磁感应定律：$ \varepsilon =-d\Phi  _{m}/dt $

穿过矩形线圈$abcd$的磁通量为
$$
\Phi_{\mathrm{m}}=\int \boldsymbol{B} \cdot \mathrm{d} \boldsymbol{S}=\int_{h}^{h+l_{2}} \frac{\mu_{0} i}{2 \pi x} l_{1} \mathrm{~d} x=\frac{\mu_{0} i_{0} l_{1}}{2 \pi} \ln \frac{h+l_{2}}{h} \sin \omega t
$$
则回路中产生的感应电动势为
$$
\varepsilon_{\mathrm{i}}=-\frac{\omega \mu_{0} i_{0} l_{1}}{2 \pi} \ln \frac{h+l_{2}}{h} \cos \omega t
$$

### 7

![image-20211216111755713](C:\Users\sean\AppData\Roaming\Typora\typora-user-images\image-20211216111755713.png)

`解：`取上下两端对称线元$dl$与$d{l}'$

> 安培力（电流方向与磁场方向垂直时）：$F=BIL$

$$
\begin{align*}
dF=B\cdot I_{2}dl&&	向上\\
d{F}'=B\cdot I_{2}d{l}'&&	向下
\end{align*}
$$

$dF$与$d{F}'$等大反向

故上下载流导线所受合力为0。
$$
\begin{align*}左：&&B_{1}=\frac{\mu_{0}I_{1}}{2\pi d},&&F_{1}=I_{2}\frac{\mu_{0}I_{1}}{2\pi d}\cdot l,&&向左
\\右：&&B_{1}=\frac{\mu_{0}I_{1}}{2\pi \left ( b+d \right ) },&&F_{1}=I_{2}\frac{\mu_{0}I_{1}}{2\pi \left ( b+d \right ) }\cdot l,&&向右
\end{align*}
$$

$$
\begin{align*}
F_{合}=F_{1}-F_{2}=\frac{\mu_{0}I_{1}}{2\pi}\cdot \frac{b}{d\left (  b+d\right ) } \cdot l,&&向左
\end{align*}
$$

