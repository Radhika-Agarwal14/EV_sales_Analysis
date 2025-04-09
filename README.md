# EV_sales_Analysis
EV sales Analysis through Power BI

The purpose of this Project is to Analyze the electric vehicle (EV) market in India through a detailed Power BI dashboard. It aims to provide insights into the current adoption and sales trends of EVs across various states and manufacturers, with a focus on understanding market penetration, growth rates, and regional performance. By leveraging interactive visualizations and calculated metrics like adoption rate, the analysis offers a comprehensive overview of the EV market's performance.

The primary objectives of this analysis are:
•	To evaluate the market penetration of electric vehicles across India, identifying regions with higher adoption and growth potential.
•	To compare sales trends by state, manufacturer, and vehicle category, highlighting key drivers and challenges in EV adoption.
•	To calculate and visualize growth projections for the EV market, using metrics such as CAGR, to forecast future trends.
•	To provide actionable insights for stakeholders, including manufacturers, policymakers, and investors, on strategic areas for expansion and investment.
This Project serves as a valuable tool for understanding the dynamics of the EV market in India and supports data-driven decision-making to accelerate the adoption of electric vehicles in the country.


Introduction

The electric vehicle market in India has witnessed significant growth in recent years, driven by government incentives, rising environmental awareness, and technological advancements. It provides an in-depth analysis of EV sales trends, regional adoption, and the growth outlook for the sector. Understanding these factors is essential for manufacturers, policymakers, and investors aiming to promote EV adoption and expand market share in a rapidly evolving industry.


Data Sources

The analysis of the electric vehicle market in India is based on three primary datasets:
1.	Electric Vehicle Sales by State (electric_vehicle_sales_by_state.csv)
    Description: This dataset contains detailed sales data for electric vehicles in India, segmented by state, vehicle category (e.g., cars, two-wheelers), and 
                year. It also includes the total number of electric vehicles sold and the total vehicle sales in each state, enabling the calculation of market 
                penetration.
    Time Period: The dataset covers the period from 2021 to 2024, providing a comprehensive view of sales trends over the last few years.
    Columns: Key columns in this dataset include state, vehicle_category, electric_vehicles_sold, total_vehicles_sold, and date. This data allows the analysis of 
            sales performance by state and vehicle category.
2.	Electric Vehicle Sales by Manufacturer (electric_vehicle_sales_by_makers.csv)
  	Description: This dataset provides sales data for electric vehicles by various manufacturers in India. It includes details on each maker’s contribution to the 
                market, segmented by vehicle category and year.
    Time Period: The data spans from 2021 to 2024, capturing the performance of major EV manufacturers over the last few years.
    Columns: Key columns include manufacturer, vehicle_category, electric_vehicles_sold, year, and sales_share. This dataset is used to evaluate market share and 
             performance by manufacturer.
3.	Date Dimension Table (dim_date.csv)
    Description: This dimension table contains information related to the fiscal year and quarter. It serves as a time-related reference for the analysis, allowing 
                the dataset to be aligned with India’s fiscal year (April–March).
    Time Period: This table spans the years 2021 to 2024.
    Columns: The key columns include date, fiscal_year, quarter, and month_name. This table is critical for time-based analysis, including calculating year-over- 
             year growth and other time-based metrics.

Data Processing and Transformation

•	Data Cleaning: Removing duplicates, correcting errors.
•	Creating Calculated Columns or Measures: calculating the market penetration rate (EV sales divided by total vehicle sales).
•	Joining Datasets: Joined 3 datasets with one to many relationship with column date in each dataset.

Dashboard overview

Page 1:This page gives the introduction in which there are two navigators when for the makers and the other for the state. Analysis is performed individually on makers and state. This dashboard consists of 4 pages.

Page 2:This page shows the analysis of the makers in which ola electric, tvs ,ather, hero electric are the top sellers for the EV vehicles. Slicers have been made for more comparison among the makers. In India, till now there are 26 makers of EV in which ola electric have shown significant growth over the year from 2021 -2024.Till now 2M vehicles have been sold.

Page 3:This page shows the table where it gives the total market percent of each year among all the makers and how much EV have been sold by them in that year. Line chart shows that march has been the high month for selling of EV. Top performer 4 wheelers is Tata Motors where as for 2 wheelers ola electric.

Page 4:This page shows State analysis that there are total 34 state and UT where EV have been adopted and Maharashtra is top state for EV vehicles.   

Page 5:This page shows the goa has the high adoption rate till now. This table shows the adoption rate and states of all which can be compared.


Analysis and Findings

•	Ola Electric are the top performer overall and in 2 wheeler.
•	Tata motor is top performer for 4 wheeler.
•	Maharashtra is top state for EV.
•	Goa has the high adoption rate.
For new company to enter into the Indian market for Ev, ola electric is the top competitor for 2 wheeler and tata motors for 4 wheelers. Manufacturing plant can be set up in India for more sales


