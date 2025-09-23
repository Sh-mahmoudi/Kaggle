{
 "cells": [
  {
   "cell_type": "markdown",
   "id": "a982a73d",
   "metadata": {},
   "source": [
    "# SMS Spam Collection Dataset\n",
    "\n",
    "This project applies machine learning models to classify SMS messages as spam or ham (not spam) using the SMS Spam Collection dataset.\n",
    "\n",
    "\n",
    "Data Source: [Kaggle-SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset/data)\n",
    "\n",
    "\n",
    "The Jupyter notebook 'SMS.ipynb' contains all data preprocessing, modeling, and evaluation steps.\n",
    "\n",
    "\n",
    "\n",
    "**Preprocessing**\n",
    "\n",
    "The data were split into training and test sets, and the text was converted into numeric features using CountVectorizer.\n",
    "\n",
    "**Model Training & Evaluation**\n",
    "\n",
    "Three classification models including: _Multinomial Naive Bayes_, _Logistic Regression_, and _Support Vector Machine (SVM)_ were compared. Each model was evaluated using accuracy scores and confusion matrices\n",
    "\n",
    "**Token Analysis**\n",
    "token frequencies were extracted for ham vs. spam, and ratios of word occurrence in spam vs. ham messages were computed.\n",
    "\n",
    "The most spam-indicative tokens were identified.\n",
    "\n",
    "\n",
    "**Results**\n",
    "\n",
    "The models achieved high accuracy (~97–99%).\n",
    "\n",
    "Naive Bayes was fast and produced the best generalization."
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "name": "python",
   "version": "3.12.1"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}
