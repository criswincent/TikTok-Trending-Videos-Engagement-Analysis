# TikTok Trending Videos: Engagement Analysis
Which video attributes go with higher engagement among 1,000 trending TikTok videos?

**Tools:** Python (pandas, SciPy, seaborn), Excel, Tableau
**Dashboard:** [Tableau Public link]
**Data:** Kaggle "TikTok Trending Videos" (1,000 videos, scraped Dec 2020). Raw data not included.

## Key findings
- 30s+ videos: median engagement 10.9% vs 8.2% for videos under 15s (non-overlapping 95% bootstrap CIs)
- Verified creators: 11.7% vs 8.7% (only 56 verified videos)
- Top 10% of videos hold 88.3% of all views (Gini = 0.90)
- No clear difference by weekday

## Method
Cleaning log, engineered features, bootstrap CIs, Kruskal-Wallis / Mann-Whitney U with FDR correction.

## Limitations
Small sample, late-2020 snapshot, trending-only videos (no baseline), descriptive not causal.
