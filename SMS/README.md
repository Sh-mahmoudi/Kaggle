# SMS Spam Collection Dataset

This project applies machine learning models to classify SMS messages as spam or ham (not spam) using the SMS Spam Collection dataset.


Data Source: [Kaggle-SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset/data)


The Jupyter notebook `SMS.ipynb` contains all data preprocessing, modeling, and evaluation steps.



**Preprocessing**

The data were split into training and test sets, and the text was converted into numeric features using CountVectorizer.

**Model Training & Evaluation**

Three classification models including: _Multinomial Naive Bayes_, _Logistic Regression_, and _Support Vector Machine (SVM)_ were compared. Each model was evaluated using accuracy scores and confusion matrices

**Token Analysis**

token frequencies were extracted for ham vs. spam, and ratios of word occurrence in spam vs. ham messages were computed.

The most spam-indicative tokens were identified.


**Results**

The models achieved high accuracy (~97–99%).

Naive Bayes was fast and produced the best generalization.
