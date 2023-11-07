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
#### Topic Modeling
![image](https://github.com/Hayoung-Zoe-Kim/Perfume-Recommendation-System/blob/main/Topic_Modeling.png)

#### Word Cloud
![image](https://github.com/Hayoung-Zoe-Kim/Perfume-Recommendation-System/blob/main/WordCloud.png)

#### K-means Clustering visualized by t-SNE
![image](https://github.com/Hayoung-Zoe-Kim/Perfume-Recommendation-System/blob/main/K-means_Clustering.png)
#### MDS graph
![image](https://github.com/Hayoung-Zoe-Kim/Perfume-Recommendation-System/blob/main/MDS_graph.png)

#### Identifying the Long Tail: The System's Unique Feature
![image](https://github.com/Hayoung-Zoe-Kim/Perfume-Recommendation-System/blob/main/LongTail_Graph.png)

## Demonstration of the Recommendation System
![image](https://github.com/Hayoung-Zoe-Kim/Perfume-Recommendation-System/blob/main/System_Demonstration.png)

## Conclusion
- The Word2Vec model facilitated a nuanced understanding of user preferences, connecting scent descriptions and review texts with user sentiments to create a personalized recommendation experience.
  
- The dual-phase approach of the project shed light on a compelling aspect of the fragrance market: While the allure of obscure brands is undeniable for certain attributes, it is remarkable to observe that many affordable yet desirable perfumes originate from well-known houses. This suggests a complex interplay between brand perception and product quality, highlighting an opportunity for small to medium fragrance businesses to capitalize on their unique offerings.

- The value of our Long-Tail Perfume Recommendation System is that by bridging the gap between accessibility and exploration, it stands as a beacon for discovery in the vast ocean of fragrances, guiding consumers to their perfect scent match while supporting the growth of diverse perfume brands.

## Applicable Business Use Cases for The Long-Tail Recommendation System:

#### Niche Market Targeting:
Boutique Retailers can use the system to stock inventory that aligns with the unique preferences of their customer base, helping them to differentiate from larger competitors.

#### Brand Development: 
Emerging and indie fragrance brands can use insights from the system to position their products in the market effectively, focusing on untapped customer segments. Also, the system can help identify scent preferences and trends, which can be used to inform marketing campaigns and product development strategies.

#### Inventory Management:
Retailers can use the system's insights to optimize their inventory, reducing stock of less popular items and focusing on what their customers are most likely to purchase. Moreover, insights from the recommendation system can assist in predicting future trends and demand for certain fragrances, aiding in production planning and inventory forecasting.

