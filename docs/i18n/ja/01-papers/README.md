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
| 現行版 | **v4.2.0**（2026-09-21） |
| Zenodo レコード | <https://zenodo.org/records/22883521> · DOI 10.5281/zenodo.22883521 |
| 全版共通 | DOI [10.5281/zenodo.19451887](https://doi.org/10.5281/zenodo.19451887) |
| 分量 | 英語版 38 頁、日本語版 45 頁 |

### 概要

標準模型の26個の自由パラメータを同時に導出した理論は存在しない。本論文は、一つの二値自由度とその占有確率 $\sigma$ を出発点として、量子論の基本方程式であるシュレーディンガー方程式と標準模型に対応する構造を導く。

置く公理は、存在は二値的である（$n \in \{0,1\}$、$n^2{=}n$）、存在は不確実である（$\sigma \neq 1$）、非存在は禁止される（$\sigma \neq 0$）の3つだけである。Fermi–Dirac の占有統計を与える分配関数の対数を Legendre 変換すると、$V = -H(\sigma)$ が代数的恒等式として得られる。$H$ は二値 Shannon エントロピーであり、$-H$ は一つの二値自由度の正準自由エネルギーである。

正準規格化した運動項（$g = 1$）を合わせると、転送行列の連続極限からシュレーディンガー方程式が導かれる。井戸の深さ $\ln 2$ と幅は固定され、束縛状態はちょうど3つであり（$N = 3$）、フェルミオンの3世代に対応する。空間次元 d = 3 は井戸の保存と重力伝播から定まる。$N = 3$ から構成される有限幾何のリー代数構造が SU(3)×SU(2)×U(1) に対応する。

本論文で導出する19個は実測値と 0.0006%–2.6% で一致し、Paper II で導出する7個と合わせ、26個の物理定数が調整可能なパラメータなしに再現される。1/α = 137.0368（0.0006%）、$\alpha_s(M_Z)$ = 0.1179（0.07%）、$\sin^2\!\theta_W$ = 3/13 = 0.23077（次補正込みで $M_Z$ において 0.23122、<0.01%）、荷電レプトン質量比 $R = \ln(m_\tau/m_e)/\ln(m_\mu/m_e) = 1.5293$（0.006%）、$\sin\theta_C$ = 0.2245（0.10%；遮蔽後 0.22435）を含む。電子質量 $m_e$ で絶対スケールを定め、振動データを用いずにニュートリノの絶対質量（$\Sigma m_\nu$ = 59.37 meV）を予測する。ニュートリノなし二重ベータ崩壊は厳密にゼロと予測される。これらの数値は全て、付属の検証コードによって再現可能である。

### 全文

論文の全文を Markdown で日英とも同梱しているので、そのまま読めます:

| 言語 | 全文 | 生成元となった v4.2.0 封印原稿の SHA-256 |
| --- | --- | --- |
| 日本語 | [存在からの物理学 I: The Equation](physics_from_existence.md) | `2562ed92ad61d3ab62fef9060e3a367a246e293c8c88483f36ad320c71d6a525` |
| English | [Physics from Existence I: The Equation](../../../01-papers/physics_from_existence.md) | `84a499b127a06402533742514f760445a36b2f92b4f81cc0cce0012edf4962d8` |

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

> Kondo, H. (2026). *Physics from Existence I: The Equation* (v4.2.0). Zenodo. https://doi.org/10.5281/zenodo.22883521

版によらず引用するには、常に最新版へ解決される concept DOI を使ってください: https://doi.org/10.5281/zenodo.19451887

```bibtex
@article{kondo2026pfe1,
  author    = {Kondo, Hidekazu},
  title     = {Physics from Existence I: The Equation},
  year      = {2026},
  publisher = {Zenodo},
  version   = {v4.2.0},
  doi       = {10.5281/zenodo.22883521},
  url       = {https://doi.org/10.5281/zenodo.22883521}
}
```

## 論文 II — 存在からの物理学 II: The Proof

準備中。論文 I の表に示される量のいくつかは論文 II で導出されるもので、[結果](../03-results/README.md) では「II」と印を付け、論文 I でもその帰属で示されています。
