---
layout: page
title: 楊昕珮
description: <small>碩士 2024 畢</small><small><small> - 融合材料內聚力之有限元素分析於變形速率相依與週期輪廓界面之機械強度解析</small></small>
importance: 20
category: Alumni
pagefind: true
---

<span class="highlight-text"><small><small>學號：R11522526 (Shin-Pei Yang)</small></small></span>

##### <span class="highlight-text">論文名稱</span>

融合材料內聚力之有限元素分析於變形速率相依與週期輪廓界面之機械強度解析 (Finite Element Analysis of Mechanical Strength on Deformation Rate-Dependent and Periodic Profile Interfaces with Cohesive Zone Models)

##### <span class="highlight-text">關鍵詞</span>

有限元素法、使用者定義元素、內聚力模型、黏彈性內聚力模型、內聚力模型參數評估、正弦波界面 (Finite Element Method, User-Defined Elements, Cohesive Zone Model, Viscoelastic Cohesive Zone Model, Evaluation of Cohesive Zone Model Parameters, Sinusoidal Interface)

##### <span class="highlight-text">DOI</span>

[https://doi.org/10.6342/NTU202401938](https://doi.org/10.6342/NTU202401938)

##### <span class="highlight-text">中文摘要</span>

本研究首先使用材料界面之指數型內聚力模型，透過Abaqus使用者定義元素功能，自行定義內聚力元素之牽引力-分離律，建構內聚力元素於三維空間中之機械力學表現。在建構內聚力元素時，需建立其幾何定義、積分點資訊、形狀函數、法向與切向單位向量、法向與切向分離位移、節點力及切線剛度矩陣。再透過上下塊材搭配單一內聚力元素之模擬，並與數學解析做比較，得以驗證內聚力元素之正確性。

對於高分子或是合金材料，其界面強度具有分離速率相依的特性，故本論文嘗試以兩種方式將內聚力模型與黏彈性材料模型結合，分別為將內聚力模型與Maxwell模型並聯，與內聚力模型與Kelvin模型串聯，得到界面分離速率相依之黏彈性內聚力模型。本論文詳細說明黏彈性內聚力模型理論之推導過程，並分別建構內聚力元素，最後亦將內聚力元素之模擬結果與方程式之計算結果進行比對與驗證。

在實驗量測方面，一常用方法為透過雙懸臂樑變形量測做出界面法向開裂之內聚力模型參數評估，本論文實作材料界面指數型內聚力模型參數評估程序，且驗證數學模型與參數的準確性。再以兩種黏彈性內聚力模型描述雙懸臂樑之材料界面性質，得出在改變雙懸臂樑分離速率下，會得到不同的界面強度表現。

考量在工程與生物材料之界面多為不平整表面，因此本論文建構二維之正弦波輪廓界面，探討界面幾何與界面強度之特性。經由調整波形幾何特徵，並以模擬結果與數學模型相互驗證，得以總結改變界面內聚力模型參數，材料界面強度隨之受到影響，並且總體接觸面積在材料界面強度上扮演至關重要的角色。最後，使用黏彈性內聚力模型定義正弦波界面，將產生速率相依的表現。

##### <span class="highlight-text">英文摘要</span>

This study first employs an exponential cohesive zone model of material interface and utilizes the user-defined element in Abaqus to define the traction-separation law of cohesive elements, thereby constructing the mechanical behavior of cohesive elements in three-dimensional space. During the construction of cohesive element, geometric definitions, integration point information, shape functions, normal and tangential unit vectors, normal and tangential separation displacement, nodal forces, and tangent stiffness matrices need to be established. The simulation of cohesive elements is then performed in conjunction with upper and lower bulk materials, and compared with the analytical solution to verify the cohesive elements.

For polymer or alloy materials, the strength of interface exhibits rate-dependent characteristics. Hence, this thesis attempts to combine the rate-independent cohesive zone model with viscoelastic material models in two ways: combining a rate-independent cohesive zone model with a Maxwell element in parallel, and combining a rate-independent cohesive zone model with a Kelvin element in series, resulting in rate-dependent viscoelastic cohesive zone models. This thesis elaborates on the derivation of the viscoelastic cohesive zone model theory, constructs cohesive elements, and finally verifies the simulation results of cohesive elements against the results calculated from equations.

Regarding experimental measurements, a commonly used method involves using the double cantilever beam test to evaluate the parameters of cohesive zone models for normal opening of interface. This thesis implements the parameter evaluation procedure for the exponential cohesive zone model of material interfaces and verifies the accuracy of the mathematical model and parameters. Furthermore, the material interface properties of the double cantilever beam are described using two viscoelastic cohesive zone models, and it can be concluded that under different opening velocities, different interface strength performances are obtained.

Considering that interfaces in engineering and biological materials are often uneven surfaces, this thesis constructs a two-dimensional model of sinusoidal profile interface to investigate the characteristics of geometry and interface strength. By adjusting the geometric characteristics of the waveform and verifying the simulation results with mathematical models, it is concluded that changing the parameters of the cohesive zone model of the interface affects the strength of interface. Moreover, the total contact area plays a crucial role in the strength of overall interface. Finally, using viscoelastic cohesive zone models to define the sinusoidal interface will result in rate-dependent behavior.
