# Data Visualization

Data visualization demonstration with **Seaborn** and **Matplotlib**, applied to eight real-world datasets.


## Ountline

| Section | Plot types | Dataset |
|---|---|---|
| 1. Trends over time | Line charts | FIFA rankings, Spotify streams, LA museum visitors |
| 2. Comparing categories | Bar charts, heatmaps | US flight delays, IGN game scores |
| 3. Relationships | Scatter, regression, swarm plots | Medical insurance, candy rankings |
| 4. Distributions | Histograms, KDE, joint plots | Iris, breast cancer diagnostics |
| 5. Styling | Seaborn themes | Spotify streams |
| 6. Amazon Data | Data cleaning, histogram, scatter, bar chart | Amazon product listings |

### Choosing the right plot

| Goal | Best-suited plot |
|---|---|
| Trend over time | `sns.lineplot` |
| Compare categories | `sns.barplot` |
| Compare two categorical dimensions | `sns.heatmap` |
| Relationship between two numeric variables | `sns.scatterplot`, `sns.regplot`, `sns.lmplot` |
| Numeric values across categories | `sns.swarmplot` |
| Shape of a distribution | `sns.histplot`, `sns.kdeplot`, `sns.jointplot` |


## Repository Structure

```
.
├── ssc_visualization.ipynb
├── README.md
└── Data_105/

```

## Getting Started

**1. Clone the repository**

```bash
git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>
```

**2. Install dependencies**

```bash
pip install requirements
```


**3. Launch the notebook**

```bash
jupyter notebook scc_visualization.ipynb
```

Then choose **Run All** to render every chart.

### Requirements

```
pandas
matplotlib
seaborn>=0.12
jupyter
```

## Data Sources
Make sure the folder (Data_105) in the path and contains all the datasets used for this demonstration.

| File | Description |
|---|---|
| `fifa.csv` | FIFA world rankings of six national teams |
| `spotify.csv` | Daily global streams of five popular songs, 2017-2018 |
| `museum_visitors.csv` | Monthly visitors to four Los Angeles museums |
| `flight_delays.csv` | Average arrival delay per airline and month |
| `ign_scores.csv` | Average IGN review score by platform and genre |
| `insurance.csv` | Medical insurance charges with demographic data |
| `candy.csv` | Head-to-head candy popularity rankings |
| `iris.csv` | Classic iris flower measurements |
| `cancer.csv` | Breast tumour diagnostic measurements |
| `amazon.csv` | Amazon product listings with prices, discounts and ratings |

The datasets come from the Kaggle Learn *Data Visualization* course, and the Amazon dataset is a public product dataset on Kaggle.


#
