# hello_world
...
下面通过一个例子来说明这种方法的使用

> $(2016全国卷)21.f(x)=(x-2)e^x+a(x-1)^2,f(x)有两个零点，求a的取值范围$

$分析:f'(x)=(x-1)(e^x+a),a>0时,f(x)在(-\infty,1)\downarrow,在(1,+\infty)上\uparrow,而f(1)=-e<0,f(2)=a>0$

$下面要找出一个x_0<1,使f(x_0)>0,即\frac{a(x_0-1)^2}{2-x_0}>e^{x_0},当x\rightarrow-\infty时,\underbrace{\frac{a(x_0-1)^2}{2-x_0}}_{趋于+\infty}>\alpha>\underbrace{e^{x_0}}_{趋于0},不妨取\alpha=a,$

$解不等式组\begin{cases}\frac{a(x_0-1)^2}{2-x_0}>\alpha\\e^x<\alpha\end{cases},得x<\rm min\{\frac{\sqrt{5}-1}{2},lna\}$

> $a>0,证明f(x)=ae^x-\frac{x}{x-2}有两个零点$

$分析:f'(x)=ae^x+\frac{2}{(x-2)^2}>0在(-\infty,2),(2,\infty)上恒成立,f(0)=a>0,\\ x\rightarrow-\infty时，\underbrace{ae^x}_{趋于0}<\alpha<\underbrace{\frac{x}{x-2}}_{趋于1},不妨取\alpha=\frac{1}{2},解不等式组\begin{cases}ae^x<\alpha\\\alpha<\frac{x}{x-2}\end{cases},得x<\rm min\{ln\frac{1}{2a},-2\}$

$\bf{lemma}$

