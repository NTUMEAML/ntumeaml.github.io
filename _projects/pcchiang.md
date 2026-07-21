---
layout: page
title: 姜品謙
description: <small>碩士 2022 畢</small><small><small> - 內嵌水平集函數之浸潤邊界法於流固耦合計算力學研究</small></small>
importance: 32
category: Alumni
pagefind: true
---

<span class="highlight-text"><small><small>學號：R09522533 (Pin-Chien Chiang)</small></small></span>

##### <span class="highlight-text">論文名稱</span>

內嵌水平集函數之浸潤邊界法於流固耦合計算力學研究 (A Level Set Embedded Immersed Boundary Method for Computational Mechanics Investigation of Fluid-Structure Interactions)

##### <span class="highlight-text">關鍵詞</span>

流固耦合、浸潤式邊界法、水平集函數、固體力學、計算流體力學 (Fluid-structure interaction, Immersed boundary method, Level set functions, Solid mechanics, Computational fluid dynamics)

##### <span class="highlight-text">DOI</span>

[https://doi.org/10.6342/NTU202202598](https://doi.org/10.6342/NTU202202598)

##### <span class="highlight-text">中文摘要</span>

綜觀流固耦合（Fluid-Structure Interaction）研究領域，一類的研究方法是針對剛性固體，將已知固體邊界靜態或動態資料做為流場求解之邊界條件；二類的研究方法則是考量彈性固體，乃至大變形的固體材料，進行流固耦合研究模擬，估計出流體與固體兩材料系統間的交互作用與相互引致之物理場域變化。對於巨量變形彈性固體纖維之流固耦合問題，本論文研究開發出一新式內嵌水平集（Level Sets）函數之浸潤式邊界法（Immersed Boundary Method），藉由水平集函數精準判定了彈性固體纖維材料之輪廓線位置，且透過水平集函數可更加精準地解析出浸潤式邊界法亟需之幾何量值資訊，包含：曲線形固體纖維材料單元之弧長、曲率、法線方向、切線方向與形成整體之封閉曲線面積等。基於上述計算力學理論，本論文研究實作了相應的應用數學方法，包含：水平集函數耦合流場演進、水平集函數重新初始化、徑向基函數（Radial Basis Function）插值等。

論文內容方面：第一章回顧流體與固體耦合力學的研究發展背景與相關歷程；第二章深入介紹浸潤式邊界法的核心概念，當中以拉格朗日（Lagrange）描述曲線形纖維材料之固體場域，而以歐拉（Euler）描述均勻背景網格之流體場域，並以狄拉克德他（Dirac delta）函數的平滑近似，做為歐拉場域和拉格朗日場域的速度與流固耦合力進行插值式之資訊交換，藉由固體與流場系統控制方程式之解析，對浸潤式邊界法核心部分之耦合力場進行理論推導；第三章為水平集函數之介紹，利用水平集函數基本概念：將介面位置以高一維度的空間函式來描述，並將水平集函數用於固體纖維之形狀建模與流固介面演進之追蹤；第四章為本論文之核心內容，提出用以描述固體邊界演進之水平集函數，能透過相應水平集數學方法精準解析邊界幾何量值，因而可優化原浸潤式邊界法之計算結果，透過一系列的計算例，系統性地比較出原浸潤式邊界法與內嵌水平集之浸潤式邊界法所得結果精準度之差異；第五章為論文結論與未來研究展望。

##### <span class="highlight-text">英文摘要</span>

In the research field of Fluid-Structure Interaction (FSI), one type of research method is to apply the known static or dynamic data of boundaries of rigid solids as the boundary conditions for flow field solutions; the second type of research method is to consider elastic solids and even solid materials with large deformations, and conduct the fluid-solid coupling simulation to estimate the physical field changes caused by the interaction between fluid and solid materials. For the fluid-structure coupling problems of large-deformed elastic fibers, this thesis develops a new Immersed Boundary (IB) method with embedded Level Set (LS) functions, which precisely determines locations of the elastic solid fiber materials by the LS function, and the geometric information required by the IB method includes: the arc lengths, curvatures, normal directions, tangential directions, and the area of the closed curve of the solid fiber material units. Based on the above proposed computational mechanics theory, this thesis also implements the corresponding applied mathematical methods, including: evolutions of LS functions coupled flow fields, LS function reinitializations, and radial basis function interpolation.

The thesis is organized as follows: Chapter 2 introduces the core concepts of the IB method, in which Lagrange is used to describe the solid fields of a curved fiber materials, and Euler is used to describe the fluid fields of uniform background grids, and the Dirac delta function is utilized as a smooth approximation to interpolate the velocity and fluid-solid coupling forces in the IB method for exchanging interaction information between solids and fluids. In addition, the theoretical derivation of the coupling force fields as an essential of the IB method is carried out based on governing equations of solid and flow field systems. Chapter 3 is an introduction to level set functions, which apply the basic concept of level set functions to describe solid-fluid interface positions as spatial functions in a higher dimension, and then applies the level set function to the solid fiber material. The fourth chapter is the core of this thesis, which proposes a level set function for describing the evolution of the solid boundary, which can accurately resolve the boundary geometry by the corresponding level set mathematical method, thus making the calculation results more precise. Chapter 5 concludes the thesis and proposes future research prospects.
