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
