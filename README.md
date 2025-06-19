# E-commerce-Clothing-Review

## Background
This project aims to analyze customers reviews of women’s clothing from an anonymous ecommerce retailer to uncover insights into customer sentiment, key product attributes, and the impact of customers’ content on purchase decisions. We will leverage NLP and other Machine Learning techniques to extract patterns from customers' reviews. By conducting this analysis, we aim to provide actionable recommendations that e-commerce businesses can apply to improve product offerings, personalize marketing strategies, and enhance customer experience.

## Data Description
### 1. Dataset Overview
• Source: Kaggle dataset – Women’s E-commerce Clothing Reviews https://www.kaggle.com/datasets/nicapotato/womens-ecommerce-clothing-reviews   

• This dataset contains 23,486 customer reviews from a women’s clothing e-commerce platform, anonymized for privacy. 

• It includes 10 features, including Text-based Data, Numerical Data and Categorical Data.

### 2. Key Variables
• Text-based Data:
  Title: String variable for the title of the review.
  Review Text: String variable for the review body.

• Numerical Data:
  Rating(1-5 scale): The product score granted by the customer.
  Age: Positive Integer variable of the reviewers age.
  Positive Feedback Count: Positive Integer documenting the number of other customers who found this review positive.

• Categorical Data:
  Recommended IND: Binary variable stating where the customer recommends the product where 1 is recommended, 0 is not recommended.
  Division Name: Categorical name of the product high level division.
  Department Name: Categorical name of the product department name.
  Class Name: Categorical name of the product class name.

## Scope of Analysis
1. Text Mining
2. Sentiment Analysis
3. Predictive Modeling

## Conclusion
### 1. Key Takeaways
Through sentiment analysis, we found that 77.1% of reviews are positive, with size and fit being the most frequently mentioned concerns. However, negative reviews often highlight issues such as sizing inconsistencies, fabric quality, and product returns, indicating that these factors strongly influence customer dissatisfaction.

In the topic modeling and word cloud analysis, we observed that customers frequently discuss material quality and comfort, reinforcing their importance in purchase decisions. Words like “soft,” “flattering,” and “well-made” appeared often in positive reviews, suggesting that comfort and high-quality materials significantly contribute to customer satisfaction.

Our predictive modeling approach, using a Random Forest model, achieved 94% accuracy in predicting product recommendations. While the model performed well in identifying recommended products, it exhibited lower recall (0.79) for non-recommended items, indicating that improvements are needed to address class imbalance in predictions.

### 2. Business Implications
To further improve the customer experience and drive better purchasing decisions, retailers should focus on enhancing product descriptions, customer engagement, and inventory management strategies.

One key area of improvement is product descriptions, where retailers should provide more detailed sizing information, particularly for items frequently described as “runs small” or “runs large.” This can help customers make more informed choices and reduce the likelihood of returns due to sizing issues.
Additionally, enhancing customer engagement by encouraging buyers to leave more detailed feedback can increase product transparency. This would not only help future buyers make better purchasing decisions but also allow businesses to gain deeper insights into customer preferences and concerns.

Lastly, optimizing inventory and marketing strategies by analyzing the most frequently mentioned product attributes can enable businesses to better align their marketing efforts and inventory planning with customer demands. By leveraging these insights, retailers can refine their product offerings, ensure adequate stock levels for high-demand items, and create more targeted marketing campaigns to enhance customer satisfaction and drive sales.

By implementing these recommendations, e-commerce retailers can significantly enhance customer experience, reduce return rates, and increase sales through data-driven decision-making.
