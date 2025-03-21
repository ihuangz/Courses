---
marp: true
theme: nju
paginate: true
---

<!--
_paginate: false
_class: homePage
-->

![h:120px](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/20_15_11_47_njulogopurple.png)

# 8: 折射地震
## 南京大学 地球科学与工程学院
黄周传 2025春

---

<!--
_paginate: false 
_class: contents
-->

## 目录

- **01**多层介质折射波走时
- **02**倾斜界面折射波走时
- **03**起伏界面折射波探测
- **04**天然地震折射波方法

---
<!-- 
_header: 多层介质折射波走时方程
_class: contentPage horizontalLayout
-->
<div class="twocols">

![w:450px](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/20_16_19_39_20250320161939039.png) 

<p class="break"></p>


 ### 天然地震
 - $$t=\frac{\Delta}{v_2}+\frac{(2H-h)\cos\theta_0}{v_1}$$
- 入射角达到临界角： $\sin\theta_0=v_1/v_2$
- 走时方程为直线 
- 斜率$t=1/v_2$ 
- $t$ 轴截距为$t_0=(2H-h)\cos\theta_0/v_1$


</div>


---

<!-- 
_header: 多层介质折射波走时
_class: contentPage horizontalLayout
-->


<div class="twocols">

![width:450px](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/20_17_11_24_20250320171124601.png) 

<p class="break"></p>

### 人工地震
-  $$t=\frac{x}{v_2}+\frac{2h\cos\alpha}{v_1}$$
-  入射角达到临界角： $\sin\alpha=v_1/v_2$
-  $\cos\alpha=\sqrt{v_2^2-v_1^2}/v_2$

-  走时方程为直线
-  斜率$t=1/v_2$
- $t$ 轴截距为$t_0=2h\cos\alpha/v_1$


</div>



<!-- _header: 多层介质折射波走时 -->


---

<!-- 
_header: 多层介质折射波走时
_class: contentPage horizontalLayout
-->

<div class="twocols">

![width:450px](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/20_17_17_7_20250320171707184.png)

<p class="break"></p>

###  双层介质
-  $$t=\frac{x}{v_3}+\frac{2h_1\cos\alpha_{13}}{v_1}+\frac{2h_2\cos\alpha_{23}}{v_2}$$
-  $$\sin\alpha_{13}=v_1/v_3, \cos\alpha_{13}=\sqrt{1-v_1^2/v_3^2}$$

- $$\sin\alpha_{23}=v_2/v_3, \cos\alpha_{23}=\sqrt{1-v_2^2/v_3^2}$$ 

- 走时方程为直线
- 斜率$t=1/v_3$ 
- $t$ 轴截距为$t_0=2h_1\cos\alpha_{13}/v_1+2h_2\cos\alpha_{23}/v_2$

</div>





---

<!-- 
_header: 多层介质折射波走时
_class: contentPage 
-->
- 速度为$v_1, v_2, v_3, ..., v_n$
- 厚度为$h_1, h_2, h_3, ..., h_n$

<br/>

$$t_n=\frac{x}{v_n}+\sum_{i=1}^{n-1}\frac{2h_i\cos\alpha_{in}}{v_i}=\frac{x}{v_n}+2\sum_{i=1}^{n-1}h_i/\frac{v_iv_n}{\sqrt{v_n^2-v_i^2}}$$
- $$\alpha_{in}=sin^{-1}(v_i/v_n)$$


<br/>

* <font color="#ff0000">${v_iv_n}/{\sqrt{v_n^2-v_i^2}}$为穿透速度</font>
* <font color="#ff0000"> 等效传播： 垂直向下入射$\Rightarrow$水平传播$\Rightarrow$垂直向上入射</font>

---
<!--
_header: 多层介质折射波走时
_class: contentPage horizontalImages
-->

| 低速层的屏蔽效应                                                                                                           | 无法探测高速薄层                                                                                                       |
| ------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------- |
| ![w:600px](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/20_20_51_40_20250320205140545.png)<br> | ![w:600px](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/20_20_52_59_20250320205259982.png) |


