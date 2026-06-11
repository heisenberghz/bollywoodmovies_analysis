# Bollywood Movie Analysis (2013–2015)

Exploratory data analysis of 149 Bollywood movies examining budgets, box office collections, YouTube engagement, and release patterns.

## Dataset

`bollywood.csv` contains 149 movies with 10 columns:

| Column | Description |
|---|---|
| `SlNo` | Serial number |
| `Release Date` | Release date (2013–2015) |
| `MovieName` | Movie title |
| `ReleaseTime` | Release timing category (Normal, Festive Season, Holiday Season, Long Weekend) |
| `Genre` | Movie genre |
| `Budget` | Budget in crores of rupees |
| `BoxOfficeCollection` | Box office revenue in crores |
| `YoutubeViews` / `YoutubeLikes` / `YoutubeDislikes` | YouTube trailer engagement |

## Analysis

The Jupyter notebook performs 15 analyses including:
- Release timing and genre trends
- ROI calculation and flop identification
- Correlation between box office and YouTube engagement
- Data visualizations (boxplots, heatmaps, barplots, KDE plots)

### Key Findings

- **2014** had the most releases (70), followed by 2013 (67), then 2015 (12)
- **Correlation** between BoxOfficeCollection and YoutubeLikes is **0.68** (moderately strong positive)
- **Long Weekend** releases have the highest average ROI (1.127); **Normal** releases have the lowest (0.658)
- **February** sees the most high-budget movie releases

## Setup

```bash
pip install numpy pandas matplotlib seaborn
```

Open `bollywoodmovies_analysis.ipynb` in Jupyter Notebook, VS Code, or Google Colab.
