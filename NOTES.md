<!-- update 7274 -->

## Visualization Notes — April 21, 2026

Added annotations to the bubble chart to call out the 'sweet spot' genres — those with high opportunity scores and low saturation. The visual now clearly shows the Puzzle/Roguelike cluster as the most attractive space for indie developers with limited budgets.

Considering adding a second chart that shows the same data filtered by budget tier to make the recommendations more actionable.

## Opportunity Score Methodology
Revised formula: Opportunity Score = (Median Revenue / Dev Cost Estimate) × Success Rate × (1 / Saturation Index). Puzzle and narrative genres score highest for $10k-$50k budget tier.

## Genre Clustering Analysis — April 25, 2026

Applied k-means clustering (k=5) to the genre dataset using revenue metrics and dev cost estimates. Clusters emerged naturally:
1. **High-risk/High-reward**: Action RPG, Open World, Survival — high median revenue but high dev costs and variance
2. **Sweet spot**: Puzzle, Roguelike, Narrative — strong ROI for $10k-$50k budgets
3. **Saturated/Low margin**: Platformer, Endless Runner — oversupply has compressed margins
4. **Niche premium**: Simulation, Strategy — lower volume but loyal audiences with high LTV
5. **Emerging**: Auto-battler, Deck-builder — growing market, early mover advantage still available

---

### Update: April 26, 2026

## Genre Opportunity Scoring — Methodology Notes

The Opportunity Score combines market size (total revenue), competition density (# of titles), and growth trajectory (YoY revenue change). Genres with high revenue but low title count represent the best entry points for indie developers.

### Scoring Formula
Opportunity = (Revenue_Percentile * 0.4) + (Inverse_Competition_Percentile * 0.35) + (Growth_Percentile * 0.25)

### Caveats
- Revenue data aggregated from public SteamSpy estimates
- Does not account for marketing budget differences
- Seasonal genres (horror, holiday) may be undervalued by annual aggregation

## 2026-04-27 11:42
Noted that Platformer genre has highest game count but median revenue has declined 40% since 2019 — saturation is measurable in the data.

## Success Rate Finding — April 28, 2026
Only 18% of indie games on Steam earn more than $25k lifetime. However, in the top 5 Opportunity Score genres, this rate rises to 34%. Genre selection is the single biggest lever for indie success.
