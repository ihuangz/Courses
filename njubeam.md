---
marp: true
theme: njubeam
paginate: true
math: katex
footer: "**黄周传** **地球物理基础** **2025春**"
---
<!-- _class: title -->
# 地球物理基础

### Zhouchuan Huang

 #### 南京大学 地球科学与工程学院

#### 2025年春

![logo GitHub Logo](http://114.212.123.179:5009/api/images/20260130160517889.png)


---

<!--
_class: contents
_header: ""
-->

# 目录

- **01**多层介质折射波走时方程
- <font color="#ff0000">**02**倾斜界面折射波</font>
- **03**起伏界面折射波
- **04**天然地震
- **05**天然地震折射波


---
<!-- 
_header: three columns
_class: hLayout
-->

- test
- test
- 


column 1

+ column 2

- column 3
---
<!-- 
_header: three columns
_class: hLayout
-->

 + ### 上倾方向

+ $$t_u=\frac{x\sin(\alpha-\varphi)}{v_1}+\frac{2h_u\cos\alpha}{v_1}$$

+ 视速度： $v_u^*=v_1/\sin(\alpha-\varphi)$
+ 截距为： $t_{0u}=2h_u\cos\alpha/v_1$

- ### 下倾方向
- $$t_d=\frac{x\sin(\alpha+\varphi)}{v_1}+\frac{2h_d\cos\alpha}{v_1}$$

 - 视速度： $v_d^*=v_1/\sin(\alpha+\varphi)$
 - 截距为： $t_{0d}=2h_d\cos\alpha/v_1$


---
<!-- header: test
_class: hLayout
-->

- ### column 1
- $$\begin{equation*} \begin{aligned} a &= b+c  \\  &= c+d \end{aligned} \end{equation*}$$
- $$\begin{matrix}已知y=\sqrt{x+3}&&(x>=0)\\求y的最大值是多少 \end{matrix}$$
- $$\begin{bmatrix}已知y=\sqrt{x+3}&&(x>=0)\\求y的最大值是多少 \end{bmatrix}$$
 - $$\begin{Bmatrix}已知y=\sqrt{x+3}&&(x>=0)\\求y的最大值是多少 \end{Bmatrix}$$
+ ### column 2
+ $$\begin{vmatrix} 0&1&2\\ 3&4&5\\ 6&7&8 \end{vmatrix}$$
+ $$\begin{Vmatrix}0&1&2\\ 3&4&5\\ 6&7&8\end{Vmatrix}
$$
+ $$ f(x)=\begin{cases} x+1, & x>0 \\ x^2 + 1, & x<0 \end{cases}$$
- ### column 3
- $$\begin{equation*}\begin{aligned}a^x−1 &\sim x\ln⁡a \\ \log_a​(x+1) &\sim \frac{x}{\ln a}​\end{aligned}\end{equation*}$$


- $$\begin{equation*}\begin{aligned} & a^x−1 \sim x\ln⁡a \\ & \log_a​(x+1) \sim \frac{x}{\ln a}​ \end{aligned} \end{equation*}$$



---
<!-- header: Columns -->

<div class="columns">
  <div>

  ### Column 1


![center w:400px](http://114.212.123.179:5009/api/images/20260130160517891.png) 

  </div>
  <div >

  ### Column 2

so many many words, so many many words, so many many words, 
  so many many words, 
  </div>


  <div >

  ### Column 3

so many many words, so many many words, so many many words
  </div>


  <div >

  ### Column 4

so many many words, so many many words, so many many words
  </div>

</div>

---
<!-- header: 'MarkdownIt Plugins' -->

There are many many words. There are many many words. There are many many words. There are many many words. There are many many words. There are many many words. There are many many words. There are many many words. There are many many words. There are many many words. There are many many words. There are many many words. 

$$ E_{\theta}[\theta] = \int_{\theta}\theta\ p(\theta)\ d\theta = \int_{\theta}\theta\ p(\theta)\ d\theta = \int_{\theta}\theta\ p(\theta)\ d\theta $$

---
<!-- header: 'Normal text' -->
**This** is what a regular slide can look like in Neobeam.
- A cool fact
- Interesting tidbit

My favorite letters are:
1. A
2. B
3. C

A quote from my favorite author
> "Hello" - Author Cool 2024

---
<!-- header: 'Code blocks' -->
We can define ``variables`` inline, and code in blocks (with syntax highlighting!!!):
```java
    if (marp) {
        apply.neobeam();
    }
```
---
<!-- header: 'Mathematics corner' -->
## Formulas
> The length of a **vector** can be computed by the following formula
> $$
||\overline v|| = \sqrt{a^2 + b^2} \\
\text{where } \overline v = (a,b)
$$
## Definitions
Blockquotes with level 4 (####) headings inside get translated to definitions like:

> #### Vector
> A collection of numbers

---
<!-- header: 'Data' -->

Tables are also decorated in this theme!Tables are also decorated in this theme!Tables are also decorated in this theme!Tables are also decorated in this theme!

| Left Row | Center Row | Right row | Right row    Right row | Right row    Right row |
| :------- | :--------: | --------: | ---------------------: | ---------------------: |
| Some     |    Cool    |      Data |         Data Right row |         Data Right row |
| Some     |    Cool    |      Data |                   Data |                   Data |


Tables are also decorated in this theme!Tables are also decorated in this theme!Tables are also decorated in this theme!Tables are also decorated in this theme!

---
<!-- header: 'Images' -->

![text:center w:700px](https://images.unsplash.com/photo-1601247387326-f8bcb5a234d4?q=80&w=2071&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D) 

Images can be left-aligned, centered, and right-aligned! 

---
<!-- header: 'HTML wonderland' -->

## These are all the HTML elements I've styled!

Text can be <mark>marked</mark>, <abbr title="abbreviated">abbr</abbr> and you **can** *quote* <u>things</u> inline <q>like this</q>.

[A video](https://git.nju.edu.cn/huangz/images/-/raw/main/pictures/2025/03/23_12_0_11_test.mp4)

---
<!--
_header: 双列排版
-->

<div class="columns"> 

<div class="column2">

### 第一项

这是一个多列文本示例。文本将自动分成<mark>三列</mark>显示。 这是一个多列文本示例。文本将自动分成三列显示。 这是一个多列文本示例。文本将自动分成三列显示。 这是一个多列文本示例。文本将自动分成三列显示。 这是一个多列文本示例。
$$ \frac {\partial^r} {\partial \omega^r} \left(\frac {y^{\omega}} {\omega}\right) = \left(\frac {y^{\omega}} {\omega}\right) \left\{(\log y)^r + \sum_{i=1}^r \frac {(-1)^i r \cdots (r-i+1) (\log y)^{r-i}} {\omega^i} \right\} $$
</div> 

<div >


![center w:400px](http://114.212.123.179:5009/api/images/20260130160517891.png) 

</div> 

</div>

---
<!--
_header: 多列
-->
## This is the heading over all columns

<div class="columns">
<div class="column2">

## Column 1


1) One
2) Two
3) Three
4) Four
5) Five
6) Six

</div>
<div >

## Column 2

![width:200px](http://114.212.123.179:5009/api/images/20260130160517893.jpg)

$$ \frac {\partial^r} {\partial \omega^r} \left(\frac {y^{\omega}} {\omega}\right) = \left(\frac {y^{\omega}} {\omega}\right) \left\{(\log y)^r + \sum_{i=1}^r \frac {(-1)^i r \cdots (r-i+1) (\log y)^{r-i}} {\omega^i} \right\} $$
</div>
<div >

## Column 3
Lorem ipsum dolor sit amet consectetur, adipisicing elit. Nam placeat debitis labore quidem exercitationem architecto.

</div>
</div>

---
<!-- 
_class: thanks
_header: ""
-->

# 谢谢!
### 黄周传 2025春

