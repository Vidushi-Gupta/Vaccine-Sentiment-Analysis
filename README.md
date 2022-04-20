# Vaccine-Sentiment-Analysis
## Abstract
The world is facing a huge crisis in the form of the coronavirus pandemic. More than a year has passed since the Covid-19 pandemic and there has been an outcry on social media over the requirement and feasibility of a COVID-19 vaccine. The project aims to analyze tweets related to Pfizer's vaccine, identify views on the vaccine and extract key themes. We performed a multi-class sentiment analysis. The obtained model result is one of three emotions (positive, negative, neutral). Based on the results, calculate the accuracy and F1 score for comparison between different models. Topic modeling was performed on the combined tweet dataset using LDA to derive the top seven topics. In addition, exploratory data analysis was performed on datasets containing global vaccination progress to highlight vaccine uptake.


## Introduction and Motivation
Sentiment Analysis is the process of ‘computationally’ determining whether a piece of writing is positive, negative or neutral. It’s also known as opinion mining, deriving the opinion or attitude of a speaker. It refers to identifying as well as classifying the sentiments that are expressed in the text source. Tweets are often useful in generating a vast amount of sentiment data upon analysis. These data are useful in understanding the opinion of the people about a variety of topics.

Friendster, MySpace, and even Facebook are the early frontiers of social media back before its marketing power was fully realized. Its simple purpose back then was to stay in touch with family or friends. Today, it’s a maze of consumer opinion – opinions that other consumers look to for guidance on which products to buy – or to avoid.
Consumer opinions have a lot of power and the only way to thrive in such an environment is to understand exactly what is driving consumer emotion and opinion.
This puts a small amount of power back in the hands of companies to a degree, as with this information you can solve problems, correct misconceptions, provide desired products and services, and interact with consumers on their terms. Without that information, you are sitting in a canoe without oars.
A social media sentiment analysis tells you how people feel about your brand online. Rather than a simple count of mentions or comments, sentiment analysis considers emotions and opinions. It involves collecting and analyzing information in the posts people share about your brand on social media. We have taken the concept and put the same to application with reference to Pfizer's Vaccine and analyze what the general consensus is about the vaccine. 

## Review of Existing methods and their Limitations
Sentiment Classification techniques can be roughly divided into Lexicon based approach, Machine Learning approach and hybrid approach. The Machine Learning approach applies famous ML algorithms and it uses linguistic features. The Lexicon based approach depends on a sentiment lexicon. Lexicon is a collection of known and precompiled sentiment terms. It is again divided into dictionary based approach and corpus based approach which use semantic or statistical methods to find sentiment polarity of the text. The Hybrid approach combines both the approaches and it is very common with sentiment lexicons playing a key role in a majority of methods. 
Sentiment analysis applications have range to almost every possible domain, from consumer products, services, and commercial services to societal events and political elections. Nearly all companies need Sentiment Analysis and Opinion Mining for different applications in different scenarios. In many product review websites like Yelp, Epinions reviews and feedbacks are explicitly asked in their web interfaces. Sentiment Analysis is not only limited to product reviews but expands it wing to many fields like political/governmental issues. Opinion Mining can increase capabilities of Customer Relationship Management (CRM) and Recommendation Systems by collecting positive and negative sentiments of the consumer. By using Sentiment Analysis techniques, wired systems displaying advertisements can detect web pages that contain sensitive content inappropriate for trailer placement. Companies are applying different marketing strategies like collecting opinions of the general public about the products and services. These sentiments can be mined using Sentiment Analysis for Business Intelligence. Not only the commercial market but government intelligence also uses opinion mining to monitor the negative communications over social media.

## Modules Description
- Acquiring Data set
We carefully handpicked a dataset from Kaggle in order to perform sentiment analysis on.

Completeness and accuracy are the minimum requirements for any dataset. In the absence of these characteristics, any final outcome is suspect of biases and wrong conclusions.

Any analysis relies on the initial dataset that we have, a Machine Learning algorithm, no matter how sophisticated is, depends on the quality of the data. For this reason, we need to invest time and effort to verify the reliability of the data before to start the process of transforming this data into valuable information for the business.


- Preprocessing Data
Data preprocessing is a data mining technique which is used to transform the raw data in a useful and efficient format. 
           Steps Involved in Data Preprocessing: 

1.Data Cleaning: 
The data can have many irrelevant and missing parts. To handle this part, data cleaning is done. It involves handling of missing data, noisy data etc. 

2. Data Transformation: 
This step is taken in order to transform the data in appropriate forms suitable for mining process. 

3. Data Reduction: 
Since data mining is a technique that is used to handle huge amount of data. While working with huge volume of data, analysis became harder in such cases. In order to get rid of this, we uses data reduction technique. It aims to increase the storage efficiency and reduce data storage and analysis costs. 

- Data Visualization
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

In the world of Big Data, data visualization tools and technologies are essential to analyze massive amounts of information and make data-driven decisions. The given data is visualized and a word cloud is made with all the Trending Hashtags.

- Data Modeling
Data Modeling is the process of analyzing the data objects and their relationship to the other objects. It is used to analyze the data requirements that are required for the business processes. The data models are created for the data to be stored in a database. The Data Model's main focus is on what data is needed and how we have to organize data rather than what operations we have to perform.

Data Model is basically an architect's building plan. It is a process of documenting complex software system design as in a diagram that can be easily understood. The diagram will be created using text and symbols to represent how the data will flow. It is also known as the blueprint for constructing new software or re-engineering any application.

- Sentiment Analysis
Sentiment analysis is contextual mining of text which identifies and extracts subjective information in source material, and helping a business to understand the social sentiment of their brand, product or service while monitoring online conversations. However, analysis of social media streams is usually restricted to just basic sentiment analysis and count based metrics. This is akin to just scratching the surface and missing out on those high value insights that are waiting to be discovered. All the tweets are analyzed by their respective sentiments.

## Implementation requirements

Requirements for implementation are:
Linux Operating System/Windows
Python Platform(Anaconda2,Spyder,Jupyter,Visual Studio Code)
NLTK package,
Modern Web Browser
Twitter API, Google API

## Contributors
- [Rachit Nigam] (https://github.com/Rachit747)
* [Vidushi Gupta](https://github.com/Vidushi-Gupta)
* [Abhimanyu Bhadauria](https://github.com/Mnayu)
* [Mudit Krishna](https://github.com/mewdit)

