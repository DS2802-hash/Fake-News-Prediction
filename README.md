#Fake News Detection
##Overview
This repository contains a Python script for detecting fake news using machine learning. The code employs the LogisticRegression and DecisionTreeClassifier models from scikit-learn for classification.

##Setup
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/fake-news-detection.git
cd fake-news-detection
Install Dependencies:

##bash
Copy code
pip install pandas numpy seaborn matplotlib scikit-learn
Dataset
The code uses two CSV files, fake.csv and true.csv, containing fake and true news data, respectively. Ensure these files are in the project directory.

##Usage
Run the fake_news_detection.py script to train the models and perform fake news detection. Ensure you have the necessary Python environment and dependencies installed.

bash
Copy code
python fake_news_detection.py
##Results
The script outputs classification reports for both the logistic regression and decision tree models, providing insights into accuracy, precision, recall, and F1-score. Additionally, manual testing results for a custom news article are displayed.

Feel free to explore and modify the code for further analysis or to use different models for fake news detection.
