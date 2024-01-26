# Waste Data & Visualisation

## Problem Space and Project Idea
In this project, we looked at some of the frequently used items at home and measured the waste produced by them in each category, such as bio, glass, metal, plastic or paper waste, and used it to do some projection to see yearly waste produced and which category and items are contributing the most to this.

Despite having recycling technologies around, only 13% of the waste produced globally is recycled. This differs country to country, but even different kind of waste has different recyclability. The idea of this project is to raise more awareness about different aspects of recycling and make the audience to seek for more sustainable and environment friendly packaging. 

## Approach

1. Manual data collection, by hand picking some items that are widely used on daily/weekly basis and measuring the weight of the waste and calculating the usage of the item on the unit of the packages. This helps to calculate monthly or yearly projection.
2. Researching the recycling information and papers, finding reliable sources around recycling process, cost of recycling, energy needed for the recycling, and estimations on the global waste produced every year.
3. Data preparation to add columns per category and also totals for different period of time, like Monthly or Yearly
4. Data exploration to see data from different perspectives and find potential correlations and form hypothesis around it and also ideas on how to effectively visualise it
5. Visualisation and presentation

## Hypothesis

After exploring data, we formed following hypothesis:

Items with short shelf time tends to have worst environmental impact, which means the `env impact` is greater than `0.5` with 95% certainity (more than half of the waste produced are harmful for the environment).

Null Hypothesis: env impact <= 0.5

Alternative Hypothesis: env impact > 0.5

The outcome produced p-value of 0.23 which is higher than our 0.05 threshold and rejects the null hypothesis.

## Data Visualisation
Built a Tableau dashboard which can be used to raise awareness and also allows to explore the data.

https://public.tableau.com/app/profile/sanober.khoso/viz/WasteRecycling_17061348989520/Dashboard1?publish=yes