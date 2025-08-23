# Climate Risk Premium Analysis: Equity Market Response to Climate Events

A quantitative finance research project analyzing how climate disasters impact stock market returns across climate-sensitive sectors using event study methodology.

## Research Question
Do climate events create abnormal returns in equity markets, and how do different sectors respond to climate-related disasters?

## Key Findings
- **Statistically significant positive abnormal returns** during climate events (p < 0.001)
- Climate events generate **0.17% daily abnormal returns** on average
- **Energy sector** shows highest volatility (36.5% annual) but strong returns (16.5% annual)
- **Insurance sector** demonstrates best risk-adjusted performance
- Results challenge conventional assumptions about climate risk pricing

## Methodology
- **Sample**: 90,424 daily observations from 45 companies (2017-2024)
- **Sectors**: Energy, Insurance, Real Estate
- **Events**: 7 major climate disasters (hurricanes, wildfires, extreme weather)
- **Analysis**: Event study methodology with statistical hypothesis testing
- **Tools**: Python, Pandas, SciPy, Matplotlib, Seaborn

**Disclosure** This analysis was conducted independently with all data collection, statistical testing, and interpretation performed by the author. Claude AI was used for writing structure and presentation.

## Repository Structure
├── notebooks/
│   ├── data_collection.ipynb          # Web scraping and data gathering
│   ├── data_cleaning_and_feature_engineering.ipynb  # Feature creation and EDA
│   ├── event_study_analysis.ipynb     # Statistical hypothesis testing
│   └── conclusions_and_implications.ipynb  # Research synthesis
├── data/
│   ├── raw/           # Original datasets
│   └── processed/     # Cleaned, analysis-ready data
└── requirements.txt   # Project dependencies

## Statistical Results
- **Primary hypothesis test**: t-statistic = 6.23, p < 0.001
- **Effect size**: Cohen's d = 0.054 (small but economically meaningful)
- **95% Confidence interval**: [0.11%, 0.22%] daily abnormal returns
- **Sample size**: 4,319 event window observations vs 86,105 normal period observations

## Business Applications
This analysis informs:
- Investment strategy and portfolio construction for climate-sensitive sectors
- Risk management frameworks for climate-related events
- Regulatory policy on climate risk disclosure requirements
- Insurance premium setting and risk assessment models

## Author
**Anush Nepal**
