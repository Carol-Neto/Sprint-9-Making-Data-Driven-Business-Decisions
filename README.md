# Sprint 9 - Making Data Driven Business Decisions


# Project Description

As an analyst for a large online store, I worked with the marketing department to develop a list of hypotheses that could boost our sales. Now, my challenge is to prioritize these ideas, launch an A/B test, and analyze the results to discover which strategies truly work.

It's a challenging but exciting job! After all, it's a chance to put my analytical skills into practice and contribute to the company's growth. 

# Step 1 - Prioritizing Hypotheses

The file `hypotheses_us.csv` contains nine hypotheses for increasing revenue for an online store with Reach , Impact , Confidence , and Effort specified for each. The task is to: 
- Apply the ICE framework to prioritize hypotheses. Rank them in descending order of priority. 
- Apply the RICE framework to prioritize hypotheses. Rank them in descending order of priority. 
- Show how the prioritization of hypotheses changes when you use RICE instead of ICE . Give an explanation for the changes.

# Step 2 - A/B Test Analysis

You ran an A/B test and got the results described in the `orders_us.csv` and `visitors_us.csv` files.

1. Make a graph of the accumulated revenue by group.
2. Plot a graph of the cumulative average order size by group.
3. Plot a graph of the relative difference in cumulative average order size for group B compared to group A.
4. Calculate the conversion rate for each group as the ratio of orders to the number of visits for each day. Plot the daily conversion rates for the two groups and describe the difference
5. Make a scatterplot of the number of orders per user.
6. Calculate the 95th and 99th percentiles for the number of orders per user.
7. Make a scatter plot of order prices.
8. Calculate the 95th and 99th percentiles of order prices
9. Find the statistical significance of the difference in conversion between groups using the raw data.
10. Find the statistical significance of the difference in average order size between the groups using the raw data.
11. Find the statistical significance of the difference in conversion between the groups using the filtered data.
12. Find the statistical significance of the difference in average order size between the groups using the filtered data.

# Conclusion

---
# Dictionary

## /data/hypotheses_us.csv
- `Hypotheses` — brief descriptions of hypotheses
- `Reach` — user reach, on a scale of one to ten
- `Impact` — impact on users, on a scale of one to ten
- `Confidence` — confidence in the hypothesis, on a scale of one to ten
- `Effort` — the resources required to test a hypothesis, on a scale of one to ten. The higher the Effort value, the more resources are required for the test.

## /data/orders_us.csv
- `transactionId` — order identifier
- `visitorId` — identifier of the user who placed the order
- `date` — of the order
- `revenue` — of the order
- `group` — the A/B test group to which the user belongs

## /data/visits_us.csv
- `date` — date
- `group` — A/B test group
- `visits` — the number of visits on the specified date for the specified A/B test group