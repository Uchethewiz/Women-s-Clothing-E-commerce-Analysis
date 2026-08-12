# Women-s-Clothing-E-commerce-Analysis
A data analytics project exploring 23,486 customer reviews from a women's clothing e-commerce company to uncover what drives customer satisfaction and product recommendations, and to deliver actionable, data-driven business recommendations.

## Business Problem

A leading women's clothing e-commerce company (name withheld) collects thousands of customer reviews — including star ratings, written feedback, and recommendation status — but lacked a structured way to understand what this feedback was telling them. The company needed to know:

- Which products and departments customers love (and which they don't)
- What actually drives a customer to recommend a product
- Whether satisfaction varies across different customer segments
- Where to focus improvement efforts to boost customer satisfaction and recommendation rates

## Objective
As the Data Analyst on this project, my task was to:

1. Clean and prepare the raw customer review dataset for analysis
2. Formulate and answer at least 6 meaningful business questions using the data
3. Design an interactive dashboard that visually communicates the findings
4. Deliver a concise executive summary with actionable recommendations for management

## 🛠️ Tools Used
- **Power BI** — data modeling, DAX calculations, and interactive dashboard design
- **Excel/CSV** — initial data cleaning and inspection
- **Data visualization** — bar charts, stacked bar charts, pie charts, and KPI cards to communicate findings

## 📝 Executive Summary

This analysis examined 23,472 customer reviews to understand customer satisfaction, product performance, and the factors influencing product recommendations. The dashboard analyzed ratings, recommendation behavior, product classes, departments, age groups, and review distributions to surface patterns that support strategic decision-making.

**Headline metrics:**
| Metric | Value |
|---|---|
| Customer Feedback (reviews analyzed) | 23,472 |
| Average Rating | 4.20 / 5 |
| Product Classes | 20 |
| Departments | 6 |
| Overall Recommendation Rate | 82.23% |

Overall, customer satisfaction is high, and satisfaction is strongly and consistently linked to recommendation behavior. However, a subset of product classes are meaningfully underperforming and represent a clear opportunity for improvement.

## DASHBOARD 
![DASHBOARD PREVIEW](./DASHBOARD/DASHBOARD PREVIEW.png)
Women's-Clothing-Ecommerce-Analysis/DASHBOARD/DASHBOARD PREVIEW.png

## Key Insights

1. **Overall customer satisfaction is high.** The average customer rating is 4.20/5, and 5-star reviews (13.12K) make up the largest share of all feedback, followed by 4-star reviews — very few customers gave 1- or 2-star ratings.

2. **Higher ratings strongly drive recommendations.** Recommendation rates climb sharply as ratings increase — from just ~1.9% of 1-star reviewers recommending the product to **99.81%** of 5-star reviewers doing so, confirming a strong positive relationship between satisfaction and advocacy.

3. **Satisfaction is consistent across age groups.** Average ratings range narrowly from 4.14 to 4.29 across all age brackets (18–25 through 56+), with the 18–25 group rating products slightly highest — indicating the product line resonates broadly regardless of customer age.

4. **Bottoms, Intimate, and Jackets are the top-performing departments**, with average ratings of 4.29, 4.28, and 4.26 respectively and recommendation rates above 83%. **Trend is the weakest department**, with an average rating of just 3.82 and a recommendation rate of 73.95%.

5. **Seven product classes underperform the company average.** Trend, Sweaters, Swim, Dresses, Blouses, Outerwear, and Knits all recorded recommendation rates between ~74% and 82%, below the overall 82.23% benchmark — flagging them as priority areas for quality or design review.

6. **Positive experiences dominate the feedback pool**, with 5-star and 4-star reviews together accounting for the vast majority of the 23K+ reviews collected, reinforcing an overall healthy customer sentiment base to build on.

## Recommendations

1. **Prioritize the Trend department and its lowest-rated classes.** Dig into the underlying review text for Trend, Sweaters, Swim, Dresses, Blouses, Outerwear, and Knits to identify recurring complaints about quality, sizing, fit, or design, and act on them.
2. **Replicate what's working in top departments.** Study the product design, quality standards, and customer preferences behind the success of Bottoms, Intimate, and Jackets, and apply those learnings to underperforming categories.
3. **Leverage top-rated products and reviews in marketing.** Since highly rated products are overwhelmingly recommended, feature top-rated products and verified reviews prominently on product pages to build trust, boost conversion, and encourage more customer feedback.

---

## 📊 Dashboard

The interactive dashboard (built in Power BI) includes filters for Division, Department, Class, Rating, and Age, and visualizes:
- Impact of product ratings on recommendations
- Lowest-rated product classes
- Average rating by age group
- Recommendation rate and average rating by department
- Distribution of ratings across the full review dataset

## 🗂️ Data Source

- **Dataset:** Women's Clothing E-Commerce Reviews dataset
- **Size:** 23,486 customer reviews (23,472 after data cleaning)
- **Fields included:**
  - `Title` — review title (text)
  - `Review Text` — full review text
  - `Rating` — product rating (1 = worst, 5 = best)
  - `Recommended IND` — whether the customer recommended the product (1 = yes, 0 = no)
  - `Positive Feedback Count` — number of users who found the review helpful
  - `Division Name` — high-level product division (e.g., General, Intimate)
  - `Department Name` — product department (e.g., Tops, Dresses, Bottoms)
  - `Class Name` — product class (e.g., Knits, Dresses, Denim)
