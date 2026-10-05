---
navigation:
  title: 論文
---

# 論文

## 論文 I — 存在からの物理学 I: The Equation

*二値エントロピー方程式 $V = -H$ と標準模型パラメータの構造*

| | |
| --- | --- |
| 著者 | 近藤秀和, Kondo Research Institute, 東京 |
| 現行版 | **v4.3.0**（2026-09-26） |
| Zenodo レコード | <https://zenodo.org/records/22984378> · DOI 10.5281/zenodo.22984378 |
| 全版共通 | DOI [10.5281/zenodo.19451887](https://doi.org/10.5281/zenodo.19451887) |
| 分量 | 英語版 38 頁、日本語版 45 頁 |

### 概要

量子論では、対象の存在——モードが占有されているか否か——は一般に確定しておらず、確率としてのみ与えられる。本論文はこの量子的な存在の不確定性を「存在」そのものへ拡張し、一つの二値自由度 $n \in \{0,1\}$——モードが占有されているか否か——とその占有確率 $\sigma$ に、存在は二値的である（$n^2{=}n$）、存在は不確実である（$\sigma \neq 1$）、非存在は禁止される（$\sigma \neq 0$）の3つの公理を置き、この3つの公理だけから正準自由エネルギー V = −H が代数的恒等式として定まることを示す。ここで H は2値 Shannon エントロピーであり、−H は分配関数の対数の Legendre 変換である。さらに本論文は、この一つの方程式の代数的展開のみから内部自由度のシュレーディンガー方程式を導き、その束縛状態の数から標準模型に対応する数学的構造を導いて、この構造が標準模型の26個の物理定数を調整可能なパラメータなしに再現することを示す。うち本論文で導出する19個は、実測値と 0.0006%–2.6% の精度で一致する。

V = −H に正準規格化（$g = 1$）の運動項を合わせると、シュレーディンガー方程式が転送行列として導出される。その井戸は深さも幅も選ぶ余地がなく、フェルミオンの3世代に対応するちょうど3つの束縛状態を持つ（$N = 3$）。空間次元 d = 3 は井戸の保存と重力伝播から導かれる。$N = 3$ から構成される有限幾何 $PG(2,3)$ の上に展開されるリー代数の構造は、ゲージ群 SU(3)×SU(2)×U(1) の構造と対応する。

この構造から、1/α = 137.0368（0.0006%）、$\sin^2\!\theta_W$ = 0.23122（<0.01%）、荷電レプトン質量比 R = 1.5293（0.006%）が導かれる。絶対スケールは電子質量の一点で定め、振動データを用いずにニュートリノの絶対質量 $\Sigma m_\nu$ = 59.37 meV と、ニュートリノなし二重ベータ崩壊の厳密なゼロを予測する。これらの量は独立な入力パラメータではなく、すべて V = −H により定まる同一の数学的構造から計算される。これらの数値は全て、付属の検証コードによって再現可能である。

### 全文

論文の全文を Markdown で日英とも同梱しているので、そのまま読めます:

| 言語 | 全文 | 生成元となった v4.3.0 封印原稿の SHA-256 |
| --- | --- | --- |
| 日本語 | [存在からの物理学 I: The Equation](physics_from_existence.md) | `9e3b5169c82059a071b1f8653defe3524804b6a3fb2309605b2254f5177bd812` |
| English | [Physics from Existence I: The Equation](../../../01-papers/physics_from_existence.md) | `cddf906d1e0737eeecf66cf5843af888cb6b8a5cd9d28a76ed373f7e225d9a9c` |

Lunascape Docs ではロケール切り替えで行き来できます。GitHub では上のリンクから
辿ってください。

封印原稿は LaTeX へ変換するために書かれているので、そのまま複製すると3点が失われます。
図がキャプションだけになること、参考文献の各項目と脚注定義2件が連続行に並んでいて
Markdown では1つの段落に連結されてしまうことです。そこで本ページは封印原稿から
[`tools/build-manuscript.py`](../../../../tools/build-manuscript.py) で生成しています。
このスクリプトは図2点を配置し、参考文献と脚注をそれぞれ独立した行にするだけで、
それ以外——語句・数値・表・数式——は一切変更しません。`--check` を付けると、
ページが生成元と一致しているかを検査できます。

組版の正本は PDF であり、引用は Zenodo レコードに対して行ってください。

### ファイル

| ファイル | 内容 |
| --- | --- |
| [physics_from_existence.md](physics_from_existence.md) | 全文 Markdown（本ドキュメント、日本語） |
| [01-papers/physics_from_existence.md](../../../01-papers/physics_from_existence.md) | 全文 Markdown（本ドキュメント、英語） |
| [physics_from_existence.pdf](../../../../paper1/physics_from_existence.pdf) | 論文（英語） |
| [physics_from_existence.tex](../../../../paper1/physics_from_existence.tex) | LaTeX ソース（英語） |
| [physics_from_existence_ja.pdf](../../../../paper1/physics_from_existence_ja.pdf) | 論文（日本語） |
| [physics_from_existence_ja.tex](../../../../paper1/physics_from_existence_ja.tex) | LaTeX ソース（日本語） |
| [physics_from_existence_pure.py](../../../../paper1/physics_from_existence_pure.py) | 純粋導出——コード中に実験値は一切現れない |
| [physics_from_existence_verify.py](../../../../paper1/physics_from_existence_verify.py) | 検証——同じ導出を実測値と比較する |
| `fig_potential.pdf`, `fig_pg23_v2.pdf` | 両 LaTeX ソースが参照する図 |

ファイル名は版によらず固定で、各リリースで中身が差し替えられ、git タグが打たれます（[リリース](../04-releases/README.md) 参照）。各版の Zenodo レコードには英語版 PDF・TeX と2本のスクリプトが収められています。

### 引用

> Kondo, H. (2026). *Physics from Existence I: The Equation* (v4.3.0). Zenodo. https://doi.org/10.5281/zenodo.22984378

版によらず引用するには、常に最新版へ解決される concept DOI を使ってください: https://doi.org/10.5281/zenodo.19451887

```bibtex
@article{kondo2026pfe1,
  author    = {Kondo, Hidekazu},
  title     = {Physics from Existence I: The Equation},
  year      = {2026},
  publisher = {Zenodo},
  version   = {v4.3.0},
  doi       = {10.5281/zenodo.22984378},
  url       = {https://doi.org/10.5281/zenodo.22984378}
}
```

## 論文 II — 存在からの物理学 II: The Proof

準備中。論文 I の表に示される量のいくつかは論文 II で導出されるもので、[結果](../03-results/README.md) では「II」と印を付け、論文 I でもその帰属で示されています。
