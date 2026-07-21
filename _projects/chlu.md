---
layout: page
title: 呂季鴻
description: <small>碩士 2025 畢</small><small><small> - 主動調諧質量阻尼器於機械系統之振動解析與原型實驗研究</small></small>
importance: 16
category: Alumni
pagefind: true
---

<span class="highlight-text"><small><small>學號：R12522502 (Chi-Hung Lu)</small></small></span>

##### <span class="highlight-text">論文名稱</span>

主動調諧質量阻尼器於機械系統之振動解析與原型實驗研究 (Vibration Analysis and Prototype Experimentation of Active Tuned Mass Dampers in Mechanical Systems)

##### <span class="highlight-text">關鍵詞</span>

主動式調諧質量阻尼器、控制策略、振動模擬、最佳化設計、樂高 EV3 (Active Tuned Mass Damper, Control strategy, Vibration modeling, Optimal design, LEGO EV3)

##### <span class="highlight-text">DOI</span>

[https://doi.org/10.6342/NTU202503950](https://doi.org/10.6342/NTU202503950)

##### <span class="highlight-text">中文摘要</span>

本研究旨在針對單自由度結構於不同加速度激振環境下的振動控制問題，提出一套具備控制力方向切換功能之主動式調諧質量阻尼器（Active Tuned Mass Damper, ATMD）控制架構。系統設計融合數值模擬與實驗驗證，透過 MATLAB 進行動態響應做最佳化設計，並結合樂高 EV3 平台進行控制實驗驗證。

本研究建構一套以雙質量系統為基礎的動態模型，包含主結構與調諧阻尼器，兩者透過橡皮筋與振動元件連接。控制策略設計上，導入可調整的控制力方向，並引入控制時間參數以及控制力係數。透過不同方向控制力輸入，使主結構振動位移響應最佳化，並將位移響應控制在設計之不同工作長度內。為提升控制效益，進一步應用 MATLAB 內建之 fmincon 最佳化演算法，調整控制參數並做最佳化設計。

最佳化振動模擬實例包含不同頻率加速度比較、不同振幅加速度比較、不同頻率組合之合成加速度輸入以及各大歷史地震加速度，探討在不同工作長度之最佳化模擬結果。在實驗方面，本研究使用樂高EV3為實驗器材，比較控制力為同方向與反方向兩種情境下對系統位移響應。結果顯示，反向控制力策略在合理控制下，能有效增加主結構振動位移響應，達成更好的振動控制效益。

綜上所述，本研究成功建立一套具調控控制力方向與參數最佳化功能之 ATMD 控制系統，並透過模擬與實驗雙重驗證其效能。未來研究可延伸應用於多自由度或非線性結構系統，並結合機器學習技術進行自動化控制策略設計，以進一步提升振動能量的控制與回收效率。

##### <span class="highlight-text">英文摘要</span>

This study focuses on vibration control of a single-degree-of-freedom (SDOF) structure under different acceleration excitation environments. A control framework for an Active Tuned Mass Damper (ATMD) system is proposed, incorporating the ability to switch the direction of control forces. The system integrates parameter-based modeling and experimental validation, with optimization conducted through MATLAB simulations. The control strategy is implemented on the EV3 platform to carry out experimental verification.

The proposed system is built upon a two-degree-of-freedom dynamic model with mass-spring-damper components, including the primary structure and the control mass. A controllable force is applied via actuators, allowing adjustment of both magnitude and direction. The strategy introduces control timing parameters and force gain coefficients. By optimizing force input in both directions, the system can achieve effective displacement control. The control parameter tuning is performed using MATLAB’s fmincon optimization solver to obtain the best performance under various working lengths.

The optimization cases consider comparisons across different excitation frequencies, amplitudes, speed ratios, and waveform combinations, including historical earthquake records. The results demonstrate that the reverse-direction control strategy, when properly tuned, can reduce the displacement of the primary structure more effectively than traditional methods, achieving superior vibration suppression benefits.

Experimentally, the EV3 platform is used to validate system performance under various directional control inputs. Results show that bidirectional force control leads to better displacement reduction of the main structure. The system proves robust and efficient under different scenarios.

In conclusion, this study successfully develops an ATMD system with adjustable bidirectional control forces and validates its performance through both simulations and experiments. The proposed framework may be extended to more complex nonlinear structural systems in the future, incorporating machine learning techniques to enable automated control strategy development and further enhance vibration energy harvesting efficiency.
