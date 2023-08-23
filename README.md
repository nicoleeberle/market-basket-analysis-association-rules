# Market Basket Analysis using Association Rules in Python
Here you can see a market basket analysis that I completed using association rules in python. While this project is completed on an example dataset, it outlines a modeling thought process that can be applied to much larger and more complex datasets. 

# Files
The following files are available to download:
1. HTML: Final write up of analysis including all code, explanations and analysis. This is all you need to see the full project
2. Code: Python code file. This allows you to re-run the analysis on your own
3. Data: The excel file dataset. This allows you to re-run the analysis on your own

# Project Topic
Using transaction level data, retailers want to understand more about consumer purchases. The dataset includes transaction at the item level from two different retailers. In this analysis, we will be focusing on if there are products that are more likely to be purchased together. Understanding this has many useful applications for the retailer, such as product placement, potential promotion offers, and other cross-sell opportunities.

Focus Question: Are there products that are more likely to be purchased together?

# Conclusion
Four key relationships were uncovered in this analysis: 
- Bud Light 24 Pack -> Coke 20 oz: Customers who bought a Bud Light 24 Pack are 1.29 times more likely to buy a Coke 20 oz. Of customers who bought a Bud Light 24 Pack, 13% also bought a 20 oz Coke
- Coke 20 oz -> Bud Light 24 Pack: Customers who bought a 20 oz Coke are 1.29 times more likely to buy a Bud Light 24 Pack. Of customers who bought a 20 oz Coke, 31% also bought a Bud Light 24 Pack
- Miller Lite 24 Pack -> Bud Light 24 Pack: Customers who bought a Miller Lite 24 Pack are 1.25 times more likely to buy a Bud Light 24 Pack. Of customers who bought a Miller Lite 24 Pack, 30% also bought a Bud Light 24 Pack
- Bud Light 24 Pack -> Miller Lite 24 Pack: Customers who bought a Bud Light 24 Pack are 1.25 times more likely to buy a Miller Lite 24 Pack. Of customers who bought a Bud Light 24 Pack , 12% also bought a Miller Lite 24 Pack 

The retailers could use these rules to come up with cross-sell promotions. This could increase revenue by helping decrease the number of transactions that only contain one product. They also could use this information to help inform product placement within the store. By placing items likely to be purchased together near each other, customers may be more likely to grab a second related item if they see it. 
