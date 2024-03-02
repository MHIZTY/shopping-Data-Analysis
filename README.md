# shopping-Data-Analysis

## Introduction 
This Excel project delves into the realm of retail shopping analysis. It aims to scrutinize, analyze, and derive insights to address pivotal queries, thereby aiding the marketing department in crafting data-informed strategies

## Problem Statement
The marketing department has set its sights on launching a campaign in the second quarter of 2024. However, they necessitate a comprehensive dashboard to monitor business activities during the interim period. This dashboard is pivotal in guiding campaign efforts, offering insights into strategic allocation of resources. Key metrics to be tracked over time include:

1. Performance of products
2. Shifts in customers' color preferences
3. Geographic and seasonal trends influencing orders

## Skills demonstratred
Throughout the analysis, a repertoire of skills was showcased, encompassing descriptive analysis, dataset summarization via pivoting, data cleaning/transformation, and statistical analysis.

## Data sourcing
The project entailed a meticulous examination of a dataset procured from Google Drive, facilitated by the Data-Nex instructor. This dataset revolves around consumer shopping behaviors. The analysis endeavors to discern consumer preferences across product categories, unraveling trends and patterns crucial for product refinement and marketing endeavors.

## Data Transformation and Cleaning
To fortify the quality and reliability of the dataset, rigorous steps were undertaken:

1. Elimination of duplicate entries
2. Sorting of data
3. Application of data filters
4. Replacement of erroneous values
5. Implementation of conditional formatting
6. Segmentation of cell contents
7. Utilization of formulas and functions
8. Accurate referencing of cells

## Cleaning the Data
Upon meticulous scrutiny of the dataset, various issues surfaced, including blank cells, incomplete data, formatting discrepancies, and inconsistencies in certain columns. Notably, the customer column exhibited missing and incomplete entries. These anomalies were identified through the filter option, prompting corrective measures.

**Table 1:**
This table illustrates the Customer ID column before and after refinement.

| Customer ID (Before) | Customer ID (After) |
|-----------------------|---------------------|
|                       |                     |

**Table 2:**
Here, the Category column is displayed. Upon review, it was noted that the category column contained variations like "footwear" and "foot wear." To rectify this, the replace functionality was employed.

| Category (Before) | Category (After) |
|--------------------|------------------|
|                    |                  |

**Table 3:**
This table showcases the Color column. During the review, it was observed that some cells were blank. Utilizing the filter option, these blank cells were replaced with "Not available."

| Color (Before) | Color (After) |
|----------------|---------------|
|                |               |

**Table 4:**
Here, the Age column is examined. Two outliers were identified during the review process, and appropriate corrective measures were taken.

| Age (Before) | Age (After) |
|--------------|-------------|
|              |             |

**Table 5:**
This table focuses on the Purchased Amount column. It was discovered that the formatting was incorrect, marked as a general value. The currency format was applied, ensuring precision with two decimal places.

| Purchased Amount (Before) | Purchased Amount (After) |
|----------------------------|--------------------------|
|                            |                          |

## Data Modelling
Data Modeling:
Throughout the analysis, no formal data modeling techniques were employed. The data provided was contained within a single Excel file.

## Analysis and Visualization:
The data underwent thorough cleaning and organization using Excel. Unnecessary columns were removed, duplicates were addressed, and efforts were made to handle blank or incomplete data entries. Following data cleaning, Excel functions such as mean, average, min, max, and various lookup functions (including MATCH, INDEX, and VLOOKUP) were utilized to generate a summary of the dataset. Additionally, the dataset was explored for insights through pivoting.

## Descriptive Analysis
Descriptive Analysis:
**Finding 1:**
In our analysis, we conducted descriptive analysis to gain insights into various aspects of the dataset, including total revenue, average revenue per item, quantity of items ordered, total number of customers, average customer age, as well as the minimum and maximum purchased items. 

During the first quarter, the total revenue amounted to $233,633.00, with an average revenue of $59.75 per order. This suggests that, on average, each successful order contributes $59.76 to the revenue stream. Furthermore, a total of 3901 customers placed orders during this period. By dividing the total revenue by the total number of customers, we arrived at the average revenue per customer order.

