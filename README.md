# Electricity Production Analysis: Global vs. Scandinavia (2000–2020)

This project explores trends in electricity production worldwide and in Scandinavian countries (Norway, Sweden, and Denmark) from 2000 to 2020, with a focus on the shift from fossil fuels to renewable energy sources.

The analysis was performed using Python and libraries such as Pandas and Matplotlib. Data cleaning, aggregation, and visualization were key steps in uncovering patterns in the dataset.

## Project Goals

- Investigate global electricity production trends by energy source.
- Compare fossil vs. renewable electricity trends over time.
- Analyze energy production patterns in Norway, Sweden, and Denmark.
- Highlight significant increases or decreases in specific energy sources.
- Practice real-world data wrangling and visualization in Python.

## Data Sources and Cleaning

- Primary dataset: [Electricity Production by Source (Kaggle)](https://www.kaggle.com/datasets/prateekmaj21/electricity-production-by-source-world/data)
- Country codes matched using ISO 3166 standards.
- Non-country entities (e.g., regions) were removed.
- Missing data was dropped to preserve integrity in source-based comparisons.

## Key Insights

### Global Trends (2000–2020)
- Solar energy increased by over 6900%.
- Wind energy grew by over 15,000 TWh, a 22 million percent increase from near-zero levels.
- Gas and hydro also saw significant growth.
- Coal remained the dominant source but showed signs of decline starting in 2018.
- Oil-based production decreased by around 19%.

### Scandinavian Highlights

#### **Norway**
- Dominated by hydropower throughout the period.
- Wind energy increased by 30,000%.
- Minor usage of gas, oil, and renewables.

#### **Sweden**
- Balanced use of hydro and nuclear.
- Wind and solar saw significant growth: solar increased by 28,000%.
- Coal use decreased by 80%.

#### **Denmark**
- Massive shift from coal (-75%) and gas (-88%) to wind (+285%) and solar (+123,000%).
- Denmark remains the smallest producer but is highly reliant on renewables.

## Visualizations

This notebook includes:
- Line plots for electricity production by source (global and country-specific).
- Comparative plots across Scandinavian countries.
- Total production trends over time.
- Percentage change calculations for each country.

## Files

- `Electricity Production Analysis.pdf`: Main notebook with code, visuals, and commentary.
- `README.md`: Project summary (this file).
- Dataset links and references are included within the notebook.

