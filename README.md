# Sentiment-analysis-Google-playstore-app-reviews

- Sentiment analysis refers to the use of natural language processing, text analysis, computational linguistics, and biometrics to systematically identify, extract, quantify, and study affective states and subjective information.

- We have scraped 16000 reviews from Google app playstore from our desired applications. Please refer "Scraping Google playstore app reviews" repository for scraping the reviews

- Our project implements ML classification models using Logistic Regression, SVM Classifier, KNN Classifier, Naive Bayes, Random Forest Classifier, Decision Tree Classifier to predict the sentiment on the test dataset.

- In addition, we are improving the classifier by training the reviews dataset using the BERT (Bi-directional Encoding Representations from Transformers) transformer through Hugging Face.

## The model accuracy for the above models are stated below:

## ML Models (Validation accuracy):

- Multinomial Logistic Regression - 0.579047619047619

- Naive Bayes - 0.4552380952380952

- KNN Classifier - 0.36

- SVM - 0.7066

- Decision Tree Classifier - 0.6819

- Random Forest Classifier - 0.7187301587301588

## NLP Model:

- BERT (Training accuracy) - 0.9880036694658105

- BERT (Validation accuracy) - 0.8932655654383737

Obviously, BERT gave the best results on both train and validation datasets when we trained our model for 10 epochs. 

Furthermore, we are using FastAPI to build a web framework for our trained model and we are testing it with various reviews from the app store. The model has given really good results and once can enhance it further to improve the predicions.

Happy Coding!