Upon closer examination, the maximum item purchase cost was $100, categorized into product ("coat"), category ("outerwear"), color ("Beige"), and season ("spring"). Conversely, the minimum purchased item cost was $20, identified as product ("sneakers"), category ("footwear"), color ("white"), and season ("summer"). 

In summary, our analysis recommends focusing marketing efforts on the footwear category to enhance customer engagement.

**Finding 2:**
Using pivot tables to summarize the dataset, we scrutinized product performance. The top-performing product was identified as "blouse," generating a revenue of $10,410. Following closely were "dress" and "shirt." Notably, "blouse" belongs to the clothing category department.

**Finding 3:**
Our investigation into customer color preferences revealed that "olive" ranked highest among other colors, with 176 demands. "Silver" and "yellow" secured second and third positions with 173 and 172 demands, respectively.

**Finding 4:**
Focusing on location performance, we narrowed down to the top 10 locations based on item purchases. "Montana" emerged as the top performer with 96 purchases, while "Maryland" ranked lowest with 86 purchases.

**Finding 5:**
Analyzing business activity across seasonal periods, we found that during spring, the highest number of orders were placed, totaling 1000, accounting for 26% of the total. Fall and winter followed closely with 25% each, while summer witnessed relatively fewer orders, totaling 955, constituting 24% of the total. This suggests that marketing strategies should be tailored towards the spring season.

## Dashboard

## Actions and Recommendations

1. **Focus on Clothing Category:** The analysis revealed a significant consumer preference for clothing items, particularly blouses, with 3849 purchases recorded. To capitalize on this trend, the marketing team should prioritize efforts towards promoting the clothing category in their campaigns.

2. **Target Montana for Enhanced Performance:** Montana emerged as the top-performing location with 96 purchases, indicating promising market potential. Conversely, Maryland exhibited lower performance with 86 purchases. Allocating additional resources and strategies towards Montana could help surpass current demand levels and drive further growth.

3. **Emphasize Olive Color Production:** Customer preference analysis highlighted olive as the most sought-after color, with 176 orders, followed closely by silver and yellow. To meet consumer demands effectively, the marketing team should focus on producing more items in olive color variants, ensuring alignment with popular preferences.

4. **Strategic Focus on Blouse Production:** In conclusion, marketing and advertising campaigns should strategically prioritize the production and promotion of blouses, considering both color preferences and location-specific demands. By tailoring campaigns to highlight blouse offerings, while incorporating preferred colors and targeting high-performing regions, the marketing team can maximize campaign effectiveness and drive sales growth.

## Based on the report findings, here are five actions and recommendations

1. **Product Diversification and Promotion:**
   - Action: Expand the product range within the clothing category, particularly emphasizing blouse designs.
   - Recommendation: Develop a marketing campaign to showcase the diverse range of clothing options available, with special focus on promoting blouses to capitalize on their popularity among consumers.

2. **Localized Marketing Strategies:**
   - Action: Tailor marketing efforts to target specific regions based on performance metrics, such as Montana's high purchase rate.
   - Recommendation: Implement targeted advertising campaigns in regions like Montana to further stimulate demand and increase market share. Allocate resources to understand local preferences and consumer behavior for more effective campaigns.

3. **Color-Driven Product Development:**
   - Action: Adjust product development strategies to incorporate popular color preferences, such as olive, silver, and yellow.
   - Recommendation: Prioritize the production of clothing items, particularly blouses, in colors that align with consumer preferences. Conduct market research to identify emerging color trends and adapt product offerings accordingly to maintain competitiveness.

4. **Enhanced Customer Engagement:**
   - Action: Implement customer engagement initiatives to foster brand loyalty and encourage repeat purchases.
   - Recommendation: Launch loyalty programs or exclusive promotions targeting frequent customers to incentivize continued patronage. Utilize customer feedback mechanisms to gather insights and tailor offerings to meet evolving needs and preferences.

5. **Data-Driven Decision Making:**
   - Action: Establish a robust data analytics framework to continuously monitor and analyze sales trends, customer preferences, and market dynamics.
   - Recommendation: Invest in data analytics tools and expertise to gain deeper insights into consumer behavior and market trends. Use these insights to inform strategic decision-making, optimize product assortments, and refine marketing strategies for better alignment with customer needs and market demands.
