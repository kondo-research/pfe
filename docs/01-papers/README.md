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
| Current version | **v4.2.0** (2026-09-21) |
| Zenodo record | <https://zenodo.org/records/22883521> · DOI 10.5281/zenodo.22883521 |
| All versions | DOI [10.5281/zenodo.19451887](https://doi.org/10.5281/zenodo.19451887) |
| Length | 38 pages (English), 45 pages (Japanese) |

### Abstract

No theory derives the 26 free parameters of the Standard Model simultaneously. From one binary degree of freedom and its occupation probability $\sigma$, we derive the Schrödinger equation, the basic equation of quantum theory, and a structure corresponding to the Standard Model.

The paper posits only three axioms: existence is binary ($n \in \{0,1\}$, $n^2{=}n$), existence is uncertain ($\sigma{\neq}1$), and non-existence is forbidden ($\sigma{\neq}0$). The Legendre transform of the logarithm of the partition function that gives Fermi–Dirac occupation statistics yields $V = -H(\sigma)$ as an algebraic identity, where $H$ is the binary Shannon entropy and $-H$ is the canonical free energy of one binary degree of freedom.

With the canonically normalised kinetic term ($g = 1$), a Schrödinger equation follows from the continuum limit of the transfer matrix. The depth $\ln 2$ and the width of the well are fixed; it has exactly three bound states ($N = 3$), corresponding to the three fermion generations. The spatial dimension $d = 3$ follows from well preservation and gravity propagation. The Lie algebra on the finite geometry built from $N = 3$ corresponds to $\mathrm{SU}(3){\times}\mathrm{SU}(2){\times}\mathrm{U}(1)$.

The 19 constants derived here agree with measurement to 0.0006%–2.6%; with the 7 derived in Paper II, the 26 physical constants are reproduced with no adjustable parameters. They include $1/\alpha = 137.0368$ (0.0006%), $\alpha_s(M_Z) = 0.1179$ (0.07%), $\sin^2\!\theta_W = 3/13 = 0.23077$ (0.23122 at $M_Z$ with the next correction, <0.01%), the charged-lepton mass ratio $R = \ln(m_\tau/m_e)/\ln(m_\mu/m_e) = 1.5293$ (0.006%), and $\sin\theta_C = 0.2245$ (0.10%; 0.22435 after screening). Setting the absolute scale with the electron mass $m_e$, we predict the absolute neutrino masses without oscillation data ($\Sigma m_\nu = 59.37$ meV). Neutrinoless double beta decay is predicted to vanish exactly. All values are reproducible with the accompanying verification code.

### Full text

The complete paper is included here as Markdown in both languages, so it can be
read in place:

| Language | Full text | Built from the manuscript sealed for v4.2.0 (SHA-256) |
| --- | --- | --- |
| English | [Physics from Existence I: The Equation](physics_from_existence.md) | `84a499b127a06402533742514f760445a36b2f92b4f81cc0cce0012edf4962d8` |
| 日本語 | [存在からの物理学 I: The Equation](../i18n/ja/01-papers/physics_from_existence.md) | `2562ed92ad61d3ab62fef9060e3a367a246e293c8c88483f36ad320c71d6a525` |

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

> Kondo, H. (2026). *Physics from Existence I: The Equation* (v4.2.0). Zenodo. https://doi.org/10.5281/zenodo.22883521

To cite the work independently of version, use the concept DOI, which always resolves to the latest version: https://doi.org/10.5281/zenodo.19451887

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

## Paper II — Physics from Existence II: The Proof

In preparation. Several quantities shown in Paper I's tables are derived in Paper II; those rows are marked "II" in [Results](../03-results/README.md) and appear in Paper I with that attribution.
