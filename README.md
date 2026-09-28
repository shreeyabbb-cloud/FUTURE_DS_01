# Task 1: Business Sales Performance Analytics

## Problem
Analyze global retail sales data to find revenue trends, profitability
risks, top markets, and customer value, and turn them into actionable
recommendations.

## Dataset
[Global Superstore (Kaggle)](https://www.kaggle.com/datasets/apoorvaappz/global-super-store-dataset),
about 51K orders across multiple markets. Pulled through the Kaggle API in Colab.

## Tools
Python (pandas, Google Colab) for cleaning, feature engineering and RFM.
Power BI Desktop for DAX measures and a 5-page dashboard.

## Method
1. Cleaned data: fixed date types, removed duplicates and unused columns.
2. Engineered features: Profit Margin %, Discount Buckets, Shipping Delay,
   Net Profit After Shipping.
3. Built an RFM (Recency, Frequency, Monetary) customer segmentation.
4. Designed a 5-page dashboard with conditional formatting.

## Key Insights
**Global Overview:** Revenue grew every year from 2011 to 2014, with a
seasonal peak in Nov-Dec and dips in Feb and Jul. Stock up ahead of Q4 and
consider promotions to offset the July slowdown.

**Category Performance:** Tables loses money (-24.20% margin, negative
profit) despite $7.57L in revenue. Binders, Appliances and Machines are also
unprofitable. Paper and Labels are the most efficient (~12-20% margin).

**Geographic:** Revenue is concentrated in the US ($2.30M, over 2x the next
country). Australia, France and China form a solid second tier.

**Discount Impact:** No-discount orders earn $1.77M profit. Profit falls to
$0.19M loss-making territory at 20-40% discount and to -$0.63M above 40%.
Cap discounts below 40%.

**Customer Segmentation:** Top spenders are highly active, except customer
BW-11110 ($30.6K lifetime spend, 55 days since last order), a clear
re-engagement target.

## Repository Structure
- dashboard/: .pbix, PDF, screenshots
- scripts/: Colab notebook
- data/: RFM output

---
Future Interns Data Science & Analytics Internship
