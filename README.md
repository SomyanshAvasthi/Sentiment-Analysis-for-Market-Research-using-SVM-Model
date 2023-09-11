# Importance of Sent. Analysis in Market Research 
•	Sentiment analysis is a powerful tool for market research as it provides insights into customer attitudes, preferences,	and behavior. 

•	It helps to identify trends, patterns, and areas of improvement, which can be used to make informed business decisions.


![image](https://github.com/SomyanshAvasthi/Sentiment-Analysis-for-Market-Research/assets/107310391/d54df769-4652-4825-8db9-ff59f79858e8)
# Methodology
After data collection (Surveys, Request to APIs, Experiments, Web Scrapping, etc )the following was the methodology adopted:-
1.	Importing necessary libraries: We import the required libraries like pandas, NumPy, and scikit-learn to load and preprocess the dataset and perform sentiment analysis.
2.	Loading the dataset: We load the dataset using pandas, which contains reviews of customers who have purchased Amazon Alexa products from Amazon.
3.	Exploring the dataset: We display the first five rows of the dataset to get an overview of the data.
4.	Selecting the required columns: We select only the required columns (verified_reviews and feedback) from the dataset.
5.	Checking for null values: We check if there are any null values in the dataset.
6.	Dropping null values: We drop the rows with null values in the verified_reviews column.
7.	Converting to string: We convert the data type of the verified_reviews column to string.
8.	Checking feedback distribution: We check the distribution of feedback (positive/negative) in the dataset using a count plot.
9.	Plotting review length distribution: We plot the distribution of review lengths for positive and negative feedback using histograms.
10.	Defining tokenization function: We define a function to tokenize the reviews by removing special characters and converting to lowercase.
11.	Defining stop words: We define a list of stop words to remove from the reviews.
12.	Defining function to remove stop words: We define a function to remove stop words from the tokenized reviews.
13.	Defining function to remove numbers: We define a function to remove numbers from the tokenized reviews.
14.	Defining function for lemmatization: We define a function to perform lemmatization on the tokenized reviews.
15.	Preprocessing the data: We preprocess the reviews by applying the functions defined in the previous cells.
16.	Word cloud visualization: We visualize the most common words in positive and negative reviews using a word cloud.
17.	Training a support vector machine (SVM) model: We train an SVM model on the preprocessed reviews and feedback labels.
18.	Evaluating the model: We evaluate the accuracy of the SVM model and generate a classification report. We also visualize the report using a heatmap.


# Results
•	The sentiment analysis model built on this dataset shows promising results with an overall accuracy of 94%. 

•	The precision and recall scores for positive and negative classes are also high, indicating that the model is able to classify the reviews with good accuracy.

•	The word cloud generated for positive and negative reviews shows the most commonly occurring words in the respective categories.

•	Overall, the model built on this dataset can be used by companies to analyze customer reviews and improve their product accordingly.

# Analysis Preferred to Validate Sent. Analysis
•	Human Annotation: Use humans to manually label a sample of text data and compare the results to the sentiment analysis output.

•	Precision, Recall, and F1 Score: Use metrics to evaluate the model's accuracy and performance.

•	Confusion Matrix: Use a table to evaluate the model's true positive, true negative, false positive, and false negative rates.

•	Cross-validation: Partition data into multiple sets to test the model's accuracy on new data.

•	A/B Testing: Compare the output of two different sentiment analysis models or techniques on the same data.

# Conclusions
•	We performed sentiment analysis on Amazon Alexa product reviews using machine learning techniques.

•	The dataset consisted of 3150 reviews, out of which 2578 were positive and 572 were negative.

•	We performed data cleaning, text preprocessing, and feature engineering on the data to prepare it for machine learning models.

•	We used the LinearSVC model for sentiment analysis and achieved an accuracy of 95.4%.

•	The precision, recall, and F1 score for both classes were also high, indicating good performance of the model.

•	We created a wordcloud for both positive and negative reviews to get an insight into the frequently occurring words in both types of reviews.

•	Based on the wordclouds, we can infer that positive reviews have words such as "love," "great," and "easy," whereas negative reviews have words such as "disappointed," "problem," and "return."
![image](https://github.com/SomyanshAvasthi/Sentiment-Analysis-for-Market-Research/assets/107310391/a9cf4473-b807-498c-a9eb-4c37716d4ef3)
![image](https://github.com/SomyanshAvasthi/Sentiment-Analysis-for-Market-Research/assets/107310391/536b8678-4a0d-4146-b6ef-7055c664ea71)
![image](https://github.com/SomyanshAvasthi/Sentiment-Analysis-for-Market-Research/assets/107310391/fd401da6-6ecc-4510-a4f4-541161b193af)

