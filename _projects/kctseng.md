---
layout: page
title: 曾高捷
description: <small>碩士 2024 畢</small><small><small> - 應用有限元素法於材料強度校準之逆向工程研究</small></small>
importance: 23
category: Alumni
pagefind: true
---

<span class="highlight-text"><small><small>學號：R11522543 (Shao-Hong Liao)</small></small></span>

##### <span class="highlight-text">論文名稱</span>

應用有限元素法於材料強度校準之逆向工程研究 (Reverse Engineering Study of Material Strength Calibration Using Finite Element Method)

##### <span class="highlight-text">關鍵詞</span>

逆向工程、非線性材料、有限元素法、參數校準、顯式動力學分析 (Reverse engineering, Nonlinear materials, Parameter calibration, Explicit dynamic analysis, Finite element method)

##### <span class="highlight-text">DOI</span>

[https://doi.org/10.6342/NTU202401484](https://doi.org/10.6342/NTU202401484)

##### <span class="highlight-text">中文摘要</span>

本研究論文分別探討三個不同逆向工程實例：行動電子裝置落摔、高分子薄膜球擊和汽車殼體撞擊，旨在透過逆向工程方法校準出真實材料參數。首先，電子裝置落摔實例中，分析了壓敏膠（Pressure sensitive adhesive）的黏彈性行為和中框鋁材的塑性變形特性。其次，對於薄膜球擊實例，重點研究高分子薄膜的預拉力和線性彈性材料楊氏模數。再者，於汽車殼體撞擊實例中，主要探究殼體鋁材的楊氏模數和降伏應力。

在逆向工程實例操作中，本研究結合有限元素分析軟體 Abaqus 和自行開發 Python 程式進行自動化分析：模型透過 Python 進行自動化網格收斂性分析，以確保模型計算的可靠度；材料參數校準方面，使用均方根誤差定義目標函數，並進行參數域設定與參數敏感度測試，以確保校準結果的準確性；透過結合 Python 函式庫 Brent 與 Nelder-Mead 演算法，與 Abaqus 計算做整合，以完成材料參數評估逆向工程實作。最後經由掃描參數域中的所有可能值，繪製誤差強度等高線圖，驗證最佳材料參數之合適性。

研究證明，目標函數參數的敏感度測試於逆向工程操作具有重要意義，且誤差強度圖有助於理解尋找最適解的收斂狀況。在行動電子裝置落摔實驗中，成功擬合出三組模擬曲線和一組實驗曲線，並精確地求得合適的材料參數。此外，於高分子薄膜球擊和汽車殼體撞擊的模擬中，使用四個不同的初始猜測點進行參數搜尋測試，結果皆顯示與預設之模擬曲線相符的材料參數，證明本研究開發逆向工程方法的有效性與可靠性。

本論文之實例研究展示逆向工程技術在材料參數校準上的應用潛力，透過有限元素分析軟體 Abaqus 和自行開發 Python 程式的結合，實現系統關鍵元件材料參數校準逆向工程的自動化操作，使其未來能夠擴展出更多層面的開發，為未來相關先進工程設計與科學理論研究，以數據做為研究成果最為堅實的支持。

##### <span class="highlight-text">英文摘要</span>

This research paper explores three distinct reverse engineering cases: mobile electronic device drop, polymer film ball impact, and automotive shell impact, aiming to calibrate the real material parameters through reverse engineering methods. First, in the case of the electronic device drop, we analyzed the viscoelastic behavior of the pressure-sensitive adhesive (PSA) and the plastic deformation characteristics of the aluminum middle frame. Secondly, for the polymer film ball impact case, the focus was on the pre-tension and the Young's modulus of the linear elastic material of the polymer film. Lastly, in the automotive shell impact case, the primary investigation was on the Young's modulus and yield stress of the shell's aluminum material.

In these reverse engineering cases, this study combined the finite element analysis software Abaqus with self-developed Python programs for automated analysis: the model underwent automated mesh convergence analysis via Python to ensure the reliability of the calculations; for material parameter calibration, the root mean square error was used to define the objective function, and parameter domain settings and sensitivity tests were conducted to ensure the accuracy of the calibration results; by integrating the Python libraries Brent and the Nelder-Mead algorithm with Abaqus calculations, material parameter evaluation and reverse engineering implementation were achieved. Finally, by scanning all possible values within the parameter domain, error intensity contour plots were drawn to verify the suitability of the optimal material parameters.

The research demonstrated that sensitivity testing of the objective function parameters is significant in reverse engineering operations, and the error intensity plot aids in understanding the convergence of finding the optimal solution. In the mobile electronic device drop test, three sets of simulated experiment curves and one set of real experiment curves were successfully fitted, and appropriate material parameters were accurately obtained. Additionally, in the polymer film ball impact and automotive shell impact simulation experiments, parameter search tests using four different initial guess points showed material parameters consistent with the preset simulated experiment curves, proving the effectiveness and reliability of the reverse engineering method developed in this study.

The case studies in this paper showcase the potential applications of reverse engineering techniques in material parameter calibration. By combining the finite element analysis software Abaqus with self-developed Python programs, the automation of reverse engineering for key component material parameter calibration is realized, enabling future expansion into more areas of development. This provides solid data support for future advanced engineering design and scientific theoretical research.
