# CO₂ Emissions Statistical Analysis: Top 10 Economies (1970–2020)

## Introduction
This repository hosts a comprehensive statistical analysis of CO₂ emissions for the top 10 global economies based on nominal GDP around 1970, covering the period from 1970 to 2020. The selected countries—United States, Soviet Union/Russia, Japan, West Germany/Germany, France, United Kingdom, Italy, China, Canada, and India—were identified using historical GDP data for consistency, as per the assignment guidelines. This project applies statistical methods to examine emission patterns, variability, and trends across five decades, providing insights into the environmental impact of economic growth, industrialization, and energy policies.

The analysis is derived from raw emissions data, processed in Excel, and summarized in a detailed report. It highlights the disproportionate historical responsibility of developed nations for global CO₂ emissions while noting the rapid rise in emissions from emerging economies like China and India.

## Project Objectives
- Identify the top 10 economies by 1970 GDP and filter CO₂ emissions data accordingly.
- Compute key statistics (mean, variance, standard deviation, minimum, maximum) for emissions at decade intervals (1970, 1980, 1990, 2000, 2010, 2020).
- Interpret results to discuss highest/lowest emissions, variability, trends, outliers, and influencing factors such as economic transformations, energy strategies, and historical events.
- Visualize cumulative contributions and trends for enhanced understanding.

## Data Sources
- **Raw Data**: `annual-co2-emissions-per-country.csv` – Annual CO₂ emissions (in tonnes) for countries worldwide, sourced from reliable datasets (e.g., Our World in Data or similar). Data extends up to 2023, but analysis focuses on 1970–2020.
- **GDP Reference**: Historical GDP figures from 1970 used to select countries, verified against sources like UN/IMF estimates.
- **Processed Data**: Cleaned and calculated in Excel, addressing any missing values transparently.

## Methodology
1. **Data Preparation**:
   - Filtered the CSV dataset for the top 10 countries: United States ($1.1T), USSR/Russia ($433B), Germany ($216B), Japan ($213B), France (~$148B), United Kingdom (~$130B), Italy (~$113B), China (~$92B), Canada (~$87B), India (~$62B).
   - Ensured complete data for decade markers (1970, 1980, 1990, 2000, 2010, 2020); no significant missing values noted after cleaning.

2. **Statistical Analysis** (in `annual-co2-emissions-per-country_ManojKumar.csv.xlsx`):
   - For each decade and country, extracted annual emissions.
   - Calculated:
     - Mean: Average emissions.
     - Variance: Spread of data.
     - Standard Deviation: Variability.
     - Minimum/Maximum: Extreme values.
   - Results organized in decade-specific sheets with summary tables.

3. **Visualization and Interpretation**:
   - Created a pie chart for cumulative emissions (1970–2020).
   - Interpreted findings in the report, linking statistics to real-world factors (e.g., China's industrialization, France's nuclear policy).

## Key Findings
### Cumulative CO₂ Emissions Share (1970–2020)
A pie chart in the report illustrates long-term contributions:
- United States: 45% – Reflects industrial dominance and fossil fuel reliance.
- Russia (USSR legacy): 13% – High from heavy industry and energy production.
- Germany: 10% – Coal-based historical emissions.
- United Kingdom: 8% – Early industrialization, recent declines via renewables.
- Japan: 7% – Post-war expansion and imports.
- India: 6% – Later industrialization, rising recently.
- France: 4% – Low due to nuclear energy.
- Canada: 4% – Energy-intensive industries like oil sands.
- Italy: 3% – Moderate contributions.
- China: Implied in analysis as a major variable emitter (not explicitly in pie percentages but discussed extensively).

**Insights**:
- Developed nations bear historical responsibility due to early industrialization.
- Energy policies (e.g., France's nuclear adoption) significantly reduce emissions.
- Emerging economies show high variability linked to growth.

### Decade-Specific Statistics and Trends
- **1970–1980**:
  - Highest Mean: United States (4,687,380,727 kt).
  - Lowest Mean: India (233,703,287 kt).  <!-- Corrected from document typo -->
  - Largest Variability: China (Variance: 6.52322×10¹⁶; Std. Dev.: 2,555,823,329).
  - Smallest Variability: France (Variance: 5.51548×10¹⁴; Std. Dev.: 23,485,066).
  - Trend: Stable high emissions in developed countries; China's rapid industrialization causes volatility.

- **1980–1990**:
  - Highest Mean: United States (4,771,131,118 kt).
  - Lowest Mean: India (412,309,034 kt).
  - Largest Variability: China (Variance: 1.50868×10¹⁷; Std. Dev.: 388,417,017).
  - Smallest Variability: Germany (Variance: 6.54625×10¹⁴; Std. Dev.: 25,585,631).
  - Trend: Continued stability in mature economies; China's fluctuations from policy shifts.

- **1990–2000**:
  - Highest Mean: United States (5,478,999,100 kt).
  - Lowest Mean: India (773,204,051 kt).
  - Largest Variability: China (Variance: 1.73446×10¹⁷; Std. Dev.: 416,467,986).
  - Smallest Variability: France (Variance: 1.52248×10¹⁴; Std. Dev.: 12,333,901).
  - Trend: Outliers in China/India from development; predictable in France.

- **2000–2010**:
  - Highest Mean: China (rising to lead by end).
  - Lowest Mean: France.
  - Largest Variability: China (Variance: ~3.006×10¹⁸; Std. Dev.: 1,733,665,532).
  - Smallest Variability: France.
  - Influences: China's economic boom; Russia's post-Soviet drop; Japan's Fukushima impact.

- **2010–2020**:
  - Highest Mean: China (e.g., 9,860,457,000 kt in 2015).
  - Lowest Mean: France (e.g., 331,490,200 kt in 2015).
  - Largest Variability: China (Variance: 3.662×10¹⁷; Std. Dev.: 605,148,202).
  - Smallest Variability: France.
  - Trend: China's dominance in emissions due to manufacturing; stable lows in nuclear-reliant France.

Overall, the analysis reveals a shift from Western dominance to Asian growth, with policy and economic maturity driving differences.

## Repository Structure
- **`CO2 Emmission Class Activity Solution.docx`**: Final report with methodology, tables, pie chart, and interpretations.
- **`annual-co2-emissions-per-country.csv`**: Raw annual CO₂ emissions dataset.
- **`annual-co2-emissions-per-country_ManojKumar.csv.xlsx`**: Processed Excel file with cleaned data, decade sheets, calculations, and cumulative distribution.

## How to Use This Repository
1. **Review the Report**: Open the DOCX for a complete overview.
2. **Explore Data**: Use the CSV for raw insights or extend analysis (data up to 2023 available).
3. **Verify Calculations**: Check Excel sheets for stats; formulas are embedded.
4. **Reproduce/Extend**:
   - Import CSV into Python (e.g., Pandas) or Excel.
   - Filter for countries and years.
   - Compute stats: e.g., `np.mean()`, `np.var()`.
   - Generate visuals with Matplotlib or Excel charts.

## Limitations and Future Work
- Analysis limited to 2020 per assignment; CSV includes up to 2023 for potential updates.
- Assumes constant country boundaries (e.g., Russia for USSR).
- Future: Incorporate per capita emissions, sector breakdowns, or post-2020 data for climate policy analysis.

## Acknowledgments
- Data sourced from public datasets.
- GDP verification from historical economic reports.

For contributions or issues, please open a pull request or issue on GitHub.
