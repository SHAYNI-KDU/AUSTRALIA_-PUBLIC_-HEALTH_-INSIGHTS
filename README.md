# AUSTRALIA_-PUBLIC_-HEALTH_-INSIGHTS
Western Australia Public Health Insights Dashboard built using SQL Server and Power BI. This project analyzes real-world public health data including maternal health, alcohol risk, cancer incidence, injuries, fertility, and population trends to support data-driven healthcare planning and policy decisions.


# Western Australia Public Health Insights Dashboard
Project Overview
This project presents an interactive **Public Health Insights Dashboard for Western Australia**, developed using **SQL Server** and **Microsoft Power BI**. The main objective is to analyze and visualize real-world public health data to identify trends, risks, and disparities across regions and years.The dashboard supports evidence-based decision-making for healthcare providers, researchers, and policymakers by transforming complex health datasets into clear, actionable insights.

# Key Focus Areas
The dashboard covers multiple public health indicators, including:

- Potentially Preventable Hospitalizations (PPH)
- Low Birth Weight Trends
- Alcohol-Related Risk and Growth Rates
- Cancer Incidence (Breast, Lung, Prostate, Colorectal)
- Fertility Rates and Stillbirth Percentages
- Injuries and Poisoning Contributions
- Age-Standardized Birth Rates (ASBR)
- Population Demographics (Male/Female ratios)
- Consumer Health Indicators (Diet, Physical Activity, Smoking)

# Tools & Technologies Used
- **Data Source**: Australian Government Open Data  
  https://www.data.gov.au/
- **Database**: Microsoft SQL Server
- **Query Language**: T-SQL
- **Visualization Tool**: Microsoft Power BI
- **Data Modeling**: Advanced DAX calculations

# Methodology
1. **Data Collection**
   - Downloaded public health datasets from data.gov.au
   - Pre-processed data using Microsoft Excel

2. **Database Creation**
   - Created SQL Server database
   - Imported datasets using flat file import

3. **Data Cleaning & Transformation**
   - Standardized column names and data types
   - Handled missing values using T-SQL
   - Applied calculated fields and aggregations

4. **Power BI Integration**
   - Connected Power BI to SQL Server
   - Built data models and relationships
   - Implemented DAX measures for trend analysis

5. **Visualization**
   - Developed interactive dashboards with slicers for:
     - Region
     - Year (2009–2014)

# Key Insights
- Acute conditions contribute the highest proportion of preventable hospitalizations.
- Low birth weight rates remain stable overall but are higher in rural and remote regions.
- Alcohol-related harm shows significant year-to-year fluctuations, indicating the impact of policy and social factors.
- Cancer incidence varies by region and population density.
- Fertility rates remain consistent, while stillbirth percentages are low, reflecting strong maternal healthcare.
- Injury and poisoning rates show a general decline due to improved safety regulations.
- Age-specific birth rates highlight the need for targeted interventions, especially among teenagers.

# Outcomes & Impact
This project demonstrates how **SQL and Power BI** can be effectively used to:
- Identify public health trends
- Highlight regional health inequalities
- Support proactive public health planning
- Enable data-driven policy formulation

# Contributors
Group Assignment – SQL for Data Science (LB1224)  
BSc in Applied Data Science Communication  
General Sir John Kotelawala Defence University

# Future Enhancements
- Extend analysis to recent years
- Add predictive analytics
- Integrate additional public health datasets
- Improve regional drill-down insights
