# Why Does Klement's Model Like the Netherlands?

**Data: FIFA Technical Study Group, 2026 FIFA World Cup | Framework: Joachim Klement's Macro Forecasting Model**

Joachim Klement's macro forecasting model identified the winners of the last three FIFA World Cups — Germany in 2014, France in 2018 and Argentina in 2022. The model is built almost entirely on macro-level factors such as FIFA ranking, population, GDP, historical football performance and structural football development indicators. Ahead of the 2026 World Cup, it rates the Netherlands among the tournament favourites — and correctly predicted their exact Round of 32 matchup against Morocco.

This project does not attempt to validate or challenge Klement's model directly. Macro factors such as population and GDP cannot be observed on a football pitch. But if a model built on these variables consistently identifies genuine contenders, there may be tactical and structural characteristics that help explain why.

---

## Published Article

📄 [Why Does Klement's Model Like the Netherlands? (Medium)](https://medium.com/@ioanniskastritis4/why-does-klements-model-like-the-netherlands-ac4987f41153)

---

## Key Findings

- **More Pressure, Same Progression** — Frenkie de Jong's reception rate fell from 72.4% (vs Japan) to 33.3% (vs Tunisia) as opponents increasingly restricted him, but his pass and line-break completion stayed consistently elite (87–100%) whenever he did receive the ball
- **The Right Side Never Changes** — Denzel Dumfries provided a stable structural outlet regardless of personnel, while adapting the way he attacked space according to the opponent. His total offers, reception rate and sprint output all increased across the group stage, reaching a 60% reception rate against Tunisia
- **Fast Recoveries, Sustained Control** — The Netherlands recovered the ball faster than every group-stage opponent they faced. Recovery time tracked in perfect rank order with final-third presence and possession share across all three matches — though not with expected goals, suggesting recovery speed functions as territorial control rather than a direct route to transition chances

---

## Methodology

The analysis uses official **FIFA Technical Study Group Post Match Summary Reports**, published for every match of the 2026 World Cup. These reports contain tracking-derived metrics — including offer-to-receive movement classifications, pass and line-break completion, physical performance data, and ball recovery time — calculated by FIFA from broadcast and stadium tracking systems, though raw positional (X,Y) data is not publicly available.

Three Netherlands group-stage matches were analysed in full:

| Match | Result | Date |
|---|---|---|
| Netherlands vs Japan | 2–2 | 14 June 2026 |
| Netherlands vs Sweden | 5–1 | 20 June 2026 |
| Tunisia vs Netherlands | 1–3 | 27 June 2026 |

Tactical patterns identified in the data were cross-checked against direct video analysis of all three matches. Where possible, multiple sources of evidence — video analysis, tracking-derived metrics and physical performance data — were combined to strengthen the interpretation of tactical behaviours. Where the FIFA dataset could not confirm a specific phase or movement (for example, the exact origin of a cross), this is stated explicitly in the article and in this repository.

A comparison against Morocco's own group-stage ball recovery data (vs Brazil, Scotland and Haiti) is included to provide forward-looking context ahead of the Netherlands' Round of 32 meeting with Morocco, without claiming predictive value.

---

## Repository Structure

```
├── Netherlands_Klement_Data.xlsx   # Full dataset across all 6 matches analysed
├── README.md                        # Project documentation
└── visuals/                         # All project charts
    ├── dejong_line_chart.png
    ├── dejong_dumbbell.png
    ├── dumfries_rotation_diagram.png
    ├── dumfries_reception_rise.png
    ├── dumfries_movement_shift_v2.png
    ├── recovery_control_scatter.png
    └── morocco_comparison.png
```

---

## Data File

`Netherlands_Klement_Data.xlsx` contains five sheets:

1. **Match Overview** — results, possession and recovery time across all three Netherlands group games plus Morocco's three group games
2. **De Jong** — offer, reception, pass and line-break completion data
3. **Dumfries** — full movement-type breakdown (underlap / overlap / far-post), physical performance, and top passing connection
4. **Recovery & Control** — recovery time, final-third receptions, possession and xG by match, plus the Netherlands vs Morocco recovery time range comparison
5. **Goals** — all ten Netherlands group-stage goals with build-up type

---

## Limitations

- The analysis is based on a three-match group-stage sample
- The FIFA dataset provides derived tracking metrics, not raw positional (X,Y) data — phase-specific or location-specific claims (such as the exact origin of a particular cross) are evidenced through video analysis rather than the dataset alone
- The Morocco comparison is descriptive, not causal, and does not account for differences in opponent quality between the two teams' respective group-stage fixtures
- Findings describe repeatable patterns observed across three matches, not predictive indicators of future match outcomes

---

## References

Bauer, P., & Anzer, G. (2021). Data-driven detection of counterpressing in professional football: A supervised machine learning task based on synchronized positional and event data with expert-based feature extraction. *Data Mining and Knowledge Discovery, 35*(5), 2009–2049.

FIFA Technical Study Group. Post Match Summary Reports, 2026 FIFA World Cup. Accessed June 2026.

Klement, J. (2026). FIFA World Cup Predictions 2026. *Klement on Investing* / Panmure Liberum.

---

## Author

**Yiannis Kastritis**
Football Data Analyst | MSc Football Data Analytics (UCAM Murcia / Sports Data Campus)

🌐 [yiannis4.github.io](https://yiannis4.github.io) · 💼 [LinkedIn](https://www.linkedin.com/in/yiannis-kastritis-a417bb122)

---

*Framework inspired by Joachim Klement's FIFA World Cup forecasting model.*
