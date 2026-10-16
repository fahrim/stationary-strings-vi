# Duran Sicimler Teoremi VI — Yayın Paketi

**Stationary Strings Theorem VI: Dirac–Majorana Chiral Peeling in Navier–Stokes Vortex Blowup, the Λ_Meral Baryogenesis Constant, and CERN ALPHA / 511 keV Observational Synthesis**

Yazar: Fahri Meral · Tarih: 16 Ekim 2026 · Sürüm: v1 (Makale VI)

## İçerik

| Dosya | Açıklama |
|---|---|
| `paper/duran_sicimler_teoremi_VI.tex` | Türkçe ana makale (Teorem 1, Tablo 1–3, fig7–fig8) |
| `paper/duran_sicimler_teoremi_VI_EN.tex` | İngilizce sürüm |
| `figs/fig7_dirac_majorana_and_meral_constant.pdf` | T13/T14 figürü |
| `figs/fig8_alpha_breit_rabi_and_511keV_fuel.pdf` | T15 figürü |
| `CITATION.cff` | Atıf kaydı |
| `LICENSE` | MIT |

## Sayısal yeniden-üretim

T13–T15 sayısal doğrulama, **V deposundaki** çözücüyle üretilir
([`stationary-strings-v`](https://github.com/fahrim/stationary-strings-v), etiket `v3`, commit `b3443e7`):

```bash
git clone https://github.com/fahrim/stationary-strings-v
cd stationary-strings-v && git checkout v3
pip install numpy scipy matplotlib
python duran_sicimler_sim/solver_engine.py   # T1–T15 (15/15 PASS)
```

`figs/` dizinindeki fig7–fig8 PDF'leri bu testlerin arşivlenmiş figürleridir
(İngilizce etiketli sürümler hazırlanmaktadır).

## Ana bulgular

- T13: kiral soyulma (Rabi `7.2e-15`, flip `0.64`, Majorana farkı `1649.08`).
- T14: `Λ_Meral^(0) = 0.07226943267767906` (kapalı form, fark `0.0`),
  `ε_CP* = 3.04422478604457e-11`.
- T15: ALPHA-g lab `1.0` tam (`1.21σ` marjinal uyum), Breit–Rabi farkı `~1e-9` kHz,
  Gauss norm `5.6e-16`, Ore–Powell `∫_0` ıraksaklığı belgeli (düzenli: `2343.47/228.08`).

## Lisans

MIT — bkz. `LICENSE`. İçerik hakem denetiminden geçmemiştir.
