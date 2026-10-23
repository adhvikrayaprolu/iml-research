# Illinois Mathematics Lab Research: Sports Statistics

Undergraduate research with the Illinois Mathematics Lab (IML) at the University of Illinois Urbana-Champaign, advised by Prof. A.J. Hildebrand. August 2025 to present.

> This repository is a public overview of my work. The current project's team repository is private while the research is in progress.

## Fall 2026: How reliable are live win probabilities?

Sports broadcasts show live win probabilities throughout a game. We are testing how well ESPN's forecasts are calibrated: when ESPN gives a team a 70% chance, does that team win about 70% of the time?

- Measuring calibration and accuracy across the stages of a game, including late-game situations and overtime.
- Comparing ESPN's forecasts with simpler regression models built from score difference and time remaining.
- Working with NBA data from the 2017-18 through 2024-25 seasons and MLB data from 2018 to 2025, with NFL data in progress.

**My contributions**

- Built the MLB data pipeline, which indexed 17,905 games and matched 1.17 million win-probability observations to plays. It reports real data coverage separately from missing data and failed requests, so gaps are never mistaken for results.
- Organized the team repository by sport and stage (data, analysis, models), split large datasets into per-season files, and wrote the data guide.
- Merged teammates' NBA evaluation and modeling work into the shared structure.

## Fall 2025: Skill versus luck in sports leagues

How much of a league's final table comes from skill, and how much could luck alone produce? We tested 25 seasons of results from the top four European soccer leagues (32,000+ matches) against pure-skill and pure-luck simulations calibrated for home advantage.

- Compared competitive balance across leagues using upset frequency, Spearman rank correlation, and win-percentage dispersion.
- Built the data pipelines that clean, standardize, and merge the match data into analysis-ready datasets.
- Presented the findings to the UIUC Mathematics Department.

Code and data: [iml_skillvsluck](https://github.com/adhvikrayaprolu/iml_skillvsluck)

## Stack

Python · pandas · NumPy · SciPy · scikit-learn · Matplotlib · Jupyter

---

[Profile](https://github.com/adhvikrayaprolu) · [LinkedIn](https://www.linkedin.com/in/adhvikrayaprolu)
