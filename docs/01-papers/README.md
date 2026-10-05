---
navigation:
  order: 100
---

# Papers

## Paper I — Physics from Existence I: The Equation

*The Binary-Entropy Equation $V = -H$ and the Structure of Standard-Model Parameters*

| | |
| --- | --- |
| Author | Hidekazu Kondo, Kondo Research Institute, Tokyo, Japan |
| Current version | **v4.3.0** (2026-09-26) |
| Zenodo record | <https://zenodo.org/records/22984378> · DOI 10.5281/zenodo.22984378 |
| All versions | DOI [10.5281/zenodo.19451887](https://doi.org/10.5281/zenodo.19451887) |
| Length | 38 pages (English), 45 pages (Japanese) |

### Abstract

In quantum theory the existence of a quantum object, that is, whether a mode is occupied, is in general not definite; it is given only as a probability. This paper extends this indefiniteness to existence itself: for one binary degree of freedom $n \in \{0,1\}$ with occupation probability $\sigma$ it posits three axioms, existence is bivalent ($n^2{=}n$), existence is uncertain ($\sigma{\neq}1$), and non-existence is forbidden ($\sigma{\neq}0$), and shows that these alone fix the canonical free energy $V = -H$ as an algebraic identity ($H$ is the binary Shannon entropy, $-H$ the Legendre transform of the log partition function). It then shows that the algebraic expansion of this one equation alone yields a Schrödinger equation for the internal degree of freedom, that the number of its bound states yields a structure corresponding to the Standard Model, and that this structure reproduces its 26 physical constants with no adjustable parameters; the nineteen derived here agree with measurement to 0.0006%–2.6%.

With the canonically normalised kinetic term ($g = 1$), $V = -H$ yields the Schrödinger equation as a transfer matrix; neither the depth nor the width of its well can be chosen, and it admits exactly three bound states, the three fermion generations ($N = 3$). The spatial dimension $d = 3$ follows from well preservation and gravity propagation. The Lie algebra on the finite geometry $PG(2,3)$ built from $N = 3$ corresponds to $\mathrm{SU}(3){\times}\mathrm{SU}(2){\times}\mathrm{U}(1)$.

From this structure follow $1/\alpha = 137.0368$ (0.0006%), $\sin^2\!\theta_W = 0.23122$ (<0.01%), and the charged-lepton mass ratio $R = 1.5293$ (0.006%). The absolute scale is set by the electron mass alone; without oscillation data we predict the absolute neutrino masses, $\Sigma m_\nu = 59.37$ meV, and an exact zero for neutrinoless double beta decay. These are not independent inputs: all follow from the structure fixed by $V = -H$. All values are reproducible with the accompanying code.

### Full text

The complete paper is included here as Markdown in both languages, so it can be
read in place:

| Language | Full text | Built from the manuscript sealed for v4.3.0 (SHA-256) |
| --- | --- | --- |
| English | [Physics from Existence I: The Equation](physics_from_existence.md) | `cddf906d1e0737eeecf66cf5843af888cb6b8a5cd9d28a76ed373f7e225d9a9c` |
| 日本語 | [存在からの物理学 I: The Equation](../i18n/ja/01-papers/physics_from_existence.md) | `9e3b5169c82059a071b1f8653defe3524804b6a3fb2309605b2254f5177bd812` |

In Lunascape Docs the locale switcher moves between the two; on GitHub, follow
the links above.

The sealed manuscript is written for conversion to LaTeX, so three things do not
survive a straight copy into a Markdown reader: the figures are present only as
captions, and the reference entries and two of the footnote definitions sit on
consecutive lines, which Markdown joins into a single paragraph. These pages are
therefore generated from the sealed manuscript by
[`tools/build-manuscript.py`](../../tools/build-manuscript.py), which places the
two figures and gives each reference and footnote its own line. It changes
nothing else — no wording, number, table or equation — and `--check` reports
whether a page is still up to date with its source.

The PDF remains the typeset version of record, and the Zenodo record is what to
cite.

### Files

| File | Content |
| --- | --- |
| [physics_from_existence.md](physics_from_existence.md) | Full text in Markdown, English (this documentation) |
| [i18n/ja/…/physics_from_existence.md](../i18n/ja/01-papers/physics_from_existence.md) | Full text in Markdown, Japanese (this documentation) |
| [physics_from_existence.pdf](../../paper1/physics_from_existence.pdf) | The paper (English) |
| [physics_from_existence.tex](../../paper1/physics_from_existence.tex) | LaTeX source (English) |
| [physics_from_existence_ja.pdf](../../paper1/physics_from_existence_ja.pdf) | The paper (Japanese) |
| [physics_from_existence_ja.tex](../../paper1/physics_from_existence_ja.tex) | LaTeX source (Japanese) |
| [physics_from_existence_pure.py](../../paper1/physics_from_existence_pure.py) | Pure derivation — no experimental value appears in the code |
| [physics_from_existence_verify.py](../../paper1/physics_from_existence_verify.py) | Verification — the same derivation, compared against measured values |
| `fig_potential.pdf`, `fig_pg23_v2.pdf` | Figures referenced by both LaTeX sources |

File names are fixed across versions; each release replaces their contents and is marked with a git tag (see [Releases](../04-releases/README.md)). The Zenodo record for each version holds the English PDF and TeX and the two scripts.

### Citation

> Kondo, H. (2026). *Physics from Existence I: The Equation* (v4.3.0). Zenodo. https://doi.org/10.5281/zenodo.22984378

To cite the work independently of version, use the concept DOI, which always resolves to the latest version: https://doi.org/10.5281/zenodo.19451887

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

## Paper II — Physics from Existence II: The Proof

In preparation. Several quantities shown in Paper I's tables are derived in Paper II; those rows are marked "II" in [Results](../03-results/README.md) and appear in Paper I with that attribution.
