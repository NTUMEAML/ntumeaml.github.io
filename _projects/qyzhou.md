---
layout: page
title: 周峮毅
description: <small>碩士 2024 畢</small><small><small> - 應用沉浸邊界法於具複雜幾何微流體元件之固液耦合計算力學研究</small></small>
importance: 26
category: Alumni
pagefind: true
---

<span class="highlight-text"><small><small>學號：F10522543 (Qun-Yi Zhou)</small></small></span>

##### <span class="highlight-text">論文名稱</span>

應用沉浸邊界法於具複雜幾何微流體元件之固液耦合計算力學研究 (Study on Liquid-Solid Coupling Computational Mechanics of Microfluidic Devices with Complex Geometric Using the Immersed Boundary Method)

##### <span class="highlight-text">關鍵詞</span>

微流體元件、固體力學、流體力學、流固耦合、沉浸邊界法 (Microfluidic devices、Solid mechanics、Fluid dynamics、Fluid-structure interaction、Immersed boundary method)

##### <span class="highlight-text">DOI</span>

[https://doi.org/10.6342/NTU202404352](https://doi.org/10.6342/NTU202404352)

##### <span class="highlight-text">中文摘要</span>

在微流體工程應用中，系統元件常用於細胞培養與分選實驗，其流道設計通常具有不規則、彎曲、截面積變化等複雜幾何形狀，並根據實驗目的而有所不同，本論文研究旨在針對具複雜幾何微流體元件之固液耦合問題，開發數值計算與模擬分析技術，從而建立微流體元件實驗的數位孿生。

研究架構上，以計算流體力學 (Computational Fluid Dynamics) 為流場求解核心，並使用水平集函數準確描述元件計算場域內的複雜流場邊界，且以直接強制法 (Direct-Forcing Method) 施加流場限制條件；微流體中固體材料設定為完全沉浸於流場之彈性纖維模型，通過沉浸邊界法 (Immersed Boundary Method) 中的連體力學理論，建立拉格朗日–歐拉混合 (Lagrangian-Eulerian) 的固液耦合機制，並由於直接強制法與沉浸邊界法的流場資訊皆能於交錯網格 (Staggered Grid) 中，透過有限差分法 (Finite Difference Method) 離散，因此具有完美的相容性。

本論文研究方法為基於非貼體網格 (Non-Body Fitted Mesh) 的固液耦合數值計算架構，除能考慮具複雜幾何形狀之流場邊界，特點在於流體與固體網格相互獨立生成並共存於計算場域內，得以各自直接建模，且流場網格於求解過程中，不必隨固體產生巨量變形而重新構建 (Re-Mesh)，因而在計算效率上具有一定優勢。期能以本論文之理論與計算力學研究成果，為微流體系統工程研究提供一精準的預測技術與設計工具。

##### <span class="highlight-text">英文摘要</span>

In the applications of microfluidic engineering, system components are often utilized in cell culture and sorting experiments. These components typically feature complex geometries, including irregularities, curvatures, and variations in cross-sectional areas, which vary based on the experimental objectives. This thesis aims to develop numerical computation and simulation analysis techniques for liquid-solid coupling issues in microfluidic devices with complex geometries, thereby establishing a digital twin for microfluidic device experiments.

The research framework centers on computational fluid dynamics (CFD) for solving the flow field. It employs the level set function to accurately describe the complex flow field boundaries within the computational domain and applies the direct-forcing method to impose flow field constraints. The solid materials in the microfluidics are modeled as elastic fibers fully immersed in the flow field. The coupling mechanism between the fluid and the solid is established through the Lagrangian-Eulerian framework of the immersed boundary method, which is based on continuum mechanics theory. Given that both the direct-forcing method and the immersed boundary method's flow field information can be discretized using the finite difference method on a staggered grid, they exhibit perfect compatibility.

This thesis adopts a liquid-solid coupling numerical computation framework based on non-body fitted mesh. It not only considers the complex geometries of the flow field boundaries but also features independent generation and coexistence of fluid and solid meshes within the computational domain, allowing for direct modeling of each. During the solving process, the fluid mesh does not need to be reconstructed (re-meshed) despite significant deformations of the solid, thus offering a computational efficiency advantage. It is hoped that the theoretical and computational mechanics research results of this thesis will provide precise predictive techniques and design tools for microfluidic system engineering research.
