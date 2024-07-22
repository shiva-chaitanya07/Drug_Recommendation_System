Drug Recommendation System
📋 Table of Contents
Introduction
Features
Tech Stack
Installation
Usage
Machine Learning Algorithms
Problem Formulation
Importance of Machine Learning
Learnings
Further Improvements
Conclusion
Future Scope
📝 Introduction
The Drug Recommendation System leverages machine learning algorithms to predict the sentiment of drug reviews, providing recommendations based on these sentiments. By analyzing various factors such as review content, the system aids in determining the effectiveness and approval of drugs. Utilizing a classification system, this project aims to assist users in making informed decisions about drug usage through the analysis of user reviews.

✨ Features
Sentiment analysis of drug reviews
Drug recommendation based on review sentiment
User-friendly web interface built with Django
Data handling with Pandas
Model training with Scikit-learn
Bar chart visualization of model accuracies
🛠️ Tech Stack
Django: Web framework
MySQL: Database
Pandas: Data manipulation and analysis
Scikit-learn: Machine learning library
Openpyxl: Excel file handling
xlwt: Excel writing
Deployment: XAMPP server
🚀 Installation
Follow these steps to set up the project on your local machine:

Clone the repository:

bash
Copy code
git clone https://github.com/shiva-chaitanya07/Drug_Recommendation_System.git
cd Drug_Recommendation_System
Create and activate a virtual environment:

bash
Copy code
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
Install the required packages:

bash
Copy code
pip install -r requirements.txt
🏃 Usage
To run the project, use the following command:

bash
Copy code
python manage.py runserver
Open your web browser and navigate to http://127.0.0.1:8000/ to access the application.

📚 Machine Learning Algorithms
This project employs several machine learning algorithms to accurately predict drug recommendation outcomes:

(a) Logistic Regression

Logistic Regression is a statistical model that in its basic form uses a logistic function to model a binary dependent variable. It's suitable for classification tasks.
(b) Support Vector Machine (SVM)

SVM is a supervised learning model that analyzes data for classification and regression analysis. It works well for high-dimensional spaces.
(c) Stochastic Gradient Descent (SGD) Classifier

SGD Classifier implements regularized linear models with stochastic gradient descent learning, which is particularly efficient for large datasets.
(d) Naive Bayes

Naive Bayes is a family of simple probabilistic classifiers based on applying Bayes' theorem with strong independence assumptions between the features.
(e) Decision Tree

Decision Tree is a non-parametric supervised learning method used for classification and regression. It splits the data into subsets based on the most significant attributes.
🤔 Problem Formulation
The Drug Recommendation System addresses the challenge of identifying effective drugs based on user reviews. With numerous reviews available online, it becomes crucial to efficiently analyze and classify these reviews to provide meaningful recommendations. This project aims to analyze drug review data and develop predictive models to classify the sentiment of reviews, thereby assisting users in making informed decisions.

Key Challenges:

Identifying effective drugs from user reviews.
Developing predictive models to assess the sentiment of reviews.
Providing reliable drug recommendations.
🤖 Importance of Machine Learning
Machine learning plays a crucial role in this project for several reasons:

Accuracy: Machine learning models can analyze vast amounts of data to make accurate predictions, reducing human error.
Efficiency: Automating the sentiment analysis process with machine learning speeds up decision-making, saving time for users.
Scalability: Machine learning models can handle increasing amounts of data without significant performance degradation, making them suitable for growing datasets.
Data Insights: By analyzing patterns in data, machine learning provides valuable insights that can help refine drug recommendations and improve user satisfaction.
📚 Learnings
Working on this project provided several valuable learnings:

Understanding the integration of machine learning models in a web application.
Handling and preprocessing data using Pandas.
Training and evaluating machine learning models with Scikit-learn.
Developing a Django web application to serve the machine learning model.
🔧 Further Improvements
Here are some areas for further improvement:

Model Enhancement: Improve the accuracy of the prediction model by exploring advanced machine learning algorithms.
User Interface: Enhance the UI for a better user experience.
Data Visualization: Incorporate data visualization tools to provide better insights into the data.
Deployment: Deploy the application on a cloud platform for wider accessibility.
🏁 Conclusion
The Drug Recommendation System is a valuable tool for users to make informed decisions about drug usage. By leveraging machine learning algorithms, this project aims to enhance the accuracy and efficiency of drug recommendations, ultimately benefiting users. Through continuous analysis and refinement of drug review data, the system can provide more reliable recommendations and improve overall user satisfaction.

🌟 Future Scope
Advanced Techniques: Implementing advanced machine learning techniques to improve prediction accuracy.
Real-time Data: Incorporating real-time data sources for dynamic drug recommendations.
Scaling: Collaborating with healthcare institutions to deploy the system on a larger scale.
Feel free to reach out if you have any questions or need further assistance! 🚀
