# My-Excel-Project
This project presents an analytical dashboard built using Excel to explore product performance, customer engagement, and pricing strategies from a synthetic Amazon product dataset.

## Overview
The dataset simulates product listings and customer reviews similar to those on Amazon. The goal of this Excel dashboard is to:

- Provide product insights by category

- Analyze discount strategies

- Correlate ratings with review volume

- Identify top-performing products


 ### Additional calculated fields:
  1. potential_revenue = actual_price × rating_count
  2. rating_score = rating × rating_count
  3. price_bucket = Categorized actual prices into ranges

### Steps Taking:
1. I fisrt removed duplicated products from the product_id
2. The category was too long, so I used Text to Columns to split the category where I used main category for the project
3. In addition to the above columns, I added 2 additional columns to it.
4. PivotTables were created, some mentioned below
5. Dashboard / Report was done though I did not include slicer because it was not linking very well.

### PivotTables
- Average discount by category
- Review and rating counts by category
- Product-wise average ratings and review volumes
- Potential revenue analysis
- Product distribution by price range

[Uploading My Excel Project - Amazon case study.xlsx…]()



## Check My Power Bi Below:

I have also done my Power BI project on Palmoria Group.

Here is the link to it:

https://github.com/Davdan35/My-Power-BI-Project/blob/main/README.md
