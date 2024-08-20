# Covid-19-Data-Analysis-Project
This project analyzes COVID-19 data in India, focusing on actice cases, deaths, and vaccination status across the different states. The project uses data visualization tools to provide insights into the pandemic's trends and impacts.

## Files
- `covid_19_india.csv`: Contains COVID-19 case data for India.
- `covid_vaccine_statewise.csv`: Contains vaccination data for different states in India.
-  `covid_analysis.ipynb`: Jupyter notebook containing the data analysis and visualization code.

## Explanation:
- `Data Loading`: Load covid-19 case data and vaccination data from CSV file.
- `Data Cleaning`: Drop unnecessary columns and convert date formats.
- `Active Cases Calculation`: Calculate active cases by subtracting cured and death cases from confirmed cases.
- `Pivot Table`: Create a pivot table to aggregate state-wise data and calculate recovery and mortality rates.
- `Visualizations`:
      - Bar plots for top 10 states with most active cases and deaths.
      - Line plot for growth trends of active cases in a top 5 affected states.
      - Pie chart for male and female vaccination distribution.
      - Bar plots for top 5 most and least vaccinated states.
