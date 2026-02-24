# FUTURE_ML_02
This is my 2nd task of my internship (Future Interns) where I built a Support Ticket Classification and Priority Prediction System using Machine Learning and Natural Language Processing (NLP) in Google Colab using Python.

In this project, I worked with real customer support ticket data and built a Machine Learning model that can automatically:
Classify support tickets into categories
Predict ticket priority levels
Help businesses handle support requests faster
Project Work Included

In this project I have done:
Data loading and cleaning
Removing missing values
Text preprocessing and cleaning

Converting text into numerical format
Feature extraction using TF-IDF
Training Machine Learning models
Category prediction of support tickets
Priority prediction of support tickets
Model evaluation using accuracy and classification metrics
How the System Works
The system reads the ticket description written by customers and automatically predicts:

Ticket Category
Examples:
Technical Issue
Billing Inquiry
Product Inquiry
Cancellation Request

Ticket Priority
Examples:
High
Medium
Low
The ticket text is cleaned and processed, then converted into numerical values using TF-IDF Vectorization, and Machine Learning models are used to predict category and priority.

Tools and Technologies Used
Python
Google Colab
Pandas
NLTK
Scikit-learn
TF-IDF Vectorizer

Logistic Regression
Dataset

Dataset used for this project is a Customer Support Ticket Dataset from Kaggle.
Dataset includes:
Ticket Description
Ticket Type
Ticket Priority
Customer Information
The dataset was downloaded in CSV format and used for training Machine Learning models.
Project Output

The system can take a new support ticket and automatically predict:
Example:
Input Ticket:"My payment was deducted but order not confirmed"
Output:Category → Billing Inquiry
Priority → High

Conclusion
This project shows how Machine Learning can help automate customer support systems by automatically categorizing and prioritizing support tickets.
This helps businesses:
Reduce manual work
Respond faster to customers
Identify urgent problems quickly
Improve customer support efficiency
