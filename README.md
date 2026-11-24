Global CO₂ Emissions: EDA & Visualization

Two notebooks analyzing global CO₂ emissions (1965–2022) using the Our World in Data CO₂ dataset.

Notebook	What it does
task_2_-_EDA.ipynb	Cleaning, data quality checks, trends, outliers, and hypothesis tests
task_3_-_Data_Visualization.ipynb	Static and interactive charts, a dashboard, and key insights
Key Findings
World CO₂ rose about 230% from 1965 to 2022 (~11,400 → ~37,500 Mt).
Top emitters in 2022: China, the US, and India. Qatar leads per person (35.8 t).
GDP and total CO₂ are strongly correlated (Spearman ρ = 0.948).
Wealthier countries emit about 6x more per person (8.03 vs 1.28 t, p < 0.001).
2020 emissions fell 5.3% (COVID-19), and 70.5% of countries saw a drop.
Coal is now the largest source, overtaking oil in the early 2000s.
Charts

Line, multi-line, bar, scatter, histogram, heatmap, stacked area, donut, world map, animated scatter, and a dashboard. Saved to charts/.

Run It
bash
pip install pandas numpy matplotlib seaborn scipy plotly jupyter
jupyter notebook

Run the EDA notebook first. Data is downloaded from the OWID URL, so internet access is needed.

Limitations
Many GDP and gas values are missing (GDP tests cover 164 countries).
Tests use 2019 and 2020 snapshots only.
Correlation does not imply causation.
Credit

Data: Our World in Data / Global Carbon Project.
