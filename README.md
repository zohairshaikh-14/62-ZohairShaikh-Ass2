Assignment 2: Sentiment Analysis on Electric Vehicles (EVs) 
1. Problem Statement 
Electric Vehicles (EVs) play a crucial role in India’s transition toward sustainable and eco-friendly 
transportation. Public opinion regarding EVs on social media platforms such as X (Twitter) includes a 
mix of positive sentiments (environmental benefits and innovation), neutral opinions, and negative 
concerns (charging infrastructure, cost, and range anxiety). 
The problem is to perform sentiment analysis on 100 public tweets and classify them into positive, 
negative, or neutral categories to understand the overall public outlook. 
2. Objective 
 To collect 100 tweets related to Electric Vehicles. 
 To manually label each tweet as positive, negative, or neutral. 
 To apply machine learning models such as: 
o Naïve Bayes 
o Support Vector Machine (SVM) 
o Logistic Regression 
 To evaluate and compare the performance of these models. 
 To identify the most effective classifier for sentiment analysis. 
4. Dataset Description 
 Source: Tweets collected using keywords like “EV India,” “Charging Stations,” and “Electric 
Mobility”. 
 Features: 
o Tweet (raw text) 
o Sentiment (manually labeled) 
 Dataset Size: 100 tweets 
5. Methodology 
4.1 Data Preprocessing 
 Removed special characters such as URLs, hashtags, and mentions (@). 
 Converted all text to lowercase for uniformity. 
 Removed stopwords to retain meaningful words contributing to sentiment. 
4.2 Data Splitting 
 Training Data: 80% (80 tweets) 
 Testing Data: 20% (20 tweets) 
4.3 Feature Extraction 
 Used TF-IDF Vectorization to convert textual data into numerical form. 
4.4 Model Building 
The following machine learning models were trained: 
 Multinomial Naïve Bayes 
 Support Vector Machine (SVM) 
 Logistic Regression 
4.5 Evaluation Metrics 
 Precision 
 Recall 
6. Results 
Model Performance Comparison 
Classifier 
Naïve Bayes 
SVM 
Precision Recall 
1.0 
1.0 
Logistic Regression 1.0 
1.0 
1.0 
Observations 
 All three models achieved perfect precision and recall (1.0). 
 The dataset had clear and distinguishable sentiment patterns. 
 Models were able to classify sentiments without error on the test data. 
6. Insights 
 The high accuracy suggests that the dataset was well-structured and clearly labeled. 
 Positive tweets mainly reflected environmental benefits and innovation. 
 Negative tweets focused on charging infrastructure and cost concerns. 
 Neutral tweets provided informational or mixed opinions. 
7. How to Run the Program 
# Install required libraries 
pip install pandas scikit-learn nltk 
# Open and run the Jupyter Notebook 
RollNo_Name_Assignment2.ipynb 
8. Conclusion 
All three machine learning models—Naïve Bayes, SVM, and Logistic Regression—performed equally 
well, achieving 100% accuracy on the test dataset. While all models are effective, SVM is generally 
preferred for handling high-dimensional text data. 
The analysis indicates that public sentiment towards Electric Vehicles in India is largely 
distinguishable, highlighting both enthusiasm for innovation and concerns regarding infrastructure. 
9. Student Details 
 Name: Mohammad Zohair Shaikh 
 UIN: 231A043 
 Roll No: 62 
 Class: TE (2025–26) 
 Course: Data Analytics and Visualisation
