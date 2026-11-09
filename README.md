# ml-course

My work for the Machine Learning course.

## Assignment 1 — Bestselling Books (EDA)

Exploratory analysis of Amazon's yearly Top-50 bestsellers (2009–2022, 700 rows) —
what do bestsellers have in common?

**Notebook:** [`assignment1/bestsellers_eda.ipynb`](assignment1/bestsellers_eda.ipynb)
**Report:** [`assignment1/report.pdf`](assignment1/report.pdf)
**Data:** [`assignment1/data/bestsellers.csv`](assignment1/data/bestsellers.csv)

What's inside:
- data inspection and cleaning (duplicate titles across years, `Price = 0`, hidden spaces)
- filtering, grouping by genre / year, top authors
- new features: `reviews_per_year`, `price_category`, `is_blockbuster`
- plots: distributions, boxplots, scatter, trends over time, correlation heatmap

Main findings:
- almost all bestsellers are rated 4.5–4.9 — the number of reviews says much more
- ratings go up over the years (rating inflation)
- Non Fiction is slightly more expensive than Fiction
- blockbusters come from many different authors; many are cheap kids' books from 2020

Tools: pandas, NumPy, matplotlib, seaborn.
