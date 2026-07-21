---
layout: page
title: 陳宣伃
description: <small>碩士 2024 畢</small><small><small> - 應用淺層神經網路技術於非線性材料之機械力學特性識別研究</small></small>
importance: 24
category: Alumni
pagefind: true
---

<span class="highlight-text"><small><small>學號：R11522556 (Shiuan-Yu Chen)</small></small></span>

##### <span class="highlight-text">論文名稱</span>

應用淺層神經網路技術於非線性材料之機械力學特性識別研究 (Application of Shallow Neural Network Techniques in Identification of Mechanical Properties of Nonlinear Materials)

##### <span class="highlight-text">關鍵詞</span>

固體力學、非線性材料、有限元素法、機器學習、神經網路 (Solid Mechanics, Nonlinear Materials, Finite Element Method, Machine Learning, Neural Networks)

##### <span class="highlight-text">DOI</span>

[https://doi.org/10.6342/NTU202402074](https://doi.org/10.6342/NTU202402074)

##### <span class="highlight-text">中文摘要</span>

本論文研究旨在應用淺層神經網路技術，識別非線性材料之機械力學特性。研究使用有限元素法 (Finite Element Method，簡記為 FEM) 對材料單元素模型進行拉伸，模擬實際實驗之材料拉伸行為，以獲取材料質點之應力─應變曲線，對曲線使用 MATLAB 之曲線擬合功能轉換為一組特定指標，將具有一定規模數目之原始應力對應應變資訊，縮減為可代表各曲線特徵的關鍵變數指標組，一組指標即代表一條應力─應變曲線，不僅大幅減少了輸入變數之數量，亦使本研究使用之前饋式神經網路更易於有效地學習非線性材料機械力學曲線之特徵。

本論文實作應用含有四層隱藏層的淺層神經網路，針對前述轉換非線性材料應力─應變曲線得到的指標組進行學習，並預測出能夠呈現材料機械力學特性的特定參數，包括且不侷限於材料之彈性模數與體積模數等參數群，對於許多機械工程應用之材料建構與設計具有重要意義。再者，本論文研究方法具另一顯著的優勢，通過有限元素法，得以直接獲取模型訓練所需之輸入變數和輸出變數，從而避免了對訓練數據進行額外標註的繁瑣過程，此數據蒐集方式確保了訓練數據的準確性和一致性，因而顯著地提高了識別實作的效率。

綜上所述，本研究提出了一種高效且準確的方法，成功透過有限元素法直接獲取模型的訓練數據，並利用淺層神經網路進行非線性材料機械力學特性識別，為先進材料特性相關之尖端工程應用，展開了新的思路。

##### <span class="highlight-text">英文摘要</span>

This study aims to apply shallow neural network technology to identify the mechanical properties of nonlinear materials. The study utilizes the finite element method to perform tensile tests on single-element models, simulating the tensile behavior of materials in actual experiments to obtain stress-strain curves of material points. MATLAB curve-fitting functionality is employed to convert these curves into a set of specific indicators. The original stress-strain data, of considerable scale, is thus reduced to key variable indicators representing the characteristics of each curve. One set of indicators represents one stress-strain curve, significantly reducing the number of input variables and facilitating the feedforward neural network used in this study to learn the features of nonlinear material mechanical properties more effectively.

This study implements a shallow neural network with four hidden layers to learn from the indicators as mentioned above derived from nonlinear material stress-strain curves and to predict specific parameters that reflect the mechanical properties of materials. These parameters include but are not limited to, the elastic modulus and bulk modulus. This is of significant importance for material construction and design in various mechanical engineering applications. Furthermore, the research method in this study has another notable advantage: using the finite element method, the input and output variables required for model training can be directly obtained, thereby avoiding the tedious process of additional labeling of training data. This data collection method ensures the accuracy and consistency of the training data, significantly improving the efficiency of the identification implementation.

In summary, this study proposes an efficient and accurate method for obtaining training data directly through the finite element method and using shallow neural networks to identify the mechanical properties of nonlinear materials. This opens up new avenues for advanced engineering applications related to the properties of advanced materials.
