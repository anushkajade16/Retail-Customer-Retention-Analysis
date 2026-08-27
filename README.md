# Retail Customer Retention Analysis (Power BI)

This is a Power BI project I worked on to understand customer retention for a retail business (using Target as the case study). Basically I wanted to figure out which customers keep coming back, which ones stop shopping, and why.

I used five datasets - customer info, transactions, store locations, loyalty program data, and churn records - cleaned them up in Power Query, built a data model, and then created some DAX measures to calculate things like churn rate, customer lifetime value, and repeat customer counts.

## What I found

The overall churn rate came out to 24.5%, which was expected, but what surprised me was that customers in the "Elite" loyalty tier actually churn more than lower tiers. You'd think the top-tier customers would be the most loyal, but that's not what the data showed here. That's something worth digging into further.

Another thing I noticed - customers are earning way more loyalty points than they're actually redeeming. So the loyalty program exists, but people aren't really using it to its full potential.

Store-wise, Superstores had the highest average purchase amount, online was the lowest. And churn stayed pretty much the same (~24.5%) no matter which store type you look at, so store type alone doesn't really explain churn.

## Dashboards

I built 4 dashboard pages:
1. Customer Retention Overview - churn rate, repeat vs churned customers, breakdown by income level
2. Loyalty & Promotion Analysis - promotion usage, churn by loyalty tier, points earned vs redeemed
3. Store & Channel Performance - purchase amounts and churn across store types
4. Customer Segmentation - CLV and purchase frequency broken down by region, age, and loyalty tier

Each page has filters (region, channel, income level, loyalty tier) so you can dig into the numbers yourself.

## Tools used
Power BI Desktop, Power Query for cleaning, DAX for the measures.

## Files in this repo
- Full project report (PDF) - goes into more detail on the datasets, DAX formulas, and methodology
- Dashboard screenshots (PDF)
- Video walkthrough: https://drive.google.com/file/d/1-a9shIea7Lgt4NpCHDCRdty5_M7rlCUK/view

## If I had more time
I'd want to look closer at why Elite tier churn is higher, and maybe build out a way to track this over time instead of just a snapshot.
