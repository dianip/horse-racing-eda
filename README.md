# Horse Racing EDA

This project performs exploratory data analysis (EDA) on a horse racing dataset to uncover trends in trainer performance, horse age, colour distribution, race pricing, and data quality.

---

## Project Structure

- `horse-racing-eda.ipynb`: Main notebook containing all analysis steps.
- `data/Horses.csv`: Dataset used for exploration.

---

## 🧰 Tools & Libraries

- Python (Jupyter Notebook, run via PyCharm)
- pandas, numpy
- matplotlib, seaborn

---

## What’s Inside

The notebook includes:

- **Data Cleaning**: Handles missing values, placeholders, and converts object-type price fields to numeric.
- **EDA**:
  - Outlier detection on race prices (`StartingPrice`, `ForecastPrice`)
  - Trainer participation and win rate analysis
  - Horse age and colour distribution
  - Missing data visualisations
- **Visuals**:
  - Histograms, bar charts, boxplots, and countplots to explain trends
- **Insights**:
  - Trainer 1079218 has the highest win rate despite lower horse volume
  - Majority of horses are aged 3–5
  - Horse colour ‘b’ is dominant — possibly due to breeding or preference

---

## Future Ideas

- Investigate links between horse colour and performance
- Explore jockey success rates and age-performance patterns
- Analyse external race-day factors influencing price variability