---
<!--
_header: 多层介质折射波走时
_class: contentPage horizontalImages
-->
![w:900px](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/20_20_54_37_20250320205437168.png)



---
<!--
_paginate: false 
_class: contents
-->

## 目录

- **01**多层介质折射波走时
- <font color="#ffc000">**02**倾斜界面折射波走时</font>
- **03**起伏界面折射波探测
- **04**天然地震折射波方法


---
<!-- 
_header: 倾斜界面折射波走时
_class: contentPage horizontalLayout
-->

<div class="twocols">

![width:500px](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/20_19_3_31_20250320190331705.png)

<p class="break"></p>

### 下倾方向
* $$\mathbf{t_d} =\frac{h_d/\cos\alpha}{v_1} +\frac{h_u/\cos\alpha}{v_1}  +\frac{x\cos\varphi-h_d\tan\alpha-h_u\tan\alpha}{v_2}$$

* $$\mathbf{t_d}=\frac{h_d}{v_1 \cos\alpha}+\frac{h_d+x\sin\varphi}{v_1 \cos\alpha} +\frac{x\cos\varphi-2h_d\tan\alpha-x\sin\varphi\tan\alpha}{v_2}$$
* $\sin\alpha=v_1/v_2$
* $$t_d=\frac{x\sin(\alpha+\varphi)}{v_1}+\frac{2h_d\cos\alpha}{v_1}$$

 * 视速度： $v_d^*=v_1/\sin(\alpha+\varphi)$
 * 截距为： $t_{0d}=2h_d\cos\alpha/v_1$
</div>


---
<!-- 
_header: 倾斜界面折射波走时
_class: contentPage horizontalLayout
-->

 + ### 上倾方向

+ $$t_u=\frac{x\sin(\alpha-\varphi)}{v_1}+\frac{2h_u\cos\alpha}{v_1}$$

+ 视速度： $v_u^*=v_1/\sin(\alpha-\varphi)$
+ 截距为： $t_{0u}=2h_u\cos\alpha/v_1$

![width:500px](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/20_19_3_31_20250320190331705.png)
- ### 下倾方向
- $$t_d=\frac{x\sin(\alpha+\varphi)}{v_1}+\frac{2h_d\cos\alpha}{v_1}$$

 - 视速度： $v_d^*=v_1/\sin(\alpha+\varphi)$
 - 截距为： $t_{0d}=2h_d\cos\alpha/v_1$

---
<!--
_header: 倾斜界面折射波走时
_class: contentPage horizontalLayout
-->

- ### 上倾方向

- $$t_u=\frac{x\sin(\alpha-\varphi)}{v_1}+\frac{2h_u\cos\alpha}{v_1}$$

- 视速度： $v_u^*=v_1/\sin(\alpha-\varphi)$
- 截距为： $t_{0u}=2h_u\cos\alpha/v_1$

- ### 下倾方向
- $$t_d=\frac{x\sin(\alpha+\varphi)}{v_1}+\frac{2h_d\cos\alpha}{v_1}$$

 - 视速度： $v_d^*=v_1/\sin(\alpha+\varphi)$
 - 截距为： $t_{0d}=2h_d\cos\alpha/v_1$

 
+ ### 走时曲线特点
+  走时曲线都是直线
+  走时间轴截距较大的为下倾方向
+  视速度更小的为下倾方向
![width:400px](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/20_19_3_31_20250320190331705.png)

---
<!--
_header: 倾斜界面折射波走时
_class: contentPage
-->
### 求解倾斜界面的倾角$\varphi$
$$\alpha=\frac{1}{2}\left[ \sin^{-1}\frac{v_1}{v_d^*} + \sin^{-1}\frac{v_1}{v_u^*} \right]$$
$$\varphi=\frac{1}{2}\left[ \sin^{-1}\frac{v_1}{v_d^*} - \sin^{-1}\frac{v_1}{v_u^*} \right]$$

