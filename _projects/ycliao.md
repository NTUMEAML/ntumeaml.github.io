---
layout: page
title: 廖晏晨
description: <small>碩士 2019 畢</small><small><small> - 應用有限元素分析於纖維化肺組織之力學研究</small></small>
importance: 37
category: Alumni
pagefind: true
---

<span class="highlight-text"><small><small>學號：607380036 (Yen-Chen Liao)</small></small></span>

##### <span class="highlight-text">論文名稱</span>

應用有限元素分析於纖維化肺組織之力學研究 (Application of Finite Element Analysis for Mechanics Study on Pulmonary with Fibrosis Diseases)

##### <span class="highlight-text">關鍵詞</span>

肺纖維化、生物計算力學、有限元素法、板殼元素、FEBio software suite、程式語言設計 (Pulmonary fibrosis, Biocomputational mechanics, Finite element method, Plate and shell elements, FEBio software suite, Programming language design)

##### <span class="highlight-text">DOI</span>

[https://doi.org/10.6846/TKU.2019.00447](https://doi.org/10.6846/TKU.2019.00447)

##### <span class="highlight-text">中文摘要</span>

有限元素法為學術研究與先進工程仰賴之計算方法，能夠針對具有幾何外型特徵之連續固體或結構系統，精準求得系統受外力刺激所造成的力學及物理反應的場域分佈，近年來除應用於固體力學與結構工程學門外，更受到生物醫學工程領域的重視。

本論文利用有限元素分析軟體 FEBio 結合美國國家衛生研究院 (NIH)所提供的肺臟 STL 模型，模擬肺纖維化前後再進行吸氣時所受到的力學狀態，在解讀程式經計算後所得出的結果。研究主要可分為三個階段，分別為 MATLAB 程式撰寫、模型與分析條件設置、歸納分析之成果。

首先先介紹 MATLAB 程式撰寫，本研究肺臟模型所希望之元素設定為板殼元素，但由於 STL 模型匯入 FEBio 中無法設定為板殼元素，所以利用 MATLAB 開發轉檔程式，藉由讀取設定分析參數的文字輸入檔和 STL 模型檔，將參數與模型資料寫成 FEBio 專有的 FEB 檔案格式儲存，便可解決板殼元素設定之問題；二為模型與分析條件設置，根據參考文獻設計纖維化區域為散佈於肺葉上與集中在支氣管上，另外也尋找相關資料設計模型的邊界條件參數；最後階段為歸納分析結果，在同樣的分析條件下，從兩個肺纖維化模型的分析結果去比較，並找出相關的規則加以歸納之。

##### <span class="highlight-text">英文摘要</span>

The finite element method is a calculation method based on academic research and advanced engineering. It can accurately determine the field distribution of mechanical and physical reactions caused by external force stimulation for continuous solid or structural systems with geometric appearance characteristics. Applied to solid mechanics and structural engineering, it is also valued in the field of biomedical engineering.

In this thesis, the finite element analysis software FEBio is combined with the lung STL model provided by the National Institutes of Health (NIH) to simulate the mechanical state of inhalation before and after pulmonary fibrosis. The results obtained after the calculation of the interpretation program are calculated. The research can be divided into three stages, which are the results of MATLAB programming, model and analysis condition setting, and inductive analysis.

First, the MATLAB programming is introduced. The desired element of the lung model is set as the shell element. However, since the STL model cannot be set as the shell element in FEBio, the MATLAB development of the conversion program is used to analyze the reading configuration. The text input file and STL model file of the parameter, the parameters and model data are written into FEBio''s proprietary FEB file format storage, which can solve the problem of setting the plate and shell elements. Secondly, the model and analysis conditions are set, and the fiberized area is designed according to the reference. In order to spread on the lungs and concentrate on the bronchus, the boundary condition parameters of the relevant data design model are also sought. The final stage is the inductive analysis result. Under the same analysis conditions, the analysis results of the two pulmonary fibrosis models are compared. And find out the relevant rules to summarize them.
