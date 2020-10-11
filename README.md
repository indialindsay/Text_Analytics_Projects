# Text_Analytics_Projects

This repository contains projects worked on within my text analytics course. 

## Brand/Attribute Discussion Forum Analysis
#### Web-scraped an online discussion forum of luxury sedan car brands and calculated associations between brands and product attributes within 5000 posts

- Calculated how likely one brand is to be mentioned in association with another brand. Notable associations:
  - Honda and Toyota. As these brands are similar in models offered, quality, and affordability, indicates that users may be debating between these two brands
  - Mercedes Benz and Volkswagen. Mercedes is a luxury brand while Volkswagen is not, indicating that consumers may be comparing these brands in quality while offering Volkswagen as an affordable option.
  - Lexus and Mercedes Benz. These two brands can be considered the closest substitutes out of all luxury sedan brands and may be competing for a shared consumer base. 
- Most frequently mentioned car attributes were performance, luxury, engine, price, and power.   
  - In terms of luxury, Lexus had the highest association and BMW had the lowest
  - Honda had the highest association with price, power, and engine; indicates Honda may offer comparative quality to luxury brands in these areas 
- Built an MDS map to visualize lifts between car brands.
  - Identified a cluster of affordable substitude brands: Volkswagen, Honda, Toyota, and Nissan 
- Honda was only affordable brand within top 5 most frequently mentioned brands 
- Volkwagen had the greatest association with aspirational words (words indicative of a users desire to purchase or obtain) 

[Brand/Attribute Discussion Forum Analysis](https://github.com/indialindsay/Text_Analytics_Projects/blob/master/Brand_Attribute_Forum_Text_Analysis.ipynb)

## Beer Recommendation System
#### Designed a collaborative filter combining a customer's desired features with reviews scraped from an online beer rating website to recommend top three similar products
- Product similarity is calculating using cosine similarity and review sentiment. The cosine similarity score identifies reviews that contain our customer's desired features. The sentiment score calculates the overall manner conveyed within the reviewer's mention of the attribute. We only wanted to recommend products that contain the desired qualities mentioned in a positive manner. 
- The overall evaluation score is the average of the product similarity scores from each review for one product. It ranges from -1 to 1; from least similar to the customer's preferences to most similar. 
- For a customer desiring fruity, citrus, and smooth beers, the engine recommended the following: Emerald Grouper, 3rd Anniversary Imperial IPA, and Swish!

[Web Scraped Product Reviews](https://github.com/indialindsay/Text_Analytics_Projects/blob/master/Web-Scraping%20Products.ipynb);
[Recommendation System](https://github.com/indialindsay/Text_Analytics_Projects/blob/master/Recommender.ipynb)
