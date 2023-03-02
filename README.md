# **Analyzing Factors Affecting Pricing on Amazon using Web Scraping and Natural Language Processing**

## **Overview**

This project aims to extract data from Amazon's product pages using web scraping techniques, create a clean and usable dataset, and analyze patterns in word choices that affect pricing. Natural Language Processing (NLP) will be used to develop an understanding of the language used in product descriptions and reviews, and how it relates to pricing. The ultimate goal is to create a model that predicts the price and rating of a product based on its description and reviews.

## **Skills**

This project requires knowledge of web scraping techniques to extract data from Amazon's product pages. Knowledge of NLP methods is essential for understanding and analyzing the language used in product descriptions and reviews. Python is the primary programming language used in this project, and experience in using relevant libraries such as BeautifulSoup, Scrapy, Pandas, and NLTK will be necessary.

## **Research Question**

The primary research question for this project is "What factors affect the pricing of products on Amazon?" The project aims to analyze patterns in the language used in product descriptions and reviews to determine how they relate to pricing. By understanding these factors, we can develop a model that predicts the price and rating of a product based on its description and reviews.

## **Potential Issue**

Scraping for all products on Amazon may not produce congruent results due to the vast number of products available. Therefore, we will focus on scraping data for one product genre to ensure consistent results.

## **Solution**

The solution to the potential issue is to scrape data for one product genre. This approach will ensure that the data is consistent and can be used to analyze patterns in the language used in product descriptions and reviews.

## **Data**

The following data will be extracted from Amazon's product pages using web scraping techniques:

- ASIN ID (Amazon's unique product ID)

- Name

- Price (sale vs original)

- Rating

- Description

- Seller/manufacturer (Sold & Shipped by Amazon, Sold by Third-Party but Fulfilled by Amazon, Sold & Shipped by Third-Party)

- Ranking on search page (page number, best seller rank)

## **Data Cleaning**

The extracted data will be cleaned and processed to create a clean and usable dataset. The cleaning process involves removing irrelevant data, filling in missing values, and standardizing the data format.

## **Natural Language Processing**

NLP methods will be used to analyze the language used in product descriptions and reviews. This analysis will involve identifying patterns and common phrases that are associated with higher-priced products. Sentiment analysis will also be used to determine the tone of the reviews and how it relates to pricing.

## **Model Development**

The final step in this project is to develop a model that predicts the price and rating of a product based on its description and reviews. The model will be trained using the cleaned and processed data, and the NLP features identified in the previous step. The model will be evaluated for accuracy and tested on new data to ensure its reliability.

## **Conclusion**

This project will provide valuable insights into the factors that affect pricing on Amazon. By analyzing patterns in the language used in product descriptions and reviews, we can develop a model that predicts the price and rating of a product accurately. This model can be used by businesses to optimize their pricing strategy and by consumers to make informed purchasing decisions.


