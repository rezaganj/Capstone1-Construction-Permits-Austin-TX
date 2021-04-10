# Austin, TX Construction Permits
Reza Ganjdanesh

# Overview

Austin, TX leads nation in population growth for a decade. The flight of tech companies to Austin has caused a massive influx of new residents to the city. Home construction in Austin is in historical high. Homebuilders are trying to satisfy demand in the lower price categories by building homes in the previously less popular neighborhoods or outer city borders where land costs are lower.
The hot market trend was prevalent before the pandemic but has become skyrocketing over the past year.
Data from the National Association of Home Builders shows Austin issued 21,653 permits for single-family homes in 2020. That puts the Capital City at No. 5 among U.S. metro areas for single-family construction permits handed out last year.
However, the builders and contractors are having trouble keeping up with the phenomenal demand. There is a significant shortage in the number of new houses. At same time, the cost of hiring contractors and construction supplies are skyrocketing because of high demand.


![Austin News](https://github.com/rezaganj/Capstone_1_ConstructionPermits/blob/main/figures/news.png)
\
\
<br>

# Dataset

- Building, Electrical, Mechanical, Plumbing and Driveway/Sidewalk Permits issued by the City of Austin
- Includes relevant details such as:
    - Issue date
    - Location
    - Expiration date
    - Description of work
    - Square footage
    - Valuation
    - Units
    - ...

Dataset           |      Size
----------------- | ---------
Number of Rows    | 2,038,853
Number of Columns |        68
Dataset size      |     1.3GB

\
<br>

Link to data: https://data.austintexas.gov/Building-and-Development/Issued-Construction-Permits/3syk-w9eu

\
<br>

---

# Motivation

Questions asked:
- What is the trend in permit applications?
- Is the city management prepared for the upward trend?
- Is there seasonality in applications?
- When builders and contractors should prepare for shortage of labor and construction supply in peak seasons?
- When is the best time for home buyers to buy and for home owners to do repair and remodel?
- What neighborhoods and zip codes having more construction?
- ...

## Basic Statistics
![Permit Types](https://github.com/rezaganj/Capstone_1_ConstructionPermits/blob/main/figures/permit_types.png)

![Permit Class](https://github.com/rezaganj/Capstone_1_ConstructionPermits/blob/main/figures/permit_class.png)

![Permit Work Class](https://github.com/rezaganj/Capstone_1_ConstructionPermits/blob/main/figures/permit_work_class.png)

![Permit Approval Time](https://github.com/rezaganj/Capstone_1_ConstructionPermits/blob/main/figures/permit_approval_time.png)

Questions:
- What is the trend in permit applications?
- Are permit applications seasonal?

---
  
# Yearly Total Permit Applications

               Correlation between permit applications and economy
![Yearly Total Permit Count](https://github.com/rezaganj/Capstone_1_ConstructionPermits/blob/main/figures/yearly_total_permit_count.png)



---
  
# Trend in Monthly Permit Applications
![Monthly Applications](https://github.com/rezaganj/Capstone_1_ConstructionPermits/blob/main/figures/monthly_applications_2010_2020.png)

# Seasonality in Permit Applications
![Seasonality in Applications](https://github.com/rezaganj/Capstone_1_ConstructionPermits/blob/main/figures/seasonality_in_permit_applications.png)

## Example
![Seasonality in Heater Applications](https://github.com/rezaganj/Capstone_1_ConstructionPermits/blob/main/figures/seasonality_in__heater_permit_applications.png)

Hypothesis testing:
- Null
- Alternative

# Non-Stationary Time Series
![Non-Stationary Time Series](https://github.com/rezaganj/Capstone_1_ConstructionPermits/blob/main/figures/non_stationary.png)

# Stationary Time Series
![Stationary Time Series](https://github.com/rezaganj/Capstone_1_ConstructionPermits/blob/main/figures/stationary.png)

---
  
# Future Work

- Neighborhood
- Arima

![Arima](https://github.com/rezaganj/Capstone_1_ConstructionPermits/blob/main/figures/arima_predictions.png)

---

![Wordcloud](https://github.com/rezaganj/Capstone_1_ConstructionPermits/blob/main/figures/wordcloud.png)

---
  
