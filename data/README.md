# Data Notes

## Included Snapshot

`steam_genres.csv` is the committed data snapshot used by the consolidated analysis notebook. It contains **63 genre records** (plus the header row). The project notebook describes the dataset as Steam tag revenue statistics from games-stats.com, covering 60 genre tags and 100,000+ games, collected in **April 2026**.

Revenue metrics are aggregate estimates. They should be read alongside the notebook's median-revenue, success-rate, and sample-size analysis rather than as a forecast for an individual game.

## Reproducing the Analysis

1. Create a virtual environment and install the packages in the repository root with `pip install -r requirements.txt`.
2. Launch `jupyter notebook notebooks/indie_game_genre_analysis.ipynb` from the repository root.
3. Run cells in order. The notebook reads the committed CSV snapshot and writes derived tables to `output/`.

## Source and Access Note

The project source is [games-stats.com Steam Tags](https://games-stats.com/steam/tags/). Access to third-party aggregation sites can vary by browser, location, or automated-request policy. The committed CSV is therefore the reproducible input for this version of the analysis. Future refreshes should record the retrieval date, source methodology, and any schema changes before replacing it.
