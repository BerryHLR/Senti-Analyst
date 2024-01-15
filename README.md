# Senti-Analyst :rocket:
The impact of news attention and public sentiment on stock prices and how they indicate potential risks in the real estate business
## background :house:
In this information age, the power of public opinion is immense, potentially determining the fate of industries. Presently, the real estate sector is a hot topic of public discourse. Country Garden, a flagship enterprise in Chinese real estate, is navigating a bankruptcy crisis. We aim to uncover the concealed risks and rewards embedded in public sentiment. Our approach involves multivariate sentiment analysis, using public opinions as signals to identify potential risks for real estate companies.
## Purpose :dart:
Our research offers future shareholders a fresh perspective to safeguard against losses. Additionally, we aspire to help companies track public opinion trends, enabling them to adapt promptly and bolster shareholder confidence.
## Methodology or Approach :rainbow:
![image](https://github.com/BerryHLR/Senti-Analyst/assets/129359676/a552c2f0-ea56-4b84-be66-ed634a20e3ec)
![image](https://github.com/BerryHLR/Senti-Analyst/assets/129359676/2e45457d-ccbc-46f0-8c65-3ceb40ceb7d3)
1. We employ Python and Excel to process data, removing duplicates, handling missing values, and eliminating stop words.
![image](https://github.com/BerryHLR/Senti-Analyst/assets/129359676/2691f512-4653-4621-8b1f-6671e2ca1500)
2. We then calculate the average monthly stock price, the proportion of news related to Country Garden, and the average monthly sentiment score.
![image](https://github.com/BerryHLR/Senti-Analyst/assets/129359676/2c15ec3a-3bc4-458a-9352-7febcf6e74d5)
3. We generate graphs to display these metrics over time, calculate their correlation coefficients, and analyze their interrelation.
![image](https://github.com/BerryHLR/Senti-Analyst/assets/129359676/669bc690-6219-440a-9b71-1e439896853d)
![image](https://github.com/BerryHLR/Senti-Analyst/assets/129359676/1beb3a90-3fd8-4b3c-b74f-cfdabba9e065)
4. We find that likes and comments are positively correlated with influence and use this to train a model to predict news influence based on content.
## Key Findings or Results :triangular_flag_on_post:
Our analysis suggests that Country Garden's stock price trends can be predicted from news attention and sentiment scores. Increased news attention and sentiment scores can indicate a potential rise in stock price, while intense news discussions and falling sentiment scores can suggest a potential decline. Sharp increases in news attention and shifts in sentiment scores can predict a consistent decrease in stock price, indicating potential risks.
## Recommendations or Proposed Solutions :memo:
During our trial, we recognized some database limitations and proposed various improvements. Firstly, we suggested enhancing data quality by diversifying data sources for a representative sample and regularly updating sentiment analysis. Secondly, we recommended refining analytics by improving AI and machine learning algorithms in sentiment analysis for better context understanding. Thirdly, we advised balancing metrics by complementing sentiment analysis with other metrics like financial data and market conditions. Lastly, we proposed filtering noise by improving methods to eliminate irrelevant information.
Despite its limitations, sentiment analysis is crucial in forecasting financial trends, as it provides insights into public confidence, a key driver of the economy. This model, while focusing on Country Garden, highlights the potential of social media data in predicting future trends.
## Conclusion
Firms and investors can leverage this approach to prepare for future challenges, using social media monitoring to take swift action against potential stock price drops. This method applies to the entire real estate industry, given adequate data support. An open and vigilant approach to potential market shifts is essential as real estate policies evolve.
Furthermore, this approach of combining big data on stock prices and public sentiment should not be limited to the real estate industry but can be extended to a wider range of industries. This will allow companies in all sectors to be sensitive to the possible future direction of the market and provide quick responses.
