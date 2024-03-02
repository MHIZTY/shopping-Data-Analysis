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

During the first quarter, the total revenue amounted to $233,132.00, with an average revenue of $59.76 per order. This suggests that, on average, each successful order contributes $59.76 to the revenue stream. Furthermore, a total of 3901 customers placed orders during this period. By dividing the total revenue by the total number of customers, we arrived at the average revenue per customer order.

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
![]()
