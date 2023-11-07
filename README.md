# Long-Tail Perfume-Recommendation-System

## Project Overview

#### Purpose
The aim of the project is to leverage sophisticated text analysis and machine learning techniques to curate and suggest unique perfume selections for niche markets with specific preferences.

#### Problem Statement
- Enhance shopping experience by minimizing choice overload and discovering high-quality,
unique products
- Empower small to medium fragrance business owners to elevate the value of their underrated
products
- Assist perfume enthusiasts in exploring affordable fragrances while discovering new scents

## Methodology
Initially, we extracted perfume reviews through web scraping. We then selected long-tail perfumes with proven quality, indicated by overall ratings exceeding 4.5 out of 5. Based on the scent descriptions and the review texts, we calculated a comprehensive evaluation score for each review. This was achieved by multiplying the similarity and sentiment scores derived from the reviews against a simulated user profile detailing scent preferences, usage occasions, and price range. Finally, employing a Word2Vec model, our recommendation system generated a list of high-scoring long-tail perfumes.

#### Data Source & Preprocessing
- source: https://www.fragrancex.com/shopping/type/perfume
- Data Collection: Scraped 69,000 'Women Perfumes' Reviews
- Key Columns: Brand, Product Name, Description, Price, Ratings, Reviews
- Data Cleaning: Focus on 29,793 Reviews from 238 Brands

## Highlights of Analysis

![image](https://github.com/Hayoung-Zoe-Kim/Perfume-Recommendation-System/blob/main/Topic_Modeling.png)
![image](https://github.com/Hayoung-Zoe-Kim/Perfume-Recommendation-System/blob/main/WordCloud.png)
![image](https://github.com/Hayoung-Zoe-Kim/Perfume-Recommendation-System/blob/main/K-means_Clustering.png)
![image](https://github.com/Hayoung-Zoe-Kim/Perfume-Recommendation-System/blob/main/MDS_graph.png)
![image](https://github.com/Hayoung-Zoe-Kim/Perfume-Recommendation-System/blob/main/LongTail_Graph.png)
![image](https://github.com/Hayoung-Zoe-Kim/Perfume-Recommendation-System/blob/main/System_Demonstration.png)

## Conclusion

## Applicable Business Use Cases for The Long-Tail Recommendation System:



