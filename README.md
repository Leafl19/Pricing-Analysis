## Pricing Analyst


## Project Objective
The objective of this pricing analysis is to explore various factors affecting product pricing, including discount impact, price elasticity, category-wise pricing strategy, and time-based trends. The analysis aims to uncover patterns and insights that will help optimize pricing strategies for increased revenue and sales volume.
 

## Project Tools Used

- R for data analysis and calculations.

 - dplyr for data manipulation and summarization.

 - Tableau for dashboard visualizations.
 

## Project Overview and Process 
I conducted multiple anlaysis to complete this entire analysis, and they were, first i wanted to find out how gross and ent prices vary across products, than after that i wante dto compare sales with and without discounts to see how they affected sales volume and net revenue, Next I went and determined how price changes influenced the quantity sold and overall revenue, I also went a analyzed if there was any changes in pricing by the diffrent months and specific day of thw week and finally i wanted to understand how diffrent product categories varied in the pricing strategy also with discounts. 


## Price Distribution Analysis

**Calculations**

- Average Gross Amount(Before Discount): 3012.94
- Average Net Amount(After Discount: 2875.95
-	Insights: The distribution of gross and net amounts shows a shift after discounts, but both maintain similar ranges. Outliers are present, indicating potential premium or low-cost products.

![Gross amount before discount](https://github.com/user-attachments/assets/3841b0f6-31e8-4f32-a467-d292f56f84d4)


![Net amount after discount](https://github.com/user-attachments/assets/d6cf5fae-0d82-412f-b824-2cb4cc4c8f98)


## Discount Impact Analysis
 Calculations:
- Transactions with Discounts: 27,415
- Average Net Amount (with discount): 2737.67
- Total Sales (with discount): 75,053,170.40
- **Insights**: Discounts lead to slightly lower net amounts but do not significantly affect the gross amount. Sales volume remains consistent, indicating that discounts drive customer engagement without heavily impacting overall revenue.


![Discount Impact](https://github.com/user-attachments/assets/8c789445-971f-47d0-93a7-25bd8a57af36)

## Price Elasticity Analysis

 Calculations:
- Highest Transaction Count: 9,832 (Price Range: 1000-2000)
- Highest Total Sales: 41,486,316.40 (Price Range: 4000-5000)
-	**Insights**: Lower price ranges attract more transactions, but higher price ranges generate more revenue. This confirms the price elasticity effect, where lowering prices boosts sales volume, but higher prices result in higher total sales.

![Price Elasticity](https://github.com/user-attachments/assets/7eb992d7-904c-4ad7-bb3c-912293445ba9)

## Time-Based Pricing Trends
 Calculations:
 - Highest Gross Amount by Month: December
 - Highest Gross Amount by Day: Wednesday
-	**Insights**: There are clear patterns in gross amounts based on month and day, with spikes during December and midweek. This suggests the possibility of seasonal and day-based pricing strategies to maximize sales.

![Price Trends By Month](https://github.com/user-attachments/assets/06d977da-6d38-42ea-9154-edb5e527ef31)

![Price By DOW](https://github.com/user-attachments/assets/b51316ab-2b5d-4059-bee5-1e973baad5c5)

## Category-Wise Price Analysis

 Calculations:
- Electronics: Highest Total Gross Sales (49,743,502.50)
- Beauty and Health: Highest Avg Gross Amount (3038.90) 
- **Insights**: Electronics and Clothing are high-performing categories, with substantial total sales. Beauty and Health maintain a higher average price, indicating a premium strategy. Discounts applied across categories show varied effects, with some categories more responsive than others.

![Category Price Wise](https://github.com/user-attachments/assets/c63f857c-a110-4412-97ab-358c57b5e2dc)

 
## Recommendations for Overall Analysis
- Leverage Effective Discounts: Discounts like NEWYEARS and SEASONALOFFER21 were the most effective. Consider using these types of offers more frequently to maintain customer engagement

- Targeted Category Strategies: Focus on optimizing pricing and promotions in Electronics and Clothing, as these categories drive the highest sales volumes. For premium categories like Beauty and Health, maintain high average pricing but offer discounts sparingly

- Optimize Time-Based Pricing: Utilize day-of-the-week and month-based trends to plan promotions, with a focus on months like December and days like Wednesday for maximized sales. Seasonal promotions during holidays or specific weekdays could further boost sales

- Price Elasticity Considerations: A balanced pricing strategy can target different consumer segments. Lower price ranges increase transaction counts, while higher price ranges generate more total sales. So considering varying prices to appeal to different buyer personas
