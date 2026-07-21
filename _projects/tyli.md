---
layout: page
title: 李庭屹
description: <small>碩士 2024 畢</small><small><small> - 具幾何特性阻流體引致渦激振動之流固耦合力學研究</small></small>
importance: 21
category: Alumni
pagefind: true
---

<span class="highlight-text"><small><small>學號：R11522536 (Ting-Yi Li)</small></small></span>

##### <span class="highlight-text">論文名稱</span>

具幾何特性阻流體引致渦激振動之流固耦合力學研究 (Study on Fluid-Structure Interaction Mechanics of Vortex-Induced Vibrations Caused by Geometrically-Featured Obstacles)

##### <span class="highlight-text">關鍵詞</span>

流固耦合、卡門渦街、有限差分法、渦激振動、勒洛多邊形 (Fluid-structure interaction, Kármán vortex street, Finite difference method, Vortex-induced vibration, Reuleaux polygon)

##### <span class="highlight-text">DOI</span>

[https://doi.org/10.6342/NTU202401692](https://doi.org/10.6342/NTU202401692)

##### <span class="highlight-text">中文摘要</span>

在流固耦合 ( Fluid-structure interaction, 簡稱FSI ) 的問題中，又可分為單向耦合 ( One-way coupling ) 與雙向耦合 ( Two-way coupling ) 兩種不同的耦合方式。在單向耦合中，可將固體結構作為流體動力學模型的邊界條件進行求解，無需考慮固體對流體的影響；在雙向耦合中，則需考慮固體對流體的影響，因此需要將流體動力學和固體力學方程式組合起來進行求解。

本論文深入探討流體動力學之經典問題–卡門渦街 ( Kármán vortex street )，即流體流至阻流體下游的兩側，因邊界層分離而產生兩非對稱排列的漩渦，其中一側的漩渦順時針轉動，另一側漩渦反方向轉動。於論文前半段進行單向耦合模擬，將阻流體設定為矩形剛體，以有限差分法為基礎並使用MATLAB自行開發流體求解器程式，藉由修改系統矩陣，以在流場中構建相應阻流體的矩形剛體區域，以符合特定流場邊界條件，來觀察阻流體下游的渦街形成過程與變化情況；於論文後半段使用商用工程軟體Ansys進行單向與雙向耦合模擬：首先設定不同幾何形狀的阻流體，包括正多邊形與勒洛多邊形，在單向耦合模擬中觀察阻流體下游的渦街結構，再於阻流體後方放置一個可變形的固體材料，以雙向耦合模擬觀察渦街引致的固體振動情況，以及流體受到固體變形影響的流場變化。

論文內容方面：第一章首先回顧流固耦合與渦激振動的研究背景與相關歷程；第二章介紹本論文使用的數值方法與模擬方法，包括有限差分法、流體求解器、修改系統矩陣以及商用軟體的模組選用；第三章驗證本論文使用流體求解器之準確性，再以此流體求解器來計算模擬矩形剛體繞流問題；第四章使用商用軟體模擬不同幾何形狀阻流體的繞流問題，再使用其流固耦合模組來觀察阻流體下游產生的渦街對固體造成的共振現象；第五章為本論文之結論與未來展望。

##### <span class="highlight-text">英文摘要</span>

In the research field of fluid-structure interaction (FSI), there are two types of coupling: one-way coupling and two-way coupling. In one-way coupling, the solid structure can be treated as a boundary condition for the fluid dynamics model without considering the influence of the solid on the fluid. In two-way coupling, the influence of the solid on the fluid must be considered, requiring the combination of fluid dynamics and solid mechanics equations for the solution.

This thesis delves into the classic problem of fluid dynamics - the Kármán vortex street. This phenomenon occurs when fluid flows past an obstacle, creating a series of asymmetrically arranged vortices downstream, with one side rotating clockwise and the other side rotating counterclockwise. In the first half of the thesis, one-way coupling simulations are conducted, setting the obstacle as a rectangular rigid body. Based on the finite difference method and using a fluid solver program developed in MATLAB, the system matrix is modified to construct the rectangular rigid body region in the flow field, matching specific flow boundary conditions, to observe the formation and evolution of the vortex street downstream of the obstacle. In the second half of the thesis, commercial engineering software Ansys is used for both one-way and two-way coupling simulations. Different geometric shapes of obstacles, including regular polygons and Reuleaux polygons, are set to observe the vortex street structures downstream of the obstacles in one-way coupling simulations. Then, a deformable solid material is placed behind the obstacle, and two-way coupling simulations are conducted to observe the vibration of the solid induced by the vortex street and the flow field changes due to the deformation of the solid.

Content of the Thesis: Chapter 1 reviews the research background and related history of fluid-structure interaction and vortex-induced vibrations. Chapter 2 introduces the numerical methods and simulation methods used in this thesis, including the finite difference method, the fluid solver, the modification of the system matrix, and the selection of modules in commercial software. Chapter 3 verifies the accuracy of the fluid solver used in this thesis and uses this solver to simulate the flow around a rectangular rigid body. Chapter 4 uses commercial software to simulate the flow around obstacles of different geometric shapes and employs its fluid-structure interaction module to observe the resonance phenomena induced by the vortex street on the solid. Chapter 5 concludes the thesis and discusses future prospects.
