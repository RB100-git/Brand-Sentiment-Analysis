# Brand-Sentiment-Analysis
## Abstract
The automotive industry in India is the fifth-largest in the world as per 2020 statistics. The usage and demand of vehicles are getting increased day by day. Similarly, the users’ requirements are also getting transformed. These different user requirements are giving a great scope of improvement to the automotive industry. Hence, the market is also becoming competitive. Automotive companies are trying to satisfy their customers by releasing new car models or improving the existing models as per customers’ requirements.
Now a days, user generated reviews are freely available on different websites. Companies to increase their competitive advantages keep an eye on their competing companies and closely analyze the data that are generated by their customers on their social media sites or websites. Text-based Sentiment Analysis is now widely used, e.g. for those car brands perception or customer satisfaction assessment, as Machine Learning approaches are able to learn rich text representations from data that can be applied to sentiment classification. Sentiment analysis alludes to the utilization of Natural Language Processing (NLP), text mining, computational linguistics, and bio measurements to methodically recognize, extricate, evaluate, and examine emotional states and subjective information. It is a great way to analyze the reviews of consumers through the available data of different websites. It would be also helpful for automobiles companies in strategy making.

In this project, a dataset has been selected which mainly contains reviews on various car models by the car users, along with all the required details of the cars. This dataset has been used as input and then it has been processed using various tools and methods to obtain our expected results. The goal of this project is to classify these reviews into sentiments (positive/ negative/ neutral) by using different supervised machine learning techniques on the collected data. As a result, we expect to do review-level categorization of review data with promising outcomes.
![image](https://user-images.githubusercontent.com/102472369/171352855-6f3a4c2d-d325-4833-a4fd-9bd9a5af2568.png) ![image](https://user-images.githubusercontent.com/102472369/171353931-51a40a2f-3b78-4260-bf10-9de6aab76202.png)


## Introduction
The automotive industry of India is the fourth largest in the world as per 2021 statistics. In 2022, India became fourth largest country in the world by doing the valuation of automotive industry. Currently India's automobile industry is worth of more than 100 billion USD and contributes 8% of the India's total export and accounts for 2.3% of country's GDP. India is a prominent auto exporter and has strong export growth expectations for the near future. In addition, several initiatives by the Government of India and major automobile players in the Indian market are expected to make India one of the leaders in the four-wheeler market in the world by 2022.
Automobile or vehicle has become a part of our daily life. Usage and demand of cars are getting increased day by day. If we see the number of vehicles in operation across India, we will come to know that the total number of vehicles in fiscal year 2019 stood at 295.8 million. Road travel seemed to be the preferred choice in India with over 60 percent of the population who used personal or shared vehicles for commute. Not only the public travel, the industrial movement of goods via roads had also been increased with well over two billion metric tons of freight transported through roads in financial year 2017 [Fig 1]

![image](https://user-images.githubusercontent.com/102472369/171356232-71319dc4-1d6d-4458-ba2f-73f7d0250866.png)
###### *Fig 1: Number of vehicles in operation across India from financial year 1951 to 2019(in millions)*



Earlier, the main objective of buying vehicles was to commute from one place to another place. So, people were purchasing the vehicles which were providing good mileage in a fairly reasonable price. But today’s scenario is different. Apart from mileage, users want customized cars according to their needs. Now people are also considering comfort, shape, size, seating capacity, safety, music system and many more things as their selection criteria to purchase a car. Earlier, people had financial constraints. But now, everyone’s disposable income has increased and banks are also there to give car loans. So, situation has improved a lot and so car owners. In fiscal year 2019, there were around 225 registered vehicles for every thousand people across India. There was a constant increase for the past two decades. Now vehicle companies are also facing huge competition among them. They are also introducing various new models into the market to satisfy their customer needs. To understand the customers’ need it is important to get a feedback or review of car by the car owner or user. If companies do analysis on their customers’ review, then it will always be beneficial for companies. The reviews on specific car models will give future scope of improvement.
So, in this project, a dataset has been selected which mainly contains reviews on various car brands by the car users, along with all the required detailed specifications related to cars. After that, we have tried to understand the customers’ feelings associated with every review and based on it to build a model to predict customers’ sentiments or feelings. 


## Objective of the Project
The main objective of this project is to analyse the automobile manufacture details and perform Sentiment Analysis thereafter using the Machine Learning techniques. The information is fetched from a reputed car website through scraping. The automobile dataset mainly contains of different types of detailed specifications related in automobile vehicles like **Brand, Car name, Variant name, Model name, Mileage(kmpl), Fuel type, No. of Seat, No. of cylinder, Body type, Transmission type, Fuel tank capacity, Boot Space, Engine Displacement, Ex-Showroom Price . The dataset also has the details like review, review date** etc. so that Text Analysis can be performed over there. 
The paper is organized as follows:

☛In the first section, *Exploratory Data Analysis (EDA)* has been conducted to grasp and explore the structure of information. It also helped us to get a perception about each and every feature of different car brands like **Hyundai, Mahindra, Tata, Toyota, Maruti, Renault, Volkswagen, Datsun, Nissan, Ford, Honda**.

☛In the second section, we have implemented Natural Language Processing (NLP) for sentiment classification. In this stage, Data cleansing process helped us to get the cleaned data without any punctuations, digits, URLs, emoticons etc.

☛At this level, data has been splitted into train and test so that, with the assistance of classification model, Reviews could be categorized as “positive”, “negative” or “neutral”. 

☛To find the answer, “which car brand is most popular among the online viewers at the base of sentiment analysis?”,  the rest of the paper is visualized in graphical form with specific informations about the most discussed brand in the reviews of our collected dataset.


## System Design
We are using python for data analysis. It is simple to learn. It has rich sets of libraries. Data handling capacity are much higher. It is used as open source language. It can run on any platform. It can transfer the process from one platform to another. It is easy to read. The developer can understand the code. It offers a variety of libraries and some of them uses great visualization tool. Visualization process can make it easier to create the clear report.

**Jupyter**: The Jupyter Notebook is an open-source web application that permits you to form and share documents that contain live code, equations, visualizations and narrative text. Uses include: data cleaning and transformation, numerical simulation, statistical modeling, data visualization, machine learning, and far more. Jupyter Notebook is our surroundings used for computation.
 
**Numpy**: Numpy is a math library to figure with n-dimensional arrays in Python. It enables you to try and do computation efficiently and effectively. It's better than regular python due to its amazing capabilities.

**Matplotlib**: Matplotlib is a plotting package that provides 2D plotting as well as 3D plotting. 

**Pandas**: Pandas library could be a very high-level python library that has high-performance, easy to use data structures. It's many functions for data importing, manipulation and analysis. specifically, it offers data structures and operations for manipulating numerical tables and statistic. 

**Seaborn**: Seaborn could be a Python data visualization library supported matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphics. For a quick introduction to the ideas behind the library, you'll be able to read the introductory notes. 

**Scikit-Learn**: The sklearn library contains a lot of efficient tools for machine learning and statistical modeling including classification, regression, clustering and dimensionality reduction.

**NLTK**: NLTK (*Natural Language Toolkit*) is a toolkit build for working with NLP in Python that provides various text processing libraries.


## Methodology and Implementation
✍**DATA COLLECTION:** 
The dataset has been collected through Web Scraping. **Parsehub**, a web-scraping tool has been utilized here to work on popular websites interacting with JavaScript and Ajax. In the application, there are ready-made templates that are pretty flexible and use machine-learning to grasp complex hierarchies.

**Parsehub**: *https://www.parsehub.com/*

This is a dataset about different car brands, which has been taken from **CarDekho** website.

 **CarDekho**: *https://www.cardekho.com/*

✍**ABOUT  THE  DATASET** : 
The dataset contains Brand, Car Name, Variant Name, Model Name, Mileage in kmpl, Fuel Type, Seat, No of  Cylinder, Body Type, Transmission Type, Fuel Tank Capacity, Boot Space, Engine Displacement, Ex-Showroom Price in Delhi (in Lakh), Rating Out of 5, Review Title, Review, Review Date, No of Views on Review.
Description of columns in the file:

Brand - Name of the brands i.e, Datsun, Toyota etc.

Car Name - Name of the cars of each brand

Variant Name - Different trims within a single car model i.e, Swift is a car model by Maruti Suzuki.

Model Name - Combination of brand, car and variant name.

Mileage in kmpl - The distance covered by the vehicle per unit fuel.

Fuel Type - Types of fuel i.e, petrol, diesel etc.

Seat - No. of seats. 

No of Cylinder - cylinder counts.

Body Type - Categorisation of a vehicle based on its design, shape and space i.e, SUV, Hatchback etc.

Transmission Type - Types of transmision i.e, automatic, manual etc.

Fuel Tank Capacity - The tank's fuel usable capacity.

Boot Space - Luggage capacity.

Engine Displacement - The total volume of all the cylinders in an engine.

Ex-Showroom Price in Delhi (in Lakh) - The price of the car without any additional RTO, Road Tax, and insurance payments.

Rating Out of 5 - Rating of the car.

Review Title - Descriptive heading of review texts.

Review - Text of the review.

Review Date - Date of the review.

No of Views on Review - View counts of the reviews.


✍**DATA CLEANING:** 
It is the process of detecting the corrupt data, removing the irrelevant parts of the data and replacing the correct data. The actual process of data cleaning is to remove the error and validating the data. Data can be cross checked to remove the error. Issue can be resolved by validating the data.

✍**STATISTICAL  ANALYSIS:** 
The Summary Statistics of Automobiles specification is shown in fig  . Various specification parameters such as Mileage (kmpl), Seat, No of Cylinder, Fuel Tank Capacity, Boot Space, Engine Displacement, Ex-Showroom Price in Delhi (in Lakh), Rating out of 5 were taken into consideration during experiments. There were 5791 entries received after data cleaning process except Boot Space as there were 77 missing values present in the column.

In terms of Descriptive Statistical Analysis, the describe function automatically computes basic statistics for all continuous variables. Here NaN values have been filled with the mean value which is calculated by taking the sum of all the values in the Boot Space divided by total number of values present in that column.


✍**EXPLORATORY DATA ANALYSIS:**
Primarily, Exploratory Data Analysis (EDA) is an approach to see what the data can communicate us away from the formal modeling or hypothesis testing task. EDA  refers to the critical process of performing initial investigations on data so on discover patterns to spot anomalies, to test hypothesis and to test assumptions with the assistance of summary statistics and graphical representations. It helps to analyze the data sets to summarize their statistical characteristics focusing on four key aspects, like, measures of central tendency (comprising of the mean, the mode and the median), measures of spread (comprising of standard deviation and variance), the shape of the distribution and the existence of outliers.
Now it’s time to explore our data and find about it……

***Box Plots***: 

A good graphical image of the concentration of data can be represented by the use of box plot. It shows the central tendency, symmetry, skew and outlier. It can be constructed from five values: the minimum, the first quartile, the median, the third quartile and the maximum value. These values are compared to show how close other data values are to them.

We have done the box plot between: 

1.	Brand and Mileage 
2.	Brand and Fuel Tank Capacity.
3.  Brand and Boot Space.
4.  Brand and Engine Displacement.

***Bar plots***:
A bar plot represents an estimate of central tendency for a numeric variable with the height of each rectangle and provides some indication of the uncertainty around that estimate using error bars.

We have done the bar plot between: 

1.	Mileage of different brands and their fuel type.
2.	Mileage of each brands and their body type(individually).

***Scatter plots:***
It is a type of plot where Cartesian coordinate is used to display the values between two variables for a set of data.

We have done the scatter plot between: 
1.	Mileage and Fuel Tank Capacity.
2.  Fuel Tank Capacity and Car price.
3.  Mileage and Engine Displacement.
4.  Engine Displacement and Car price.


✍**IMPLEMENTATION OF SENTIMENT ANALYSIS:**

***Text Processing***

Before proceeding into sentiment classification, reviews of the dataset must be preprocessed in order to perform any data mining functionality. Text Preprocessing involves the following tasks: 

*Removing URLs*: Normally URLs doesn't contribute to investigate the sentiment within the informal text. For instance, consider the sentence “I wanted to buy this car but I have logged in to www. happycarsflorida.com/ as I’m bored” actually the above sentence is negative but due to the presence of the word ‘happy’ it should become neutral or positive and it’s a false prediction. So as to avoid this type of failures we must employ a method to get rid of URLs.

*Removing Special Characters*:  Special characters like '\[.*?\]', ''should be removed so as to get rid of discrepancies during the assignment of polarity. For instance, “it’s good:” if the special characters don't seem to be removed sometimes the special characters may concatenate with the words and make those words unavailable within the dictionary. So as to beat this we remove special characters. 

*Removing Stopwords:*  Stop words are available in abundance in any human language. By removing these words, we remove the low-level information from our text in order to give more focus to the important information. Removal of stop words definitely reduces the dataset size and thus reduces the training time due to the fewer number of tokens involved in the training. But general Natural Language Toolkit (nltk) stop words contains words like not, hasn't, wouldn’t which actually conveys a negative sentiment. If we remove that it will end up contradicting the sentiments. So we have curated the stopwords which doesn't have any negative sentiment or any negative alternatives.

*Tokenizing*:  A tokenizer breaks natural language text into chunks of information that can be considered as discrete elements. The token occurrences in a document can be used directly as a vector representing that document. These tokens further help in understanding the context by analysing the sequence of words or developing the model for the NLP.
![image](https://user-images.githubusercontent.com/102472369/171434883-c72b644e-afa0-4fae-b240-f9b9fa91d43a.png)
###### *Fig 2: Steps for Text Processing*

***Frequency Analysis***

*WordCloud:*
Word Cloud may be a data visualization technique used for representing text data during which the dimensions of every word indicates its frequency or importance. Word clouds are useful in analyzing any kind of text data. Word clouds are more than just a visual representation of words; they can have important applications to a variety of different types of assessments. Typically, a word cloud takes the most frequently used words and displays them in an appealing visual representation that identifies key words in different sizes and colours based on the frequencies. By examining frequencies in a word cloud, an instructor can look for specific patterns of words and phrases, or the shortage thereof, in text data. 

*N-gram Analysis (Unigram, Bigram, Trigram):*
N-grams are continuous sequences of words or symbols or tokens in a document. In technical terms, they can be defined as the neighbouring sequences of items in a document. ’n’ is just a variable that can have positive integer values including 1,2,3 and so on. ’n’ basically refers to multiple. When n=1, it is said to be a unigram, when n=2 it is said to be a bigram and when n=3 it is said to be a trigram.

***Text Vectorization:***
The reason we need Text Vectorization is to help correct for words like “of”, “as”, “the”, etc. since they appear frequently in an English corpus. Thus by taking inverse document frequency, we can minimize the weighting of frequent terms while making infrequent terms have a higher impact. Term Frequency -Inverse Document Frequency(TFIDF) is a technique to quantify a word in documents, we generally compute a weight to each word which signifies the importance of the word in the document. This method is a widely used technique in Information Retrieval and Text Mining. 

Here we've splitted as Bigram and considered their combined weight for our data. Also we've taken only the top 5000 words from the reviews.


✍**SENTIMENT CLASSIFICATION ALGORITHM:**

*Predictor Variable* - One or more variables that are used to determine(Predict) the 'Target Variable'.
Top 5000 words taken as tokenized form, is our Predictor Variable.

*Target Variable* - A variable that needs to be predicted is a target variable.
Sentiment classes i.e 'positive', 'negative, and 'neutral', is our Target Variable.

The data has been used to train the classifier that we had built for the model. We trained our classifier from around 80% of the data and then we tested it with the remaining 20% to check that trained classifier was working properly or not.

![image](https://user-images.githubusercontent.com/102472369/171465801-c18fd999-2028-4c1b-a56b-6a8429d21058.png)
###### *Fig 3: Sample tokens of reviews with classes*
To classify reviews in different sentiment classes (positive, negative and neutral), we have used six in-built classifiers of scikit learn library in python, those are:

Random Forest Classifier,                          Logistic Regression,                      Decision Tree Classifier,
KNeighbors Classifier,                                      SVC,                             Naïve-Bayes Classifier 

*Model Selection*:

Here we have done cross validaton by using all of the classification algorithms first to select the best performing model. 




## Results
The ultimate outcome of this dataset after review analysis is that, the machine is capable of judging whether an entered sentence bears positive response or negative response.
To discuss about the classification report, it’s needed to know about Precision, Recall and F1 Score.
Precision (also called positive predictive value) is the fraction of relevant instances among the retrieved instances, while Recall (also known as sensitivity) is the fraction of relevant instances that have been retrieved over the total amount of relevant instances. Both precision and recall are therefore based on an understanding and measure of relevance. [Fig 4]
![image](https://user-images.githubusercontent.com/102472369/171466140-564ffb9b-a72e-4a72-9f45-94f95f7aec09.png)
###### *Fig 4: Presision and Recall from relevant and retrieved documents*

•	Precision, which indicates how many of the items that we identified were relevant, is 

true positive / (true positive + false positive).

•	Recall, which indicates how many of the relevant items that we identified, is 

true positive /( true positive + false negative).

F1 score (also F-score or F-measure) is a measure of a test's accuracy. It considers both the precision and the recall of the test to compute the score. The F1 score is the harmonic average of the precision and recall, where an F1 score reaches its best value at 1 (perfect precision and recall) and worst at 0. [Fig 5]

![image](https://user-images.githubusercontent.com/102472369/171466685-94b6b4f9-0eee-440e-bdce-3d232a23d2d3.png)
###### *Fig 5: F1 Score evaluation*

*Confusion Matrix*:
The Confusion matrix of evaluation is also calculated. It is thus capable of judging an externally written review as positive, negative or neutral. 

The Confusion Matrix Format is as follows: [Fig 6]
![image](https://user-images.githubusercontent.com/102472369/171543643-d83a3fd8-a510-4291-a3bc-08562b6f4c52.png)
###### *Fig 6: Format of Confusion Matrix*

*ROC-AUC curve*:

In statistics, a receiver operating characteristic curve, i.e. ROC curve, is a graphical plot that illustrates the diagnostic ability of a classifier system as its discrimination threshold is varied. The Total Operating Characteristic (TOC) expands on the idea of ROC by showing the total information in the two-by-two contingency table for each threshold. ROC gives only two bits of relative information for each threshold, thus the TOC gives strictly more information than the ROC. When using normalized units, the area under the curve (often referred to as simply the AUC) is equal to the probability that a classifier will rank a randomly chosen positive instance higher than a randomly chosen negative one (assuming 'positive' ranks higher than 'negative').


## Conclusion and Future Scopes
*Conclusion*:

Sentiment analysis is one of the most shining field of text and data mining in numerous sectors. It paints a clear picture of the most important issues, allowing us to automate decisions based on large amounts of data rather than pure intuition. This article focuses on a typical Brand Sentiment Analysis model consisting of four core steps, namely Exploratory Data Analysis (EDA), Review analysis, Sentiment Classification, and Sentiment distribution of the top most brand according to the user ratings.  We applied the Logistic Regression for sentiment classification. Our system will provide better and efficient solution to the cars of different brands’ business strategy. Furthermore, we concluded the insights of the sentiment distribution of the most wanted car brand according to the online users and how they compare the other brands while making a decision of brand. Sentiment analysis is an emerging research area in text mining and computational linguistics, and has attracted considerable research attention in the past few years. Future research shall explore sophisticated methods for opinion and product feature extraction, as well as new classification models that can address the ordered labels property in rating inference. Applications that utilize results from sentiment analysis are also expected to emerge in the near future.

*Future Scopes*:

Data analysis on Automobile analytics allows companies to form decisions supported performance of their manufacture products. The analysis report of our model induces relevant information about the vehicles to the car companies as well. The accuracy is extremely questionable during this case. So, with the assistance of our model, the accurate information of the vehicles can be determined precisely. As we concluded the insights of the sentiment distribution of the most wanted car brand according to the online users and how they compare the other brands while making a decision of brand, it would be also helpful for automobiles companies in strategy making.






  












