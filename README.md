# AtliQ Mart Supply Chain Analytics

## Problem Statement

* AtliQ Mart, a growing FMCG manufacturer headquartered in Gujarat, India, is currently operational in three cities: Surat, Ahmedabad, and Vadodara. The company plans to expand to other metros/Tier 1 cities in the next 2 years. However, AtliQ Mart is facing a problem where a few key customers did not extend their annual contracts due to service issues. It is speculated that some of the essential products were either not delivered on time or not delivered in full over a continued period, which could have resulted in bad customer service.
* The management wants to fix this issue before expanding to other cities and requested their supply chain analytics team to track the 'On time' and 'In Full' delivery service level for all the customers on a daily basis so that they can respond swiftly to these issues.

## Steps Followed

### Understanding Problem:
* Defined the scope of the analysis, focusing on key metrics like OT%, IF%, LIFR%,etc.
### Data Gathering and Transformation:
* Collected the supply chain data from the provided Excel file.
* Utilized ETL operations to clean and transform the data into a suitable format for analysis.
### Creating Metrics using DAX:
* Implemented Data Analysis Expressions (DAX) to create key metrics, including OTIF%,LIFR% , IF% and more.
### Dashboarding with Power BI Desktop:
* Utilized Power BI Desktop to visualize the data and create interactive dashboards.
* Developed visualizations to provide insights into Customer and product performance acoross key metrics including delays in delivery.

## Key Metrics

- Total Orders: 31.7K
- Total Quantity: 13.4 Million
- IF%: 31.02% below target
- OT%: 31.43% below target
- OTIF%: 55.97% below target
- VOFR%: 96.59%
- LIFR%: 65.96%

## Data Model
![Image Alt text](/images/Data_Model_image)

## Project Presentation Report
(Report)[https://github.com/Swam80/Supply-Chain-FMCG-project_codebasics/blob/main/Supply_chain_FMCG_presentation.pdf]

## Summary

* The key metrics indicate poor customer service in terms of delivery.
* The delivery performance for Coolblue, Acclaimed Stores, and Lotus Mart is concerning, with major issues in on-time delivery and mediocre in full delivery.
* Dairy has been the most ordered category with almost 10.5 Million units which is around 78% of all units ordered.
* For CoolBlue and Elite mart, there is a need to look at the Vadodra branch. For Info store, Surat was the branch and for Soferoz, it was Ahmedabad.
*  AM Milk 500, AM Butter 500, and AM Curd 50 have high demand but low LIFR%, indicating a need to focus on these products.

## Recommendations

1. Improve the 'On time' and 'In Full' delivery service level by optimizing the supply chain processes, improving inventory management, and enhancing supplier reliability.
2. Prioritize the stock for high demand products like AM Milk 500, AM Butter 500, and AM Curd 50 to ensure they are always available for delivery.
3. Pay special attention to the branches that are underperforming, like the Vadodra branch for CoolBlue and Elite mart, Surat for Info store, and Ahmedabad for Soferoz.
4. Prioritize the delivery for top customers like Vijay Stores, Acclaimed, Lotus, and Coolblue who have high quantities of undelivered items.
5. Work on reducing the delivery delay which can go as long as 3 days. This could be achieved by improving the logistics and transportation processes.
6. Set up a regular monitoring system to track the 'On time' and 'In Full' delivery service level for all the customers on a daily basis. This will help in identifying the issues early and taking swift actions.
7. Once the delivery performance is improved and stabilized, start planning for the expansion to other metros/Tier 1 cities. Ensure that the lessons learned from the current operations are incorporated in the expansion plan to avoid similar issues in the future.
