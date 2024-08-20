# Hubspot-Subscription-Sales-Analysis

## The goal of this project is to investigate the sales performance from 2022 to 2023 at HubSpot in order to surface recommendations on enhancing sales tactics and fostering overall growth.

**Founded in 2006, HubSpot is a leading customer relationship management (CRM) platform that offers a comprehensive suite of tools for marketing, sales, customer service, and content management.** Serving millions of customers worldwide, HubSpot enables businesses to grow and manage their relationships with customers effectively. In recent years, HubSpot has continuously innovated its product offerings, expanding its subscription services to include various plans tailored to the diverse needs of its clients.

In 2022 and 2023, HubSpot focused on optimizing its subscription sales strategies, launching targeted marketing campaigns, and introducing new product features to enhance customer engagement and retention. The subscription plans, ranging from Starter to Enterprise, each with distinct pricing tiers and service levels, have been instrumental in driving HubSpot’s revenue growth. With a dedicated data team, HubSpot aims to analyze the performance of these subscription plans, evaluate customer acquisition, and optimize its sales strategies for future growth. The company’s efforts are geared toward two primary objectives: 1) increasing sustained growth, and 2) expanding HubSpot’s global presence and market share.



## Data cleaning & Explorenatory analysis

Identify missing values, duplicated entries, and correlations between Revenue and the four dimensions—Product, Plan Period, Customer Platform, and Region. For more details, click [here](https://github.com/WittsMei/Hubspot-Subscription-Sales-Analysis-Overview/blob/main/Hubspot%20Data%20Cleaning%20%26%20EDA.ipynb).

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
- At the start of September 2022, Enterprise plans saw a remarkable spike, hitting a record high of $3.35 million in monthly bookings. However, this surge sharply declined, almost reaching its lowest point, 2.31 million, in June 2023 during the two-year period.
- Starters and Professionals plans exhibited significant volatility from summer 2022 to fall 2023. This fluctuation warrants an investigation to determine whether there are underlying issues with the products themselves or if a new competitor has entered the market, potentially impacting the performance of these plans.

#### Plan Period
- Yearly plans make up around 70% of the bookings but have exhibited a significant drop-off towards September 2023, which was more than four times the drop-off observed in monthly plans.


#### Plan Region
- UCAN accounted for nearly two-thirds of the monthly bookings, with the majority of yearly and marketing hub bookings also concentrated in this region.
- From summer 2022 to summer 2023, all regions exhibited a consistent drop-off in bookings.


## Suggestions & Next Step

#### Plan Platform Type
- Investigate the Cause of the Decline: The sharp decline in Enterprise plans from September 2022 to June 2023 requires a detailed analysis. Review any changes in product offerings, pricing, or market conditions that may have contributed to this drop.
- Customer Feedback: Conduct surveys or interviews with Enterprise plan customers to understand their concerns or reasons for downgrading or canceling. This feedback could provide insights into necessary adjustments.
- Targeted Promotions: Consider launching targeted promotions or value-added services to reinvigorate interest in the Enterprise plan, particularly focusing on the features that initially drove the spike in September 2022.
- Analyze Market Competition: The volatility in these plans may be influenced by new competitors. Conduct a competitive analysis to identify any new entrants in the market and how they might be affecting customer choices.
- Product Improvement: Evaluate the features and pricing of the Starters and Professionals plans. If product issues are identified, prioritize enhancements to address customer pain points and stabilize performance.
Monitor Trends: Continuously monitor the performance of these plans to detect early signs of market shifts, enabling quicker responses to emerging trends.

#### Plan Period
- Focus on Retention for Yearly Plans: Given the significant drop-off in yearly plans, particularly in September 2023, implement retention strategies such as loyalty programs, renewal discounts, or added incentives for long-term commitments.
- Analyze Customer Preferences: Investigate why customers might be shifting away from yearly plans in favor of monthly options. Understanding their preferences can help tailor offers that better align with their needs.
Reassess Yearly Plan Value Proposition: Ensure that the value proposition of yearly plans is clearly communicated and perceived as advantageous compared to monthly options.

#### Plan Regional:
- Strengthen UCAN Market: Given that UCAN dominates both monthly and yearly bookings, prioritize this region in your marketing and sales strategies. Consider further investment in customer acquisition and retention programs tailored to this market.

- Address Regional Drop-Offs: Since all regions showed a consistent decline from summer 2022 to summer 2023, investigate regional-specific factors contributing to this trend. Adjust marketing strategies and product offerings to better cater to the unique needs of each region.
Expand Regional Focus: If other regions show potential for growth, consider developing region-specific campaigns or introducing products that cater specifically to their markets.


#### Continuous Monitoring and Data Analysis:
- Establish Regular Reporting: Set up a system for regular monitoring of plan performance, customer feedback, and market conditions. This will allow for timely adjustments and proactive decision-making.
- Predictive Analytics: Use predictive analytics to anticipate future trends in bookings based on historical data, helping to optimize marketing and sales strategies ahead of time.
- Make a quaterly option to increase AOV (average order value). 
