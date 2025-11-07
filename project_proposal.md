Project Proposal
================

## Group Members

**Wang, Yishi**: <yw4665@cumc.columbia.edu>

**Zhou, Yiquan**: <yz5227@cumc.columbia.edu>

**Mao, Yutong**: <ym3139@cumc.columbia.edu>

**Wu, Tao**: <tw3108@cumc.columbia.edu>

## Project Title

**Time Spending on Games**

## Motivation

As passionate gamers, we aim to uncover why some Steam titles accumulate
far more play hours than others. Many factors, including playtime,
genre, pricing, and reviews have an impact on play hours, and we want to
identify which features predict sustained engagement.

## Data

We currently have one primary data source from Kaggle
(<https://www.kaggle.com/datasets/fronkongames/steam-games-dataset/data>).

## Product

Interactive dashboard showing top predictors of playtime, filters
(genre, price, multiplayer), and game-by-game detail. With a final
report and slide deck summarizing methods, key findings, and
developer/player recommendations.

## Planned Analys

**Exploratory data analysis**: distributions of median playtime (forever
vs. 2-week), genre/price breakdowns

**Visuals**: violin/box plots, stacked bar charts, and release-year
timelines.

**Modeling**: baseline linear regression and regularized models,
tree-based models (Random Forest / XGBoost) for feature importance.

## Compressed Timeline

### Week 1 — Nov 7–13: Setup

Kickoff, assign roles, create GitHub repo & project board

Pull Kaggle dataset, run validation

### Week 2 — Nov 14–20: Cleaning & feature engineering

Clean/normalize release dates, price, genres/tags

Create engineered features: monetization, multiplayer flag, vote ratios,
release-era. (Data wrangler / ML lead)

Draft Data Sources page content and data dictionary.

### Week 3 — Nov 21–27: Modeling baseline & EDA polish

Baseline models (log-linear, simple tree), cross-val, metrics
(RMSE/AUC). (ML lead)

Interpretability: feature importances, 1–2 SHAP plots.

Finish EDA page visuals and add short captions for site.

### Week 4 — Nov 28–Dec 4: Final models, dashboard prototype

Assemble Project Report draft and slides.

Final polish & submission

Submit by Dec 6 (PM ensures upload & README submission).
