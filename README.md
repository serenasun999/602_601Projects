# 601 Project - Working with Data and Visualization
### Guiding Questions
1. How did the environmental parameters such as greenhouse gasses (Carbon Dioxide, Methane, Nitrogen Dioxide and Nitric Oxide), air quality index, wind speed and temperature change over the course of 39 years?
2. Is there any correlation between temperature and greenhouse gasses and between wind speed and greenhouse gasses over the 39 years? 
3. What is the distribution of pollutants throughout Calgary? 


# 602 Project - Statistical Data Analysis
### Focus of statistical investigation
The focus of our statistical investigation is to understand if there is any statistical difference between the particulate matter recorded in Calgary vs particulate matter recorded globally in order to gain evidence to support or reject our hypothesis that PM2.5 globally is equal to PM2.5 in Calgary. We also want to determine how the greenhouse gas emissions changed over the years in Calgary by plotting the distribution of greenhouse gas emissions over the years and estimating the population average via bootstrapping. This data is leveraged by the Government of Alberta to visualize, analyze and continually monitor air pollution. This enables Calgary residents to protect themselves and take the necessary precautions especially those who are health compromised. 

## Dataset
- The dataset we have chosen for 601 and 602 project is “Historical Air Quality”  which was collected by the Calgary Region Airshed Zone and submitted to Alberta Environment and Parks (AEP). This information is publicly available and can be used from the City of Calgary’s Open Data Portal. City of Calgary’s Open Data Portal Historical Air Quality [online]. Available at: https://data.calgary.ca/Environment/Historical-Air-Quality/uqjm-jxgp/data
- WHO Air Quality Database. WHO Air Quality Database (Update 2022), Available at: https://www.who.int/data/gho/data/themes/air-pollution/who-air-quality-database
- The datasets we have chosen for 604 through different databases that were collected and published by the American Community Survey, which are publicly available on the New York City Department of Health Environment and Health Data Portal from the New York City government website.
  - New York City Department of Health, Environment & Health Data Portal."Neighborhood Air Quality" data. Black carbon. Accessed at "https://a816-dohbesp.nyc.gov/IndicatorPublic/beta/data-explorer/air-quality/?id=2024#display=summary" on 10/31/2022.
  - New York City Department of Health, Environment & Health Data Portal."Neighborhood Air Quality" data. Fine particles (PM 2.5). Accessed at "https://a816-dohbesp.nyc.gov/IndicatorPublic/beta/data-explorer/air-quality/?id=2023#display=summary" on 10/31/2022.
  - New York City Department of Health, Environment & Health Data Portal."Neighborhood Air Quality" data. Nitric oxide (NOx). Accessed at "https://a816-
dohbesp.nyc.gov/IndicatorPublic/beta/data-explorer/air-quality/?id=2028#display=summary" on 10/31/2022.
  - New York City Department of Health, Environment & Health Data Portal."Neighborhood Air Quality" data. Nitrogen dioxide (NO2). Accessed at "https://a816-dohbesp.nyc.gov/IndicatorPublic/beta/data-explorer/air-quality/?id=2025#display=summary" on 10/31/2022.
  - New York City Department of Health, Environment & Health Data Portal."Neighborhood Air Quality" data. Ozone (O3). Accessed at "https://a816-dohbesp.nyc.gov/IndicatorPublic/beta/data-explorer/air-quality/?id=2027#display=summary" on 10/31/2022.
  - New York City Department of Health, Environment & Health Data Portal."Neighborhood Air Quality" data. Sulfur dioxide (SO2). Accessed at "https://a816-
dohbesp.nyc.gov/IndicatorPublic/beta/data-explorer/air-quality/?id=2026#display=summary" on 10/31/2022.
  - New York City Department of Health, Environment & Health Data Portal. "Adults asthma prevalence" data. Adults with asthma (past 12 months). Accessed at "https://a816-dohbesp.nyc.gov/IndicatorPublic/beta/data-explorer/asthma/?id=18#display=summary" on 10/31/2022.
  - New York City Department of Health, Environment & Health Data Portal. "Economic conditions" data. Neighborhood poverty. Accessed at "https://a816-
dohbesp.nyc.gov/IndicatorPublic/beta/data-explorer/economic-conditions/" on 10/31/2022.
  - New York City Department of Health, Environment & Health Data Portal. "Carbon monoxide" data. Carbon monoxide incidents. Accessed at "https://a816-
dohbesp.nyc.gov/IndicatorPublic/beta/data-explorer/carbon-monoxide-incidents/" on 10/31/2022.
  - New York City Department of Health, Environment & Health Data Portal. "Cancer" data. Lung and bronchus cancer. Accessed at "https://a816-
dohbesp.nyc.gov/IndicatorPublic/beta/data-explorer/cancer/" on 10/31/2022.
  - New York City Department of Health, Environment & Health Data Portal. "Cancer" data. Non-Hodgkin's lymphomas. Accessed at "https://a816-
dohbesp.nyc.gov/IndicatorPublic/beta/data-explorer/cancer/" on 10/31/2022.
  - New York City Department of Health, Environment & Health Data Portal. "Cancer" data. Esophageal cancer. Accessed at "https://a816-dohbesp.nyc.gov/IndicatorPublic/beta/data-explorer/cancer/" on 10/31/2022.
  - New York City Department of Health, Environment & Health Data Portal. "Cancer" data.Larynx cancer. Accessed at "https://a816-dohbesp.nyc.gov/IndicatorPublic/beta/data-explorer/cancer/" on 10/31/2022.
- The datasets we have chosen for 603 is from The North Carolina Department of Public Instruction. School Report Card Resources for Researchers. Accessed at " https://www.dpi.nc.gov/data-reports/school-report-cards/school-report-card-resources-researchers" on 11/15/2022.
