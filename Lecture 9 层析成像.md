---
marp: true
theme: njubeam
paginate: true
math: katex
footer: "**黄周传** **地球物理基础** **2025春**"
---
<!-- _class: title -->
# 9: 地震层析成像

### Zhouchuan Huang

 #### 南京大学 地球科学与工程学院

#### 2025年春

![logo GitHub Logo](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/20_15_11_47_njulogopurple.png)

---

<!--
_class: contents
_header: ""
-->

# 目录

- **01**层析成像基本原理
- **02**层析成像经典应用
- **03**层析成像前沿进展


---
<!-- header: 层析成像基本原理-->

<div class="columns">
<div>

### 1979年诺贝尔生理学或医学奖：计算机辅助断层扫描（CT）
- 美国物理学家阿兰·科马克，建立起CT的数学和物理学基础
- 英国电机工程师 高弗雷·豪斯费尔德，发明了第一台CT机
</div>

<div class="column2">

![center](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/26_9_8_20_20250326090820475.png)


</div></div>


---
<!-- header: 层析成像基本原理 -->

- 通过旋转发射源与接收器，对人体进行360°的扫描。
![center w:550px](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/26_9_9_20_20250326090920205.png)

* ![center w:550px](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/26_9_14_16_20250326091416110.png)

---
<!-- header: 层析成像基本原理 -->
- 地震层析成像是典型的地球物理反演问题
![center](https://box.nju.edu.cn/f/17f01e0f7eb74c0a8549/?dl=1)

---
<!-- header: 层析成像基本原理-->
<div class="columns">
<div>

地震反演使观测走时($t^{obs}$)与理论走时($t^{pre}$)间的走时残差($r$)最小。
$$\begin{equation*}
\begin{aligned}
& t^{obs} =\int_{(s+\delta s)}\frac{ds}{c(s)+\delta c(s)}\approx\int_{(s+\delta s)}(u(s)+\delta u(s))\cdot ds \\

& t^{pre} =\int_{s}\frac{ds}{c(s)}=\int_{s}u(s)\cdot ds \\

& r =t^{obs}-t^{pre}
\end{aligned}
\end{equation*}$$

> 费马原理 (Fermat's Principal)：The travel time of a ray between two given points in space must be stationary for small perturbations in the path follow the ray.
</div><div>

结构异常会造成射线路径的偏移，但其对走时的影响可以忽略不计：


$$\begin{equation*}
\begin{aligned}
r &=\int_{(s+\delta s)}(u(s)+\delta u(s))\cdot ds-\int_{s}u(s)\cdot ds \\

  &=\int_{s}(u(s)+\delta u(s))\cdot ds-\int_{s}u(s)\cdot ds \\

  &=\int_{s}(u(s)+\delta u(s)-u(s))\cdot ds=\int_{s}\delta u(s)\cdot ds \\

 r &=\int_{s}\delta u\cdot ds=\int_{s}\delta(\frac{1}{v})\cdot ds=-\int_{s}\frac{\delta v}{v^{2}}\cdot ds=-\int_{s}\frac{\delta v}{v}\cdot dt \\
\\

r & =\frac{\partial T}{\partial\lambda}\cdot\Delta\lambda+\frac{\partial T}{\partial\varphi}\cdot\Delta\varphi+\frac{\partial T}{\partial h}\cdot\Delta h+\frac{\partial T}{\partial t}\cdot\Delta t+\sum_{1}^{N}\frac{\partial T}{\partial u}\cdot\Delta u+\mathbf{e} 

\end{aligned}
\end{equation*}$$
</div></div>

---
<!--层析成像基本原理-->

<div class="columns">
<div>

> #### 地震层析成像一般步骤
> * 地震定位
> * 射线追踪
> * 建立方程组
> * 求解方程组
> * 分辨率测试与误差分析

</div><div>

 ![w:500px](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/26_9_40_35_20250326094035739.png)

</div></div>

---
<!--层析成像基本原理-->

<div class="columns">
<div>

### 敏感核
![center w:400px](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/26_9_31_32_20250326093132034.png)
</div><div>

### 分辨率测试
![w:900px](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/26_9_30_24_20250326093023998.png)
</div>
</div>

---

<!--
_class: contents
_header: ""
-->

# 目录

- **01**层析成像基本原理
- **02**<font color="#ff0000">层析成像经典应用</font>
- **03**层析成像前沿进展

---
<!--层析成像基经典应用-->
### 人工地震成像

![center w:700px](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/26_11_40_10_20250326114010205.png)


---
<!--层析成像基经典应用-->
### 人工地震成像

![center w:700px](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/26_11_40_44_20250326114044706.png)

---
<!--层析成像基经典应用-->
### 俯冲带成像

![center w:800px](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/26_11_47_38_20250326114738583.png)

---
<!--层析成像基经典应用-->
### 俯冲带成像
- 俯冲板片
- 岛弧火山

![center w:700px](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/26_11_48_28_20250326114828167.png)

---
<!--层析成像基经典应用-->
### 俯冲带成像

![center w:700px](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/26_11_53_34_20250326115334050.png)

---
<!--层析成像基经典应用-->
### 俯冲带成像


![center w:800px](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/26_11_49_45_20250326114945196.png)

---
<!--层析成像基经典应用-->
### 俯冲带成像

![center w:800px](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/26_11_56_38_20250326115638823.png)

---
<!--层析成像基经典应用-->
### 俯冲带成像

![center w:600px](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/26_11_50_55_20250326115055212.png)


---
<!--层析成像基经典应用-->
### 俯冲带成像

![center w:900px](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/26_11_51_15_20250326115115362.png)


---
<!--层析成像基经典应用-->
### 俯冲带成像

![center w:800px](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/26_11_51_35_20250326115135506.png)

---
<!--层析成像基经典应用-->
### 地幔柱成像

![center w:700px](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/26_11_52_34_20250326115234608.png)


---
<!--层析成像基经典应用-->
### 地幔柱成像

![center w:800px](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/26_11_54_58_20250326115458586.png)

---
<!--层析成像基经典应用-->
### 地幔柱成像

![center w:800px](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/26_11_55_25_20250326115525701.png)



---
<!--层析成像基经典应用-->
### 地幔柱成像

![center w:800px](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/26_11_58_0_20250326115800646.png)

---
<!--层析成像基经典应用-->
### 地幔柱成像

![center w:700px](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/26_11_57_5_20250326115705888.png)

---
<!--层析成像基经典应用-->
### 地幔柱成像

![center](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/26_12_11_37_LLSVP.gif)

---
<!--层析成像基经典应用-->
### 地幔柱成像

![center](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/26_11_58_39_20250326115839274.png)



---
<!--层析成像基经典应用-->

![center w:700px](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/26_11_59_13_20250326115913515.png)

---
<!--层析成像基经典应用-->
### 地震震源区成像

![center w:800px](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/26_12_0_7_20250326120007577.png)

---

<!--
_class: contents
_header: ""
-->

# 目录

- **01**层析成像基本原理
- **02**层析成像经典应用
- **03**<font color="#ff0000">层析成像前沿进展</font>


---
<!--层析成像基前沿进展-->
### 地震波衰减成像

![center w:700px](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/26_12_1_10_20250326120110372.png)


---
<!--层析成像基前沿进展-->
### 全波形层析成像

![center w:600px](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/26_12_1_53_20250326120153789.png)

---
<!--层析成像基前沿进展-->
### 全波形层析成像

![center w:800px](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/26_11_33_46_20250326113346059.png)

---
<!--层析成像基前沿进展-->

<div class="columns">
<div >

### 时变层析成像

![center w:400](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/26_12_4_21_20250326120421659.png)

</div><div>

![center w:300](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/26_12_4_51_20250326120451265.png)

</div></div>

---
<!--层析成像基前沿进展-->
### 时变层析成像

![center w:500px](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/26_12_7_50_20250326120750099.png)

![center w:500px](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/26_12_8_7_20250326120807779.png)



---
<!--层析成像基前沿进展-->


![center w:700px](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/26_12_32_15_c2c0f301e08148da86cadac79e320af8.gif)


---
<!-- 
_class: thanks
_header: ""
-->

# 谢谢!
### 黄周传 2025春


