# EDA on Global Terrorism Dataset

This project performs an Exploratory Data Analysis (EDA) on the Global Terrorism Dataset. It provides insights into patterns, trends, and factors influencing terrorism activities worldwide. Visualizations and statistical analyses are used to highlight key findings.

## Objective
The primary objective of this analysis is to uncover meaningful patterns and trends in terrorism data. This includes:
- Identifying the most affected regions and countries.
- Analyzing attack types and target groups.
- Understanding the impact of terrorism over time.

## Dataset
The dataset used in this project is the [Global Terrorism Database (GTD)](https://www.start.umd.edu/gtd/), which contains detailed information on terrorist events worldwide from 1970 onwards. 

### Key Features of the Dataset:
- **Event ID**: Unique identifier for each incident.
- **Date**: Date of the incident.
- **Region**: Region where the incident occurred.
- **Country**: Country where the incident occurred.
- **Attack Type**: Type of attack (e.g., bombing, armed assault).
- **Target Type**: Target classification (e.g., civilians, government).
- **Casualties**: Number of people killed or injured.

## Key Insights

1. **Geographic Analysis**:
   - Top regions and countries affected by terrorism.
   - Visualization of incident density across the world.

2. **Attack Trends**:
   - Most common attack types.
   - Year-wise trends in the frequency of attacks.

3. **Impact Analysis**:
   - Casualty distribution by region and attack type.
   - Patterns in targeting specific groups or sectors.

## Tools & Technologies
- **Python**: Primary language for data analysis.
- **Libraries Used**:
  - `pandas` and `numpy` for data manipulation.
  - `matplotlib` and `seaborn` for visualizations.
  - `plotly` for interactive graphs.
- **Jupyter Notebook**: Environment for writing and running code.

## Getting Started

To explore the analysis locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/vinitudasi/GlobalTerrorism---EDA.git
   cd GlobalTerrorism---EDA
   ```

2. **Install Dependencies**:
   Ensure you have Python installed, and use the following command to install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn plotly
   ```

3. **Run the Notebook**:
   Open the Jupyter Notebook:
   ```bash
   jupyter notebook Task5.ipynb
   ```

4. **Heatmap**:

![GlobalTerrorism---EDA](images/newplot.png)


## Future Scope
- Deep dive into factors influencing terrorism trends.
- Predictive analysis for assessing potential future incidents.
- Enhanced interactive dashboards using advanced tools like Tableau or Power BI.




## Contributing
Contributions are welcome! Fork the repository, make changes, and submit a pull request.
