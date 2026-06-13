# Understanding Uganda's GDP: Machine Learning Prediction Analysis

![GDP Analysis](assets/uganda%20gdp.png)

##  Project Overview

This project focuses on analyzing **Uganda's Gross Domestic Product (GDP)** from 2001 to 2025, exploring economic trends across different sectors and using machine learning to forecast future GDP values.

**GDP Definition:** The standard measure of value added created through the production of goods and services within a specific period of time.

###  Objectives

- Analyze Uganda's economic growth trends over 24+ years
- Identify sector contributions to economic development
- Build predictive models for future GDP forecasting
- Visualize economic patterns and insights

---

##  Dataset

- **Source:** [Uganda Bureau of Statistics (UBOS)](https://www.ubos.org/explore-statistics/)
- **Time Period:** 2001 - 2025
- **Data Format:** Excel spreadsheet (`UBOS_GDP_CP.xlsx`)
- **Key Metrics:** Gross Domestic Product by sector and year

---

##  Methodology

### 1. **Data Acquisition**
   - Data sourced from the official UBOS website
   - Multiple sectors tracked over 24+ years

### 2. **Data Loading & Cleaning**
   - Utilized **Pandas** for data inspection and validation
   - Handled missing values and data inconsistencies
   - Prepared data for exploratory analysis

### 3. **Exploratory Data Analysis (EDA)**
   - Visualized trends using **Matplotlib**
   - Analyzed sector-wise contributions to GDP
   - Identified growth patterns and anomalies

### 4. **Machine Learning Models**
   - **Linear Regression:** Baseline model for trend prediction
   - **Random Forest Regressor:** Advanced ensemble method for improved accuracy
   - Model evaluation and comparison of predictive performance

---

##  Project Structure

```
Understanding-UBOS_GDP_CP/
├── README.md                        # Project documentation
├── Understanding UBOS_GDP.ipynb     # Main analysis notebook
├── UBOS_GDP_CP.xlsx                 # Raw dataset
├── assets/                          # Project images
│   └── uganda gdp.png              # GDP visualization
└── uganda gdp.png                  # Hero image
```

---

##  Technologies Used

| Tool | Purpose |
|------|---------|
| **Python** | Core programming language |
| **Pandas** | Data manipulation & cleaning |
| **Matplotlib** | Data visualization |
| **Scikit-learn** | Machine learning models |
| **Jupyter Notebook** | Interactive analysis environment |

---

##  Getting Started

### Prerequisites
- Python 3.7+
- Jupyter Notebook
- Required packages: pandas, matplotlib, scikit-learn

### Installation

```bash
# Clone the repository
git clone https://github.com/200-4/Understanding-UBOS_GDP_CP.git
cd Understanding-UBOS_GDP_CP

# Install dependencies
pip install pandas matplotlib scikit-learn jupyter

# Launch Jupyter Notebook
jupyter notebook "Understanding UBOS_GDP.ipynb"
```

---

##  Key Findings

The analysis reveals:
- Long-term GDP growth trends in Uganda
- Sector-wise economic contributions
- Predictive insights for future economic development
- Model performance comparison between Linear Regression and Random Forest approaches

---

##  Notebook Contents

The main Jupyter notebook (`Understanding UBOS_GDP.ipynb`) includes:
- Data loading and preprocessing
- Exploratory data visualization
- Statistical analysis
- Machine learning model development
- Predictions and performance metrics
- Conclusions and recommendations

---

##  Model Performance

Both models were evaluated for accuracy in predicting future GDP values:
- **Linear Regression:** Fast, interpretable baseline model
- **Random Forest Regressor:** Captures non-linear relationships for potentially better predictions

---

##  Future Improvements

- Incorporate additional economic indicators (inflation, exchange rates)
- Implement advanced models (ARIMA, Neural Networks)
- Add external economic factors analysis
- Create interactive visualizations with Plotly/Dash
- Deploy prediction model as a web application

---

##  License

This project is open-source and available for educational and research purposes.

---

##  Author

**200-4**

For questions or suggestions, feel free to open an issue or contact the repository owner.

---

##  References

- [Uganda Bureau of Statistics](https://www.ubos.org/)
- Scikit-learn Documentation: Machine Learning Models
- Pandas Documentation: Data Analysis
- Matplotlib Documentation: Data Visualization

---

**Last Updated:** June 2026
