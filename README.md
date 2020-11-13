# Etsy-Web-Scrape

# Project Summary 
For start-ups in the DIY/ handmade businesses, Etsy is the one of the most well-known place to start. However, competitors are tough these days, and the more you know your them, the better decisions you can make for your own store. This project's client is a newly-established handmade paracord bracelet brand, who want to explore their competitors on the Etsy market. The information and analysis might be beneficial in their costing plan and marketing strategies.

# Dataset
- The dataset was scraped from Etsy on Oct 29, 2020, with 944 observations.
- Variables including:
    - header: name of the product
    - price_cad: price in CAD
    - sales: total sales of the seller/ store
    - seller: name of the seller/ store
    - details: details of the product
    - description: what seller say about that product
    - availability
    - num_reviews: total reviews of the seller/ store

# Process
1. Scrape relevant data from Etsy
- Keyword used: paracord bracelet
- Number of pages to scrape: 20 pages, as most customers will not surf more than that
- Category: Braided & Woven bracelets
- Use BeautifulSoup to scrape contents
2. Clean & Aggregate Data
- Extract information from the 'details' column, such as:
    - made_to_order
    - personalised
    - material
    - adjustable
    - bracelet_width
    - bracelet_length
- Outliers Detection
3. Data Analysis & Visualization
- General Market
- Explore sellers
- Description Analysis
- Header Analysis

# Tools used
1. Pandas
2. Numpy
3. Matplotlib/ Seaborn: Data Visualization tools
4. BeautifulSoup: Scrape data from web
5. Wordninja: split long words that are originally 2 words but stick together
6. re/ nltk: Natural Language Tool Kit for Text Analysis
7. LDA: identify common topics using LDA with Gensim
8. WordCloud: graph showing words with most occurence

