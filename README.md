# CodeAlpha_DataVisualization

Data Visualization project on the **Gapminder dataset**, completed as **Task 3** of the **CodeAlpha Data Analytics Internship**.

## Objective
To turn raw data into clear visuals that tell a story: *Can money buy a longer life, and how did the world change between 1952 and 2007?*

## Dataset
- **Source:** [Gapminder](https://raw.githubusercontent.com/plotly/datasets/master/gapminder_with_codes.csv)
- **Size:** 1,704 rows, 142 countries, 5 continents, 1952 to 2007 (every 5 years)
- **Columns:** `country`, `continent`, `year`, `lifeExp`, `pop`, `gdpPercap`
- **Data quality:** no missing values

## Questions Answered
1. How has life expectancy changed from 1952 to 2007?
2. Does higher income mean a longer life?
3. Which continents lead and which lag behind?
4. How did population change across continents?

## Visualizations
| # | Chart | Purpose |
|---|-------|---------|
| 1 | Line chart | World life expectancy over time |
| 2 | Scatter plot (bubble) | Income vs life expectancy, bubble size = population |
| 3 | Bar chart | Average life expectancy by continent (2007) |
| 4 | Box plot | Spread of life expectancy inside each continent |
| 5 | Horizontal bar chart | Top 10 richest countries by GDP per capita |
| 6 | Line chart | Population growth by continent |
| 7 | Heatmap | Correlation between life expectancy, population and GDP |

## Key Insights
- World average life expectancy rose from about **49 years (1952) to 67 years (2007)**, a gain of roughly 18 years.
- Richer countries tend to live longer, but the benefit **flattens at high incomes**.
- **Oceania (about 81 years)** and **Europe (about 78 years)** lead; **Africa (about 55 years)** is lowest.
- Africa also shows a **wide spread** between countries; Asia ranges from about 44 (Afghanistan) to 83 (Japan).
- **Norway, Kuwait and Singapore** had the highest income per person in 2007.
- **Asia's population grew the most**, from 1.4 to 3.8 billion.
- GDP per capita and life expectancy are **strongly correlated (0.68)**; population has almost no link with either.

## Tools Used
Python, Pandas, Matplotlib, Seaborn, Google Colab

## How to Run
1. Open `CodeAlpha_DataVisualization.ipynb` in [Google Colab](https://colab.research.google.com/)
2. Click **Runtime → Run all**
3. The dataset loads directly from the URL, so no download is needed

## Repository Structure
```
CodeAlpha_DataVisualization/
├── CodeAlpha_DataVisualization.ipynb   # complete analysis and charts
└── README.md
```

## Author
**Shiwam Pandey**
BSc Statistics (Hons), 2nd Year, MD University, Rohtak
Data Analytics Intern, [CodeAlpha](https://www.codealpha.tech)