### 求解下层介质的速度$v_2$

$$\left| \frac{1}{v_u^*} \right| + \left| \frac{1}{v_d^*} \right| = \frac{2\sin\alpha\cos\varphi}{v_1} = \frac{2\cos\varphi}{v_2}$$

<br/>

- 当$\varphi$比较小时（$<10^\circ \sim 15^\circ$），$\cos\varphi\approx1$：

$$v_2\approx\frac{2}{k_{2u}+k_{2d}}$$

---
<!--
_header: 倾斜界面折射波走时
_class: contentPage
-->
### 求解倾斜界面的倾角$\varphi$:
$$\alpha=\frac{1}{2}\left[ \sin^{-1}\frac{v_1}{v_d^*} + \sin^{-1}\frac{v_1}{v_u^*} \right]$$
$$\varphi=\frac{1}{2}\left[ \sin^{-1}\frac{v_1}{v_d^*} - \sin^{-1}\frac{v_1}{v_u^*} \right]$$
### 求解下层介质的速度$v_2$:
$$v_2\approx\frac{2}{k_{2u}+k_{2d}}$$

### 求解倾斜界面的垂直深度:


$$h_d=\frac{v_1 t_{0d}}{2\cos\alpha}$$

$$h_u=\frac{v_1 t_{0u}}{2\cos\alpha}$$

---
<!--
_header:  倾斜界面折射波走时
_class: contentPage horizontalImages
-->
![width:550px](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/20_20_33_37_20250320203337550.png) ![w:550px](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/20_20_35_22_20250320203522348.png)
- 下倾方向： $t_d=\frac{x\sin(\alpha+\varphi)}{v_1}+\frac{2h_d\cos\alpha}{v_1}$

- 上倾方向： $t_u=\frac{x\sin(\alpha-\varphi)}{v_1}+\frac{2h_u\cos\alpha}{v_1}$
* 下倾方向观测不到折射波
* 上倾方向无法形成折射波

---

<!--
_header: 倾斜界面折射波走时
_class: contentPage
-->
<div class="twocols">

![w:500px](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/20_20_42_53_20250320204253338.png)

<p class="break"></p>

### $\alpha=\varphi$

- 下倾方向： $t_d=\frac{x\sin(\alpha+\varphi)}{v_1}+\frac{2h_d\cos\alpha}{v_1}$

- 上倾方向： $t_u=\frac{x\sin(\alpha-\varphi)}{v_1}+\frac{2h_u\cos\alpha}{v_1}$

*  $v_u^*=+\infty$:  所有震中距地震波同时到达

</div>


---
<!--
_header: 倾斜界面折射波走时
_class: contentPage
-->

<div class="twocols">

![w:500px](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/20_20_45_17_20250320204516992.png)

<p class="break"></p>

### $\alpha<\varphi$

- 下倾方向： $t_d=\frac{x\sin(\alpha+\varphi)}{v_1}+\frac{2h_d\cos\alpha}{v_1}$

- 上倾方向： $t_u=\frac{x\sin(\alpha-\varphi)}{v_1}+\frac{2h_u\cos\alpha}{v_1}$

*  $v_u^*<0$: 震中距大的地方地震波先到达



</div>


---
<!--
_paginate: false 
_class: contents
-->

## 目录

- **01**多层介质折射波走时
- **02**倾斜界面折射波走时
- <font color="#ffc000">**03**起伏界面折射波探测</font>
- **04**天然地震折射波方法



---
<!--
_header: 起伏界面折射波探测
_class: contentPage horizontalImages
-->

<div class="twocols">

<br/>

![w:500px](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/21_10_42_13_20250321104213758.png)

<p class="break"></p>

### 差数时距曲线法

$$t_1=\frac{O_1A+BS}{v_1}+\frac{AB}{v_2}$$

$$t_2=\frac{O_2D+CS}{v_1}+\frac{CD}{v_2}$$

- 互换时间$T$为：

$$T=\frac{O_1A+O_2D}{v_1} + \frac{AB+BC+CD}{v_2}$$

