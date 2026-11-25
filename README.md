# FinTech Adoption and Islamic Bank Performance in ASEAN: Mediation and Moderation Effects

![Conference: ICMWEB 2026](https://img.shields.io/badge/Conference-ICMWEB%202026-blue) ![Status: Under review at MBER](https://img.shields.io/badge/Status-Under%20review%20at%20MBER-yellow) ![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey)

Conference presentation slides for a panel-data study of how FinTech adoption relates
to Islamic-bank profitability in ASEAN, with financial inclusion as a mediator and
regulatory quality as a moderator.

## About

Islamic banking operates across very different levels of financial-sector maturity,
digitalisation and regulation in Malaysia, Indonesia, Brunei and Thailand. Existing
work usually studies FinTech, financial inclusion and bank performance separately.
This study combines all three — and tests regulatory quality as a moderator rather
than a control — for Islamic banks in ASEAN.

## Research question

How do mobile banking penetration, FinTech investment and digital payment volume
relate to Islamic-bank return on assets (ROA), through financial inclusion and
under different regulatory quality?

## Method

- **Design:** quantitative, explanatory panel-data research
- **Sample:** 11 full-fledged Islamic banks / Islamic financial institutions across
  Malaysia, Indonesia, Brunei and Thailand; 121 bank-year observations, 2014–2024
- **Dependent variable:** ROA (net income / total assets). Mean ROA 0.751%
  (SD 1.213; range −8.70% to 4.08%)
- **FinTech indicators (country-year):** mobile banking penetration, FinTech
  investment, digital payment volume — sourced from IMF FAS, national central banks,
  KPMG Pulse of Fintech, CB Insights, BIS and related ASEAN reports
- **Mediator:** financial inclusion index. **Moderator:** regulatory quality
- **Controls:** bank size, CAR, NPF ratio, liquidity, GDP growth, inflation
- **Estimation:** Random Effects GLS (Hausman χ²(18) = 19.73, p = 0.348 → RE
  preferred); Baron–Kenny causal-steps mediation; FinTech × regulatory quality
  interactions; year fixed effects

## Key findings

- **Direct effects:** only digital payment volume has a significant positive direct
  effect on ROA (β = 5.75e−06, p = 0.039 — a USD 100 million increase in
  digital-payment value is associated with about a 0.058 percentage-point increase
  in ROA). Mobile banking penetration (p = 0.173) and FinTech investment
  (p = 0.489) are not significant.
- **Mediation:** financial inclusion does **not** mediate the FinTech–ROA
  relationship — it does not significantly predict ROA (β = −0.0004, p = 0.956).
  Mobile banking raises inclusion (β = 0.8419, p = 0.021) while FinTech investment
  reduces it — a "reach without return" pattern.
- **Moderation:** regulatory quality **negatively** moderates all three FinTech–ROA
  relationships (mobile × regqual β = −0.0151, p = 0.019; FinTech investment ×
  regqual β = −0.0031, p = 0.021; digital payment × regqual β = −0.0000157,
  p = 0.003). As regulatory quality rises, the profitability slope of
  digitalisation weakens and can reverse — a compliance-burden effect.
- **Controls:** the NPF ratio has a strong negative effect on ROA (β = −0.1376,
  p = 0.001).

In short: FinTech improves Islamic-bank performance selectively — digital payments
are the clearest revenue-linked channel — and the regulatory environment determines
how much of the benefit reaches profitability.

**Limitations:** small population (11 institutions / 121 bank-years); several
FinTech, inclusion and regulatory measures are country-year rather than bank-level;
Baron–Kenny mediation is conservative (no bootstrap).

## Authors

- **Abul Hosen** — Bachelor of Finance (Islamic Finance), School of Business and
  Social Sciences, Albukhary International University, Alor Setar, Kedah, Malaysia
- **Mohamed Inshaf Mohamed Faleel** — Albukhary International University, Malaysia

## Status and presentation

- **Under review** at *The Muslim Business and Economic Review (MBER)*.
- **Presented at ICMWEB 2026** — 5th International Conference on Muslim World
  Economy and Business.

## Contents

- `FinTech-Adoption-Islamic-Bank-Performance-ASEAN.pptx` — conference presentation
  slides (14 slides)
- `README.md` — this file
- `CITATION.cff` — citation metadata (GitHub "Cite this repository")
- `LICENSE` — Creative Commons Attribution 4.0 International (CC BY 4.0)

## How to cite

> Hosen, A., & Faleel, M. I. M. (2026). *FinTech Adoption and Islamic Bank
> Performance in ASEAN: Mediation and Moderation Effects.* Presented at the 5th
> International Conference on Muslim World Economy and Business (ICMWEB 2026).
> Under review at *The Muslim Business and Economic Review*.

## Contact

Abul Hosen — abul.hosen@student.aiu.edu.my ·
[LinkedIn](https://www.linkedin.com/in/abulhosen)

## License

This work is licensed under a [Creative Commons Attribution 4.0 International
License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). See `LICENSE`.
