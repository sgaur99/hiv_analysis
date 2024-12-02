---

# HIV Trends and Economic Indicators Analysis

This project explores the intricate relationship between **HIV prevalence** and economic factors such as **GDP** and **unemployment** across **France, Germany, Italy, and the United Kingdom** for the period 2007–2016. The analysis uncovers key insights and provides actionable recommendations to improve public health outcomes.

---

## Features
- **Custom Dataset Creation**: Data compiled from trusted sources like **WHO** and **World Bank**, ensuring accuracy and eliminating the need for cleaning.
- **KPI Calculations**:
  - **HIV Prevalence Rate (%)**
  - **Mortality Rate (%)**
- **Visual Insights**:
  - Comprehensive visualizations (e.g., scatter plots, trend lines).
  - Analysis of key factors such as HIV-related deaths, new cases, and demographic trends.
- **Data-Driven Recommendations**:
  - Country-specific strategies to improve public health and reduce socio-economic disparities.

---

## Project Structure
```plaintext
.
├── data/
│   ├── country_csv.csv           # Country-level economic and population data
│   ├── hiv_csv.csv               # HIV-related statistics
│   └── hiv.db                    # SQLite database containing integrated data
├── images/
│   ├── Deaths.png                # Trend in HIV-related deaths by country
│   ├── GDP.png                   # GDP trends over the years
│   ├── HIV Prevalence Rate (%)   # KPI: HIV prevalence rate visualization
│   ├── HIV Under 5 (%).png       # Children under 5 living with HIV
│   ├── New Cases.png             # Trend in new HIV cases
│   ├── Population.png            # Population trends by country
│   ├── Unemployment.png          # Unemployment rate trends
│   ├── Women's share (%).png     # Women's share of HIV cases
│   └── hiv_prevalance_*.png      # Various KPI-related scatter plots
├── notebooks/
│   └── hiv_analysis.ipynb        # Jupyter Notebook for end-to-end analysis
├── myenv/                        # Python virtual environment
├── .gitignore                    # Git ignore file
├── requirements.txt              # Python libraries required for the project
└── README.md                     # Project documentation
```

---

## Prerequisites
To run this project, ensure you have:
- **Python 3.x**
- Required libraries: Pandas, NumPy, Matplotlib, Seaborn, SQLite3, Jupyter Notebook

Install dependencies:
```bash
pip install -r requirements.txt
```

---

## Usage
### 1. Clone the Repository
```bash
git clone https://github.com/sgaur99/hiv-trends-analysis.git
cd hiv-trends-analysis
```

### 2. Set Up the Environment
- Use the `hiv.db` file in the `data` folder for database operations.
- Visualizations are stored in the `images` folder.

### 3. Run the Jupyter Notebook
Open and execute `hiv_analysis.ipynb` step-by-step for the complete analysis:
```bash
jupyter notebook notebooks/hiv_analysis.ipynb
```
---

## Insights and Recommendations
- **Economic and Health Correlation**:
  - Countries with higher GDP exhibit **lower HIV prevalence**, reflecting how economic stability supports better public health.
  - Higher unemployment correlates with **increased HIV prevalence**, showcasing socio-economic disparities.

- **Public Health Trends**:
  - **France**: Significant progress with a **50% reduction in HIV-related deaths**.
  - **UK**: Highest increase in new cases, highlighting the need for proactive measures.

- **Demographics**:
  - Women and children under five are critical demographics requiring targeted healthcare strategies.

---

## Tools and Technologies
- **Programming**: Python (Pandas, NumPy, Matplotlib, Seaborn)
- **Database**: SQLite
- **Visualization**: Matplotlib and Seaborn
- **Notebook**: Jupyter

---

## License
This project is licensed under the **MIT License**.

---

## Contact
For questions or collaboration:
- **Name**: Shashank Gaur
- **Email**: shashank.gaur3099@gmail.com
- **GitHub**: https://github.com/sgaur99