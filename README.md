# yuzhou_TAS

TAS Cosmology seminar

第1次“鱼鱼聊鱼粥”微沙龙，活动简介、本学期将讨论的主要内容及宇宙学的（部分）主要内容。

## 1 概论

芝士鱼介绍了“鱼鱼聊鱼粥”微沙龙的背景、预期的内容、以及“鱼粥学”一个可能的框架。

see the slides @
[intro](https://siyizhao.github.io/yuzhou_TAS/intro/index.html)

## 2 广相1

参加讨论的鱼：zcx, wzq, zsy, tyy, zys, qqy, yxr

可参考 [在微信公众号中发表的笔记](https://mp.weixin.qq.com/s/neNO3lazsxxd-yKx1l_Uyw)， 可能存在部分typo，欢迎在本库中留言。

## 3 广相2

2022-10-8
（快乐鱼粥试点

可参考 [在微信公众号中发表的笔记](https://mp.weixin.qq.com/s/7ChW5ZvHDnyrFSY-gVrR8w)， 可能存在部分typo，欢迎在本库中留言。


## 4 Friedmann Equation

- 时间：2022年10月16日 19:00-21:00
- 地点：C楼310A
- 主讲鱼：太阳鱼

第四次鱼粥的主题是弗里德曼方程，具体地，讲述了
1. 如何描述对称性（killing vector），以及最大对称性对应的描述（killing vector的形式）
2. 如何由最大对称性（maximum symmetry）得到FLRW度规，
3. 得到度规后如何利用测地线方程（本质是利用欧拉方程）快速地得到 Christoffel symbol 的具体形式。此后只需计算Ricci tensor和Ricci scalar代入Einstein field equation便可得到Friedmann Equation

亮点标记：
1. Weinberg G&C 一书中，Riemann tensor 与一般宇宙学中的定义差一个负号。同时，规定Riemann tensor 13指标缩并为 Ricci tensor，与“一般”14缩并不同。这两个记法共同导致了其 Ricci tensor 与“一般”定义是一致的。
2. 利用测地线方程可以将 “耐心杀手” Christoffel symbol计算在4分钟内极限完成（可是主讲鱼真的做这个计算了吗？

## 5 distance measurement in cosmology

- 时间：2022年10月23日 19:00-21:00
- 地点：蒙南楼S727
- 主讲鱼：xrjj

## 6 thermal history

- 时间：2022年11月13日 ?
- 地点：蒙南楼S727
- 主讲鱼：道长鱼

## 7 inflation 1

- 时间：2022年11月20日 19:00-21:00
- 地点：4105
- 主讲鱼：zys

## 8 inflation 2

## 9 CMB

## 10 21-cm cosmology

# 2023 Spring

TAS seminar

第二期“鱼粥”开始读温伯格2019年出版的天体物理教材。
本学期预计读第一章——关于恒星的计算

## 1 intro & Hydrostatic Equilibrium

- 假设恒星内部各项同性，化简为可求解的1维方程。
- 我们有**连续性方程**和**流体静力学平衡方程**，未知量有 密度 $\rho(r)$, 压强 $P(r)$, 质量 $M(r)$, 缺一个状态方程。
- 但仍然可以得到一些初步的结论：
  - 。。。（待补充）
- 之后的小节将仔细讨论状态方程。

## 2 Radiative Energy Transport (1)

- 本节讨论 *辐射在恒星内部的传递*， 但(1)中的讨论是更宽泛的，也适用于其它天体物理环境中的辐射转移，比如光子经过IGM。

- 定义“intensity”，
- 我们考虑“intensity”的时间变化率，有四项贡献：
  - transport
  - absorption
  - scatter
  - emission
- 得到完整的辐射转移方程

$$
\begin{aligned}
\frac{\partial}{\partial t} \ell(\hat{n}, \mathbf{x}, v, t)= & -c \hat{n} \cdot \nabla \ell(\hat{n}, \mathbf{x}, v, t) \\
& -c \kappa_{\mathrm{abs}}(\mathbf{x}, v, t) \rho(\mathbf{x}, t) \ell(\hat{n}, \mathbf{x}, v, t) \\
& +c \rho(\mathbf{x}, t) \int d^2 \hat{n}^{\prime}\left[-\kappa_{\mathcal{S}}\left(\hat{n} \rightarrow \hat{n}^{\prime} ; \mathbf{x}, v, t\right) \ell(\hat{n}, \mathbf{x}, v, t)\right. \\
& \left.+\kappa_{\mathcal{S}}\left(\hat{n}^{\prime} \rightarrow \hat{n} ; \mathbf{x}, v, t\right) \ell\left(\hat{n}^{\prime}, \mathbf{x}, v, t\right)\right] \\
& +j(\mathbf{x}, v, t) \rho(\mathbf{x}, t) / 4 \pi
\end{aligned}
$$


---

本网页托管于 GitHub , 源库见 https://github.com/THU-Astro-Society/yuzhou/
