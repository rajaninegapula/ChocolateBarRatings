# ChocolateBarRatings

1. Introduction
Chocolate is among the most beloved candies worldwide. In the United States alone, people consume a staggering 100 pounds of chocolate collectively every second. This analysis aims to uncover insights into consumer behavior within the chocolate industry. By analyzing patterns in the data, we can identify key factors that influence consumer ratings and how these factors affect their preferences.

2. Conclusions Addressing Research Questions

What are the key variables influencing Chocolate Bar Ratings?
From the Random Forest model, CocoaPercentage emerges as a critical factor, as indicated by its significant contribution to the percentage increase in Mean Squared Error (MSE). Additionally, REF proves to be important due to its role in enhancing the purity measure.

Are chocolate ratings improving over time?
Based on the Mean Rating vs. Time plot, there is a clear upward trend in chocolate ratings over time. Furthermore, the Linear Regression model confirms that increasing time contributes positively to ratings, establishing a linear relationship between the two.

What is the impact of CocoaPercentage on chocolate ratings?
The Linear Regression analysis reveals that higher CocoaPercentage is associated with a decrease in ratings, indicating a negative relationship between cocoa content and consumer preference.

Key Findings
• Average Rating is approximately 3.1, indicating most chocolates fall in the "Satisfactory to Praiseworthy" range.
• Cocoa Percent ranges from 60% to 100%, with a higher concentration around 70-80%.
• The dataset includes chocolates from over 50 Company Locations and cocoa beans from more than 40 countries.

Limitations
1. Data Completeness: Missing values in certain fields like Specific Bean Origin could impact deeper analysis.
2. Bias: Ratings are subjective and may reflect individual preferences of reviewers rather than universal standards.
3. Scope: Focuses narrowly on plain dark chocolate, excluding flavored or milk chocolate, which limits broader industry insights.

• ![image](https://github.com/user-attachments/assets/2a8a18ba-dbad-4476-be40-951c7c6a2b06)
Interpretation of the Correlation Heatmap:
1. Cocoa Percent vs. Rating: Correlation is slightly positive, suggesting that higher cocoa percentages might be associated with slightly higher ratings.
2. Review Date vs. Rating: Correlation is near zero, indicating no meaningful relationship between the year of review and ratings.
3. Review Date vs. Cocoa Percent: Very weak negative correlation, indicating almost no relationship between the review date and cocoa percentage.
• ![image](https://github.com/user-attachments/assets/0cc6dd19-1797-47b0-94a0-19da20c7c21c)
Observations from the Scatterplot:
• There is no strong linear relationship between Cocoa Percent and Rating.
• However, chocolates with cocoa percentages around 70%–75% seem to have more favorable ratings, indicating a potential sweet spot for cocoa content.
• ![image](https://github.com/user-attachments/assets/1c9b7b35-e4d4-4cab-bbd9-3cd472947831)
• ![image](https://github.com/user-attachments/assets/3fc763a1-3198-48a2-8bfa-f8facd2ab57b)

The dataset contains 10 columns, with a mix of numeric and categorical variables. Here's a brief summary: Columns:
1. REF: Unique reference numbers (likely not useful for analysis).
2. Company: Name of the chocolate company (categorical).
3. Company Location: The country where the company is based (categorical).
4. Review Date: Year of the review (numeric).
5. Country of Bean Origin: Country where the cocoa beans were sourced (categorical).
6. Specific Bean Origin or Bar Name: Details about the bean origin or bar name (categorical).
7. Cocoa Percent: Percentage of cocoa in the chocolate (numeric).
8. Ingredients: Type and number of ingredients (categorical).
9. Most Memorable Characteristics: Descriptive traits of the chocolate (textual).
10. Rating: The rating given to the chocolate (numeric).

The analysis addresses the following:
• **Geographical Trends:** Where are the best cocoa beans grown? Based on the categorical plot (e.g., average ratings by Country of Bean Origin), countries like Venezuela, Ecuador, and Madagascar often source highly-rated beans. These regions are known for their favorable climates and soil for high-quality cocoa.
• Which countries produce the highest-rated chocolate bars?
The Company Location bar plot shows that countries like Belgium, Switzerland, and France consistently produce high-rated chocolate bars. These regions have established reputations for chocolate craftsmanship, which is reflected in the ratings.
• **Cocoa Percent and Ratings**: Is there a relationship between cocoa solids percentage and ratings? The scatterplot of Cocoa Percent vs. Rating reveals a slight positive trend, suggesting that chocolates with higher cocoa content generally receive better ratings. However, the relationship is weak and not strictly linear.
• **Does a higher cocoa percentage correlate with better ratings?** Chocolates in the 70%–75% cocoa range tend to receive the highest ratings. Extremely high cocoa percentages (e.g., above 85%) sometimes lead to lower ratings, possibly due to the bitterness associated with higher cocoa solids.
• **Company Performance: Which companies consistently produce high-rated chocolate bars? **A focused analysis of the Rating variable by Company can reveal top-performing companies. Based on preliminary insights, companies in regions like Switzerland and France stand out for their high ratings.
• **Are there regional patterns in company performance?** European countries dominate in producing high-rated chocolate bars. This could be due to their access to premium cocoa beans and advanced chocolate-making techniques.
• **Trends Over Time: How have chocolate ratings changed over the years?**
The pair plot and correlation analysis show no significant change in average ratings over the years. This indicates that rating standards have remained consistent over time.
• **Do certain regions show improvement in quality over time?** A deeper time-based analysis of Company Location and Rating is required to identify whether specific regions show improvement. However, current data does not strongly suggest significant regional trends over time.

