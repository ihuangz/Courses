---
marp: true
paginate: true
math: katex
theme: blue
style: ".columns {  display: flex;  gap: 1rem;}.columns > div {  flex: 1 1 0;}"
---
<!-- _class: lead -->

#  8: 折射地震

<br>

#### **黄周传**
#### 南京大学
2025年3月21日

---

<!-- 
_class: lead
_header: 主要内容
_text-align: center
-->

## <font color="#ff0000">**01**多层介质折射波走时</font>
## **02**倾斜界面折射波走时
## **03**起伏界面折射波探测
## **04**天然地震折射波方法

---

<!-- _header: 多层介质折射波走时 -->


![bg left:40% width:100%](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/20_16_19_39_20250320161939039.png) 


### 天然地震
- 入射角达到临界角： $\sin\theta_0=v_1/v_2$
$$t=\frac{\Delta}{v_2}+\frac{(2H-h)\cos\theta_0}{v_1}$$
- 走时方程为直线 
- 斜率$t=1/v_2$ 
- $t$ 轴截距$t_0=(2H-h)\cos\theta_0/v_1$

---

<!-- _header: 多层介质折射波走时 -->


![bg left:40% width:90%](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/20_17_11_24_20250320171124601.png) 

### 人工地震
$$t=\frac{x}{v_2}+\frac{2h\cos\alpha}{v_1}$$
- 入射角达到临界角： $\sin\alpha=v_1/v_2$
	-  $\cos\alpha=\sqrt{v_2^2-v_1^2}/v_2$
- 走时方程为直线
- 斜率$t=1/v_2$ 
 -  $t$ 轴截距为$t_0=2h\cos\alpha/v_1$

---

<!-- _header: 多层介质折射波走时 -->

![bg left:40% width:90%](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/20_17_17_7_20250320171707184.png)

$$t=\frac{x}{v_3}+\frac{2h_1\cos\alpha_{13}}{v_1}+\frac{2h_2\cos\alpha_{23}}{v_2}$$
- $$\sin\alpha_{13}=v_1/v_3, \cos\alpha_{13}=\sqrt{1-v_1^2/v_3^2}$$
- $$\sin\alpha_{23}=v_2/v_3, \cos\alpha_{23}=\sqrt{1-v_2^2/v_3^2}$$

- 走时方程为直线
- 斜率$t=1/v_3$ 
-  $t$ 轴截距为$t_0=2h_1\cos\alpha_{13}/v_1+2h_2\cos\alpha_{23}/v_2$

---

<!-- _header: 多层介质折射波走时-->
- 速度为$v_1, v_2, v_3, ..., v_n$
- 厚度为$h_1, h_2, h_3, ..., h_n$

$$t_n=\frac{x}{v_n}+\sum_{i=1}^{n-1}\frac{2h_i\cos\alpha_{in}}{v_i}=\frac{x}{v_n}+2\sum_{i=1}^{n-1}h_i/\frac{v_iv_n}{\sqrt{v_n^2-v_i^2}}$$

其中：

$$\alpha_{in}=sin^{-1}(v_i/v_n)$$

- <font color="#ff0000">${v_iv_n}/{\sqrt{v_n^2-v_i^2}}$为穿透速度</font>
- <font color="#ff0000"> 等效传播： 垂直向下入射$\Rightarrow$水平传播$\Rightarrow$垂直向上入射</font>

---

<!-- 
_class: lead
_header: 主要内容
_text-align: center
-->

## **01**多层介质折射波走时
## **02**<font color="#ff0000">倾斜界面折射波走时</font>
## **03**起伏界面折射波探测
## **04**天然地震折射波方法

---
<!-- _header: 倾斜界面折射波走时 -->

![bg left:40% width:110%](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/20_19_3_31_20250320190331705.png)
* $$\mathbf{t_d} =\frac{h_d/\cos\alpha}{v_1} +\frac{h_u/\cos\alpha}{v_1} \\ +\frac{x\cos\varphi-h_d\tan\alpha-h_u\tan\alpha}{v_2}$$

* $$\mathbf{t_d}=\frac{h_d}{v_1 \cos\alpha}+\frac{h_d+x\sin\varphi}{v_1 \cos\alpha} \\+\frac{x\cos\varphi-2h_d\tan\alpha-x\sin\varphi\tan\alpha}{v_2}$$

* $$t_d=\frac{x\sin(\alpha+\varphi)}{v_1}+\frac{2h_d\cos\alpha}{v_1}$$

---
<!-- _header: 倾斜界面折射波走时 -->

![bg left:40% width:110%](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/20_19_3_31_20250320190331705.png)

**下倾方向：**

* $$t_d=\frac{x\sin(\alpha+\varphi)}{v_1}+\frac{2h_d\cos\alpha}{v_1}$$

 * 视速度： $v_d^*=v_1/\sin(\alpha+\varphi)$, 截距为： $t_{0d}=2h_d\cos\alpha/v_1$

**上倾方向：**

* $$t_u=\frac{x\sin(\alpha-\varphi)}{v_1}+\frac{2h_u\cos\alpha}{v_1}$$

* 视速度： $v_u^*=v_1/\sin(\alpha-\varphi)$, 截距为： $t_{0u}=2h_u\cos\alpha/v_1$
---
<!--
_header: 倾斜界面折射波走时
_class: contentPage horizontalLayout
-->
**下倾方向：**

$$t_d=\frac{x\sin(\alpha+\varphi)}{v_1}+\frac{2h_d\cos\alpha}{v_1}$$


**上倾方向：**

$$t_u=\frac{x\sin(\alpha-\varphi)}{v_1}+\frac{2h_u\cos\alpha}{v_1}$$
* 走时曲线都是直线
* 与时间轴截距较大的为下倾方向
* 视速度更小的为下倾方向

---
<!--
_header: 倾斜界面折射波走时
_class: contentPage horizontalLayout
-->

## column1

## column 2

# column 3

---

<!-- _header: Fragmented list-->

---

<!-- _header: Fragmented list-->

---
<!--
_class: lead
_paginate: skip
-->
# Thank you very much!

