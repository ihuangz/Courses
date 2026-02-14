---
marp: true
theme: njubeam
paginate: true
math: katex
footer: "**黄周传** **地球物理基础** **2025春**"
---

<!-- _class: title -->
# 10: 地震面波

### 黄周传

 #### 南京大学 地球科学与工程学院

#### 2025年春

![logo](http://114.212.123.179:5009/api/images/20260130160501839.png)


---
<!--
_class: contents
_header: ""
-->
# 目录

- **01**面波基本特征
- **02**面波频散曲线
- **03**面波层析成像
- **04**背景噪声面波

---
<!-- header: 地震波形
_class: hLayout
-->

- ![h:400px](http://114.212.123.179:5009/api/images/20260130160501840.png)
- 面波振幅最大，能量最强



---
<!-- header: 面波的形成
_class: hLayout
-->

浅震P-SV波场
<video height="500" controls style="border: 3px solid blue; background:lightblue;">
    <source src="https://box.nju.edu.cn/f/c7597e265ab948e6b11d/?dl=1" type="video/mp4">
</video>


---
<!-- header: 面波的形成
_class: hLayout
-->

浅震P-SV波场
![h:500px](http://114.212.123.179:5009/api/images/20260130160501841.png)


---
<!-- header: 面波的形成
_class: hLayout
-->
SH波场
<video height="500" controls style="border: 3px solid blue; background:lightblue;">
    <source src="https://box.nju.edu.cn/f/ea21f478c27d4edc9b56/?dl=1" type="video/mp4">
</video>


---
<!-- header: 面波的形成
_class: hLayout
-->

深源P-SV波场
<video height="500" controls style="border: 3px solid blue; background:lightblue;">
    <source src="https://box.nju.edu.cn/f/92ac2efecf364d5c9f90/?dl=1" type="video/mp4">
</video>


---
<!-- header: 面波的形成
_class: hLayout
-->

- 面波是由体波干涉叠加在界面附近生成的一种次生波
- 振幅随深度增加而迅速减小，能量主要集中在界面附近并沿界面传播
- 面波主要有瑞利波和勒夫波两种基本类型



---
<!-- header: 面波的基本类型
_class: hLayout
-->

> ### 瑞利波(Rayleigh)
> - 1885年由英国物理学家Rayleigh首先在理论上导出，后在观测中证实
> -  P + SV 波在自由界面耦合形成的非均匀波
> - 沿地表传播，位移矢量在垂直于地面的平面内做逆行的椭圆振动
> - 振幅在地表最大，随深度以指数形式减小
> - 瑞利波的波速小于横波波速，泊松比为 0.25 时，瑞利波速度为$c_R=0.9194v_s$

![](https://box.nju.edu.cn/f/2bcf3d71ab1041aba259/?dl=1)



---
<!-- header: 面波的基本类型
_class: hLayout
-->

> ### 勒夫波（Love）
> - 1911年英国物理学家Love提出
> - 由 SH 波相干干涉形成
> - 产生于层状介质中，且要求上覆层横波速度小于下半空间的横波速度
> - 振动方向平行于地面，与传播方向垂直
> - 勒夫波的速度 $c_L$ 介于上下层介质的 S 波速度之间$v_{s1}<c_L<v_{s2}$
> - 勒夫波的速度大于瑞利波速度:$c_L>c_R$

![](https://box.nju.edu.cn/f/f1a8be35af274bdca1ea/?dl=1)



---
<!-- header: 面波的基本类型
_class: hLayout
-->

- ### 全球面波记录
	由于面波能量衰减很慢，大地震产生的面波在绕地球多圈后能量仍十分明显，在一个特定台站可观察到环绕地球不同路径的瑞利型 R 和勒夫型 G 长周期面波.

	* 从地震沿**小圆弧**路径到达台站的瑞利波记为 R1, R3, R5, ...
	* 从地震沿**大圆弧**路径到达台站的瑞利波记为 R2, R4, R6, ...

![image.png](http://114.212.123.179:5009/api/images/20260130160501844.png)


---
<!-- header: 面波的基本类型
_class: hLayout
-->

![w:600](http://114.212.123.179:5009/api/images/20260130160501845.png)

 >### 体波（P、S）在三维空间传播
> - 距震源r处的体波能流密度为：$I_b=E_b/2\pi r^2$
> - 能量以$1/r^2$衰减
> ### 面波在地表一定深度范围传播
> - 距震源r处的面波能流密度为：$I_s=E_s/2\pi rd$
> - 能量以$1/r^1$衰减



---
<!--
_class: contents
_header: ""
-->
# 目录

- **01**面波基本特征
- **02**<font color="#ff0000">面波频散曲线</font>
- **03**面波层析成像
- **04**背景噪声面波


---
<!-- header: 面波频散曲线
_class: hLayout
-->

 ![h:400px](http://114.212.123.179:5009/api/images/20260130160501840.png)

---
<!-- header: 面波频散曲线
_class: hLayout
-->

 ![h:300px](http://114.212.123.179:5009/api/images/20260130160501840.png)

* ![h:500px](http://114.212.123.179:5009/api/images/20260130160501846.png)

---
<!-- header: 面波频散曲线
_class: hLayout
-->


- 频率愈低(周期长)的面波穿透的深度越深，且深部介质的速度更大
- 因此长周期波传播较快,在面波波列中显示为前段周期大后段周期小，即周期大(频率低)的波先到

- ![h:300px](https://box.nju.edu.cn/f/c2c91895df114c5ebdc0/?dl=1)

+ ![w:700px h:500px](http://114.212.123.179:5009/api/images/20260130160501846.png)

---
<!-- header: 面波频散曲线
_class: hLayout
-->
* 多个单频波的叠加形成面波“波包”
* ![w:800](https://box.nju.edu.cn/f/33bb95db29d64b708d4d/?dl=1)
* ![w:800](https://box.nju.edu.cn/f/cdfafe652c804102ab3d/?dl=1)

---
<!-- header: 面波频散曲线
_class: hLayout
-->


- ![w:600](https://box.nju.edu.cn/f/cdfafe652c804102ab3d/?dl=1)

> ###   相速度
> 单频率简谐波的传播速度
> ###   群速度
> 多频率简谐波叠加的传播速度


---
<!-- header: 面波频散曲线
_class: hLayout
-->

+ ![h:300px](https://box.nju.edu.cn/f/c2c91895df114c5ebdc0/?dl=1) 
- ![h:300](https://box.nju.edu.cn/f/5d78508b19434ddfa536/?dl=1)

---
<!-- header: 面波频散曲线
_class: hLayout
-->
![](http://114.212.123.179:5009/api/images/20260130160501851.png)

---
<!--
_class: contents
_header: ""
-->
# 目录

- **01**面波基本特征
- **02**面波频散曲线
- **03**<font color="#ff0000">面波层析成像</font>
- **04**背景噪声面波


---
<!-- header: 面波层析成像
_class: hLayout
-->
1. 面波反映台站间的平均相速度/群速度结构
2. 特定周期的面波反映特定深度范围的综合结果
	- 周期相同，则反映的深度范围相同


---
<!-- header: 面波层析成像
_class: hLayout
-->

二维相速度/群速度反演 <font color="#ff0000">$\Rightarrow$获得各个网格点的频散曲线 </font>
![](http://114.212.123.179:5009/api/images/20260130160501852.png)


---
<!-- header: 面波层析成像
_class: 
-->

- 相速度/群速度的<font color="#ff0000">敏感核</font>
- 网格点的相速度/群速度  <font color="#ff0000">$\Rightarrow$获得不同深度的速度 </font>
<div class=columns>
<div>

- ![image.png h:400](http://114.212.123.179:5009/api/images/20260130160501853.png)

</div><div>

* ![image.png h:400](http://114.212.123.179:5009/api/images/20260130160501854.png)
</div></div>

---
<!-- header: 面波层析成像
_class: hLayout
-->

体波成像的缺陷
![image.png](http://114.212.123.179:5009/api/images/20260130160501855.png)

+ ![image.png](http://114.212.123.179:5009/api/images/20260130160501856.png)

* ![image.png](http://114.212.123.179:5009/api/images/20260130160501857.png)


---
<!-- header: 面波层析成像
_class: hLayout
-->


体波成像的缺陷
![image.png](http://114.212.123.179:5009/api/images/20260130160501855.png)


+ 面波的优势
+ ![image.png w:400](http://114.212.123.179:5009/api/images/20260130160501858.png)

* ![image.png](http://114.212.123.179:5009/api/images/20260130160501859.png)


---
<!--
_class: contents
_header: ""
-->
# 目录

- **01**面波基本特征
- **02**面波频散曲线
- **03**面波层析成像
- **04**<font color="#ff0000">背景噪声面波</font>

---
<!-- header: 背景噪声面波
_class: hLayout
-->

![image.png w:800](http://114.212.123.179:5009/api/images/20260130160501860.png)


---
<!-- header: 背景噪声面波
_class: hLayout
-->

![image.png w:400](http://114.212.123.179:5009/api/images/20260130160501861.png)

* ![image.png h:600](http://114.212.123.179:5009/api/images/20260130160501862.png)


---
<!-- header: 背景噪声面波
_class: hLayout
-->

![image.png h:600](http://114.212.123.179:5009/api/images/20260130160501863.png)


---
<!-- header: 背景噪声面波
_class: hLayout
-->

结构时变探测
![image.png h:500](http://114.212.123.179:5009/api/images/20260130160501864.png)


---
<!-- header: 地震层析成像
_class: hLayout
-->

### 地球CT
- 射线路径 vs 敏感核
- 走时 vs 目标函数 


---
<!-- 
_class: thanks
_header: ""
-->



# 谢谢!
### 黄周传 2025春


