# Health Twitter Topic Modeling

This project utilizes various machine learning techniques to explore topic modeling from health-related tweets. The Twint Python package was used to scrape over 200,000 tweets from 14 health related Twitter News Sources, including BBC Health, CNN Health, Fox News Health, NYT Health, and US News Health. The two main models that were used for topic modeling were Latent Dirichlet Allocation (LDA), and Gibbs Sampling Dirichlet Multinomial Mixture (GSDMM). These models yielded 10 distinct and descriptive topics among the scraped tweets. Sentiment Analysis also classified the polarity and subjectivity of the scraped data.  

# File Directory

* The gsdmm folder contains all files related to running the GSDMM Model.
* The notebooks folder contains all the Exploratory Data Analysis, topic models, and sentiment analysis files. These are Jupyter Notebooks.
* The pyLDAvis folder contains the model visualizations from the LDA analysis.
* The `preprocessor.py` file processes the scraped data.
* The `twitter_scraper.ipynb` file contains the scraping script for our data. 
