# Implications of Cryptocurrencies for Monetary Systems: The Case of Bitcoins in Turkey

This repository contains the code and data used for the project analyzing the implications of Bitcoin for Turkey's monetary system. The study develops GARCH models to evaluate the impact of Bitcoin price and volatility on key monetary aggregates such as inflation, real exchange rates, and money velocity.

![Image](https://api.time.com/wp-content/uploads/2016/05/gettyimages-534012032.jpg)

## Project Structure

- **`Adv_Macro_project.ipynb`**: Jupyter notebook implementing the data analysis and GARCH models.
- **`Bitcoin_and_Turkey.pdf`**: Report summarizing the theoretical framework, methodology, and key results.

## Key Objectives

The project investigates:
1. How Bitcoin price and volatility influence Turkey's monetary aggregates.
2. The rationale behind Turkey's central bank decision to ban cryptocurrency payments in April 2021.

## Methodology

The study applies GARCH modeling to analyze the relationship between Bitcoin and monetary indicators:
- Inflation (INF)
- Real exchange rate (RER)
- Money velocity (V1 and V2)

### Data Sources
- Bitcoin prices: Yahoo Finance
- Macroeconomic indicators: OECD, FRED, and World Bank

The dataset spans from October 2014 to May 2021.

## Results

1. **Inflation**:
   - Bitcoin price and volatility negatively affect inflation growth.
   - Bitcoin volatility has a significant deflationary impact.

2. **Real Exchange Rate (RER)**:
   - No significant impact of Bitcoin price or volatility on RER.
   - Industrial production differentials influence RER.

3. **Money Velocity**:
   - Bitcoin price has no significant effect on money velocity.
   - GDP significantly affects money velocity across definitions.

## Dependencies

The following Python libraries are required:
- `numpy`
- `pandas`
- `matplotlib`
- `statsmodels`
- `arch`
- `seaborn`

To install the dependencies, run:
```bash
pip install -r requirements.txt