- 折射界面曲率半径远大于埋深时，$\triangle SBC$为等腰三解形:

$$\frac{BS}{v_1}\approx\frac{CS}{v_1}=\frac{h}{v_1\cos\alpha}$$


$$\frac{BC}{v_2}\approx\frac{2h\tan\alpha}{v_2}$$


</div>



---
<!--
_header: 起伏界面折射波探测
_class: contentPage horizontalImages
-->

<div class="twocols">

<br/>

![w:500px](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/21_10_42_13_20250321104213758.png)

<p class="break"></p>

### 差数时距曲线法

- 令：

$$t_0=t_1+t_2-T=\frac{BS}{v_1}+\frac{CS}{v_1}-\frac{BC}{v_2}=\frac{2h\cos\alpha}{v_1}$$

$${\color{red} h}=\frac{v_1 t_0}{2\cos\alpha}=(t_1+t_2-T)\frac{v_1}{2\cos\alpha}=K\cdot t_0$$

- 其中，

$$K=\frac{v_1}{2\cos\alpha}=\frac{1}{2\sqrt{\frac{1}{v_1^2}-\frac{1}{v_2^2}}}$$

- 因此，该方法的关键是求取$K$值，因此，需要知道$v_1$和$v_2$的值。


</div>


---
<!--
_header: 起伏界面折射波探测
_class: contentPage horizontalImages
-->

<div class="twocols">

<br/>

![w:500px](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/21_10_42_13_20250321104213758.png)

<p class="break"></p>

### 差数时距曲线法

- 定义：

$$\Delta t(x)=T-t_2(x)$$

$$t_0(x) = t_1(x)+t_2(x)-T=t_1(x)-\Delta t(x)$$


$$\theta(x) = t_1(x)-t_2(x)+T=t_1(x)+\Delta t(x)$$

- 当界面起伏比较和缓时，

$$\frac{\delta\theta(x)}{\delta x}=\frac{\delta t_1(x)}{\delta x}-\frac{\delta t_2(x)}{\delta x}=\frac{1}{v_d^*}+\frac{1}{v_u^*}=\frac{2\cos\varphi}{v_2}$$

- 当 $\varphi<15^\circ$ 时，$cos\varphi\approx 1$，


$$\color{red} v_2\approx 2/\frac{\Delta\theta}{\Delta x}$$

</div></div>


---
<!--
_paginate: false 
_class: contents
-->

## 目录

- **01**多层介质折射波走时
- **02**倾斜界面折射波走时
- **03**起伏界面折射波探测
- <font color="#ffc000"> **04**天然地震折射波方法</font>


---
<!--
_header: 天然地震折射波方法
_class: contentPage horizontalImages
-->
<div class="colwrap">
<div class="left">

<br/>

### 接收函数：$y=f(x)$
- 利用转换波与直达波的时间差，推测地球深度速度间断面的深度

![w:500px](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/21_10_58_51_20250321105851541.png)

</div>

<div class="right inverted">

<br/>

![w:500px](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/21_10_59_30_20250321105930684.png)

</div>

</div>


---
<!--
_header: 天然地震折射波方法
_class: contentPage horizontalImages
-->

- ### 四川龙门山下方的地壳结构
![h:500px](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/21_11_3_13_20250321110313515.png)


---
<!--
_header: 天然地震折射波方法
_class: contentPage horizontalImages
-->

- ### 俯冲带结构
![h:500px](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/21_11_5_57_20250321110557282.png)


---
<!--
_header: 天然地震折射波方法
_class: contentPage horizontalImages
-->

- ### 地幔转换带结构
![h:500px](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/21_11_6_53_20250321110653968.png)


---
<!--
_header: 天然地震折射波方法
_class: contentPage horizontalImages
-->

- ### 岩石圈结构
![h:500px](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/21_11_7_13_20250321110713239.png)


---
<!--
_paginate: false
_class: thanksPage
-->
## 谢谢！

<br/>

**黄周传 2025-03-21**

