# SENTIMENT-ANALYSIS-WITH-NLP

COMPANY : CODTECH IT SOLUTIONS

NAME : ANJURU BALAJI SHREYANSH

INTERN ID : CTIS8550

DOMAIN : MACHINE LEARNING

DURATION : 8 WEEKS

MENTOR : NEELA SANTHOSH


DESCRIPTION:

Sentiment Analysis is one of the most important applications of Natural Language Processing (NLP) that is used to identify and classify opinions or emotions expressed in textual data. It helps determine whether a piece of text contains a positive, negative, or neutral sentiment. Businesses and organizations widely use sentiment analysis to understand customer feedback, product reviews, social media comments, and user opinions. By analyzing customer sentiments, companies can improve their services, products, and overall customer satisfaction.
In this project, a Sentiment Analysis model is implemented using Natural Language Processing techniques along with Machine Learning algorithms in Python. The main objective of the project is to analyze customer reviews and automatically predict the sentiment expressed in the text. The implementation uses TF-IDF Vectorization for feature extraction and Logistic Regression for classification. The project demonstrates the complete workflow of text preprocessing, feature engineering, model training, prediction, and performance evaluation using the Scikit-learn library.
The implementation process begins with importing the required Python libraries such as Pandas, NumPy, Matplotlib, Scikit-learn, and NLTK. These libraries are used for data manipulation, text processing, visualization, and machine learning operations. After importing the libraries, a dataset containing customer reviews and sentiment labels is loaded into the program. The dataset generally contains text reviews as input data and sentiment categories such as positive or negative as output labels.
Before training the model, the textual data must be cleaned and preprocessed because raw text often contains unnecessary symbols, punctuation marks, stop words, and inconsistent formatting. Text preprocessing includes converting text to lowercase, removing punctuation, eliminating stop words, tokenization, and stemming or lemmatization. These preprocessing techniques help improve the quality of the textual data and increase the accuracy of the machine learning model.
Once preprocessing is completed, TF-IDF (Term Frequency–Inverse Document Frequency) Vectorization is applied to convert textual data into numerical format. Machine learning algorithms cannot directly process text data, so TF-IDF transforms the words into weighted numerical vectors based on their importance in the dataset. This method helps identify significant words while reducing the impact of commonly occurring but less meaningful terms.
After vectorization, the dataset is divided into training and testing sets using the train_test_split() function. The training data is used to train the Logistic Regression model, while the testing data is used to evaluate the model’s performance on unseen reviews. Logistic Regression is a supervised machine learning algorithm commonly used for text classification tasks because of its simplicity, efficiency, and high performance in binary classification problems.
The model is trained using the fit() method and predictions are generated using the predict() function. The predicted sentiments are then compared with the actual sentiments to evaluate the performance of the model. Different evaluation metrics such as accuracy score, confusion matrix, precision, recall, and F1-score are used to measure the effectiveness of the classifier.
Finally, the project showcases how NLP and machine learning techniques can be combined to perform automated sentiment analysis on customer reviews. The implementation demonstrates the practical use of TF-IDF vectorization and Logistic Regression in solving real-world text classification problems. This project provides a clear understanding of data preprocessing, feature extraction, machine learning modeling, and sentiment evaluation using Python and Scikit-learn.



OUTPUT:

<img width="1109" height="380" alt="Image" src="https://github.com/user-attachments/assets/2b3d8746-83df-4adb-8df7-6f1066cb1b56" />

<img width="1247" height="386" alt="Image" src="https://github.com/user-attachments/assets/631a8f0f-fcb7-4670-9092-5e02ae1e881d" />

<img width="1012" height="145" alt="Image" src="https://github.com/user-attachments/assets/2073baf9-1937-42f9-982f-457942964d69" />

<img width="1001" height="285" alt="Image" src="https://github.com/user-attachments/assets/ac73a29c-a6c4-404d-8b32-ac358e6fc396" />

<img width="1056" height="833" alt="Image" src="https://github.com/user-attachments/assets/3cb879f8-9589-41e2-9677-ef5002f686f2" />

<img width="992" height="519" alt="Image" src="https://github.com/user-attachments/assets/05e6455d-25bf-42cc-8ee6-ef9febad2039" />

