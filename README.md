线性规划问题，Matlab+Yalmip+Cplex，Ilog/Cplex，从入门开始....<br>
==
<br>

欢迎大家批评指正，又cai又爱玩  
<br>
问题一，问题描述<br>
--
1.某工厂在计划期内要安排生产桌子（table)、椅子（chair），已知生产单位产品所需的设备台时及A，B两种原材料的消耗量，如表1所示。该工厂每生产一张桌子获利2元，每生产一件椅子获利3元，问如何安排生产获利最大？
<br>
<br>
|    | 资源约束表 |    |   |
| ------------- | ------------- | ------------- | ------------- |
| Content Cell  | 桌子/张  | 椅子/张  | 合计  |
| 设备台时  | 1  | 2  | 8  |
| 原材料A  | 4  | 0  | 16 kg |
| 原材料B  | 0  | 4  | 12kg  |
<br>
建议自己写出他的数学模型，非常简单...
<br>
$$
\text{max } z = 2x_1 + 3x_2
$$

Subject to:

$$
x_1 + 2x_2 \leq 8
$$
$$
4x_1 \leq 16
$$
$$
4x_2 \leq 12
$$
$$
x_1, x_2 \geq 0
$$


<br>
$\hbar\frac
{\partial \psi}
{\partial t}
= \frac{-\hbar^2}{2m} \left(\frac{\partial^2}
{\partial x^2} + \frac{\partial^2}
{\partial y^2}+\frac{\partial^2}
{\partial z^2}
\right) \psi + V \psi$
