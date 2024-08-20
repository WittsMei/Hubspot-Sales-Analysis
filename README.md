# Hubspot-Subscription-Sales-Analysis

## The goal of this project is to investigate the sales performance from 2022 to 2023 at HubSpot in order to surface recommendations on enhancing sales tactics and fostering overall growth.

**Founded in 2006, HubSpot is a leading customer relationship management (CRM) platform that offers a comprehensive suite of tools for marketing, sales, customer service, and content management.** Serving millions of customers worldwide, HubSpot enables businesses to grow and manage their relationships with customers effectively. In recent years, HubSpot has continuously innovated its product offerings, expanding its subscription services to include various plans tailored to the diverse needs of its clients.

In 2022 and 2023, HubSpot focused on optimizing its subscription sales strategies, launching targeted marketing campaigns, and introducing new product features to enhance customer engagement and retention. The subscription plans, ranging from Starter to Enterprise, each with distinct pricing tiers and service levels, have been instrumental in driving HubSpot’s revenue growth. With a dedicated data team, HubSpot aims to analyze the performance of these subscription plans, evaluate customer acquisition, and optimize its sales strategies for future growth. The company’s efforts are geared toward two primary objectives: 1) increasing sustained growth, and 2) expanding HubSpot’s global presence and market share.



## Data cleaning & Explorenatory analysis

Identify missing values, duplicated entries, and correlations between Revenue and the four dimensions—Product, Plan Period, Customer Platform (Plan Platform Type), and Region (Plan Region). For more details, click [here](https://github.com/WittsMei/Hubspot-Subscription-Sales-Analysis-Overview/blob/main/Hubspot%20Data%20Cleaning%20%26%20EDA.ipynb).

<img width="920" alt="image" src="https://github.com/user-attachments/assets/8c050c6f-4333-4f67-9582-2f56e504610a">


## Dashboard
The dashboard can be found in Tableau Public [here](https://public.tableau.com/app/profile/witts.jianming.mei/viz/HubspotSalesOverview/HubspotSalesOverview?publish=yes). This dashboard allows users to filter by date, platform type, product, and region, with a focus on revenue metrics.

<img width="947" alt="image" src="https://github.com/user-attachments/assets/6db17bc9-6467-4316-a0e7-05ae7a8a4379">



## North Start Metrics & Dimensions
- **Total Sales**: Total subscription sales from Starter, Professional, Enterprise plans
- **Plan Platform Type**: Starter, Professional, Enterprise 
- **Plan Period**: Yearly or monthly plan
- **Plan Region**: Asia Pacific (APAC), United States, Canada, and the Caribbean (UCAN), Latin America (LATM), Europe, the Middle East, and Africa (EMEA)


## Summary of Insights

#### Plan Platform Type
- In September 2022, Enterprise plans experienced a significant surge, reaching a record high of $3.35 million in monthly bookings. However, this momentum sharply declined twice: first in the winter of 2022 and then again in the summer of 2023, eventually falling to nearly its lowest point of $2.31 million by June 2023.
- Starters and Professionals plans exhibited significant volatility from summer 2022 to fall 2023. This fluctuation warrants investigation to determine whether the issues stem from the products themselves or if post-pandemic shifts in business priorities and digital strategies are affecting their performance.


#### Plan Period
- Yearly plans, which made up approximately 70% of total bookings, saw a substantial decline by September 2023 compared to July 2022—exceeding the drop-off in monthly plan bookings by more than four times.



#### Plan Region
- UCAN accounted for nearly two-thirds of the total bookings, with the majority of yearly plans and marketing hub bookings concentrated in this region.
- From summer 2022 to summer 2023, all regions experienced a gradual decline in bookings.


## Suggestions & Next Step

- Deep dive into the factors behind the sharp decline in Enterprise plan bookings after September 2022 and the significant fluctuations in Starters and Professionals plans from summer 2022 to fall 2023. Consider factors such as market competition, product features, or post-pandemic related in customer needs. Are there any product features we can implement to combat these dips?

- 

- Make a quaterly option to increase AOV (average order value). 
