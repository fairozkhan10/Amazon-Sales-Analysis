# Amazon-Sales-Analysis

This project delves into the analysis of Amazon sales data to uncover insights into customer behavior, product performance, and the impact of pricing strategies.

---

## Overview

The analysis addresses two key questions:
1. How do customer ratings vary across Amazon's product categories, and are the ratings related to sales volume?
2. How are Amazon sales and ratings influenced by product discounts?

By leveraging R and R Markdown, the project highlights actionable insights for e-commerce sellers, researchers, and businesses optimizing strategies on platforms like Amazon.

> **Note**: This was a Collaborative Group Project** completed as part of our **Statistics 240: Data Science Modeling I** course at the **University of Wisconsin-Madison**.

---

## Features

- **Dynamic Visualizations**: Explore trends using bar charts, scatter plots, and boxplots.
- **Correlation Analysis**: Examine relationships between ratings, sales, and discounts.
- **Predictive Insights**: Use linear regression and hypothesis testing for data-driven findings.
- **Logarithmic Scaling**: Enhance data interpretation for skewed datasets.

---

## Dataset Details

- **Source**: [Kaggle](https://www.kaggle.com/datasets/karkavelrajaj/amazon-sales-dataset/data) (January 2023)
- **Scope**: Over 1,000 Amazon products from the tech accessories category.
- **Key Variables**:
  - **Product Information**: `product_id`, `product_name`, `category`.
  - **Pricing Details**: `actual_price`, `discounted_price`, `discount_percentage`.
  - **Customer Feedback**: `rating`, `rating_count`, `review_content`.

---

## Key Insights

1. **Sales Volume by Category**:
   - Categories like `Electronics`, `Computers & Accessories`, and `Home & Kitchen` dominate sales volume (approximated by rating count).
   - High customer satisfaction across these categories is reflected in average ratings.

2. **Ratings and Sales**:
   - A weak positive correlation (r = 0.237) exists between ratings and sales volume.
   - Higher ratings have a slight influence on sales, though other factors like marketing play significant roles.

3. **Discounts and Sales**:
   - Surprisingly, discounts show a weak negative correlation with sales volume.
   - This suggests other factors (e.g., quality, branding) are more critical for customer engagement.

---

## Limitations

- **Subjective Ratings**: Ratings alone cannot capture holistic customer satisfaction.
- **Dataset Scope**: Limited to a single category and timeframe, reducing generalizability.
- **Temporal Bias**: Excludes long-term and seasonal trends in consumer behavior.

---

## Future Directions

- **Expand Dataset**: Include additional categories and time periods for broader insights.
- **Advanced Analytics**: Apply machine learning for sentiment analysis and predictive modeling.
- **Cross-Platform Analysis**: Compare trends across different e-commerce platforms.

---

## How to Use

1. **Files**:
   - `Project_Final.Rmd`: Analysis code in R Markdown.
   - `Project_Final.html`: Rendered report with visuals and findings.
2. **Steps**:
   - Open the `.Rmd` file in RStudio.
   - Ensure required R packages are installed.
   - Knit the file to generate the HTML report.

---

## Dependencies

Install these R packages to run the analysis:
- `tidyverse`
- `lubridate`
- `readr`
- `kableExtra`
- `broman`
- `ggplot2`

---

## Contact

For inquiries or feedback:
- **Email**: [Your Email Address]  
- **GitHub**: [Your GitHub Link]
