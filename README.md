# Indie Game Genre Profitability Analysis

**Which game genre should you build if you want to actually make money?**

This analysis examines real Steam revenue data across 60 genre tags and 100,000+ games to identify which genres offer the best return on investment for indie developers — broken down by budget tier.

## Key Results
- **Farming Sim** has the highest Opportunity Score (97.3) — $4,200 median revenue, $120K typical dev cost
- **73% of Action games** earn less than $5,000 despite the genre having $43B in total market revenue
- **The average lies**: Action averages $820K/game but the *median* is $570 — inflated by blockbusters
- **Best $10K budget genre:** Visual Novel or Deck Building — highest median relative to dev cost
- **Best genre combination:** Farming Sim + Relaxing (Stardew Valley model) or Roguelite + Difficult (Hades model)

## Research Questions
1. Which genres have the highest median revenue (what the *typical* game earns)?
2. What percentage of games in each genre actually turn a profit?
3. How does development cost affect ROI by genre?
4. Which genre combinations offer the best risk-adjusted returns?
5. What should a developer with $10K, $50K, or $200K build?

## Tech Stack
| Tool | Purpose |
|---|---|
| Python 3.11 | Core analysis |
| pandas | Data manipulation |
| matplotlib | Visualizations |
| numpy | Statistical calculations |

## Project Structure
```
indie-game-genre-analysis/
├── data/
│   └── steam_genres.csv           # 60 genres with revenue, success rates, dev costs
├── notebooks/
│   └── indie_game_genre_analysis.ipynb  # Full analysis notebook
├── images/
│   ├── 01_revenue_landscape.png
│   ├── 02_risk_matrix.png
│   ├── 03_opportunity_score.png
│   ├── 04_budget_tier_analysis.png
│   ├── 05_saturation_vs_revenue.png
│   └── 06_genre_combinations.png
├── output/
│   ├── genre_analysis_full.csv
│   └── top_genres_by_opportunity.csv
└── README.md
```

## How to Run
```bash
git clone https://github.com/Clivesay1/indie-game-genre-analysis
cd indie-game-genre-analysis
pip install pandas matplotlib numpy
jupyter notebook notebooks/indie_game_genre_analysis.ipynb
```

## Budget-Based Recommendations

| Budget | Best Genre | Median Revenue | Dev Cost | Why |
|---|---|---|---|---|
| $10K (Solo) | Deck Building | $2,200 | $45K | Engaged niche, low art requirements |
| $50K (Small Team) | Farming Sim | $4,200 | $120K | Dedicated community, high engagement |
| $200K (Mid Indie) | City Builder | $3,500 | $200K | Growing market, low saturation |
| $500K+ (Funded) | Co-op | $2,700 | $450K | High ceiling, viral potential |

## Data Source
Revenue data from [games-stats.com](https://games-stats.com/steam/tags/) — aggregated from Steam API and SteamSpy across 100,000+ games.

---
*Author: Chris Livesay | [LinkedIn](https://www.linkedin.com/in/christopher-livesay)*
<!-- revision 3366 -->
<!-- update 8670 -->

