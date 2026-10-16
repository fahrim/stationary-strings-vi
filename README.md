# Stationary Strings Theorem VI — Publication Package

> **Türkçe:** [README_TR.md](./README_TR.md)

**Stationary Strings Theorem VI: Dirac–Majorana Chiral Peeling in Navier–Stokes Vortex Blowup, the Meral Baryogenesis Constant, and CERN ALPHA / 511 keV Observational Synthesis**

Author: Fahri Meral · Date: October 16, 2026 · Version: v1 (Paper VI)

> **Status:** Unpublished preprint (v1). Not peer-reviewed.

## Contents

| File | Description |
|---|---|
| `paper/duran_sicimler_teoremi_VI.tex` | Main paper, Turkish (Theorem 1, Tables 1–3, fig7–fig8) |
| `paper/duran_sicimler_teoremi_VI_EN.tex` | English version |
| `figs/fig7_dirac_majorana_and_meral_constant.pdf` | Test T13/T14 figure (TR) |
| `figs/fig7_dirac_majorana_and_meral_constant.png` | Test T13/T14 figure preview (TR) |
| `figs/fig7_dirac_majorana_and_meral_constant_en.pdf` | Test T13/T14 figure (EN) |
| `figs/fig7_dirac_majorana_and_meral_constant_en.png` | Test T13/T14 figure preview (EN) |
| `figs/fig8_alpha_breit_rabi_and_511keV_fuel.pdf` | Test T15 figure (TR) |
| `figs/fig8_alpha_breit_rabi_and_511keV_fuel.png` | Test T15 figure preview (TR) |
| `figs/fig8_alpha_breit_rabi_and_511keV_fuel_en.pdf` | Test T15 figure (EN) |
| `figs/fig8_alpha_breit_rabi_and_511keV_fuel_en.png` | Test T15 figure preview (EN) |
| `CITATION.cff` | Citation record |
| `LICENSE` | MIT |

## Numerical reproduction

Tests T13–T15 are produced with the solver in the **Paper V repository**
([`stationary-strings-v`](https://github.com/fahrim/stationary-strings-v), tag `v3`, commit `b3443e7`):

```bash
git clone https://github.com/fahrim/stationary-strings-v
cd stationary-strings-v && git checkout v3
pip install numpy scipy matplotlib
python duran_sicimler_sim/solver_engine.py   # T1–T15 (15/15 PASS)
```

The `figs/` PDFs are the archived figures of these tests (English-labelled versions in preparation).

## Key findings

- T13: chiral peeling (Rabi `7.2e-15`, flip `0.64`, Majorana difference `1649.08`).
- T14: `Λ_Meral^(0) = 0.07226943267767906` (closed form, difference `0.0`),
  `ε_CP* = 3.04422478604457e-11`.
- T15: ALPHA-g lab `1.0` exact (`1.21σ` marginal agreement), Breit–Rabi difference `~1e-9` kHz,
  Gauss norm `5.6e-16`, Ore–Powell `∫_0` divergence documented (regulated: `2343.47/228.08`).

## License

MIT — see `LICENSE`. Content is not peer-reviewed.
