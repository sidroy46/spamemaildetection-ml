Spam Email Detection using Machine Learning

Spam messages are a common problem in email and messaging platforms.
In this project, I built a spam detection system that can automatically classify messages as Spam or Not Spam (Ham) using machine learning techniques.

The project is implemented in Python and executed using Google Colab.

->About the Dataset:

I used the SMS Spam Collection Dataset, which is a well-known real-world dataset used for spam detection tasks.
Total messages: 5,572
Classes:
Spam
Ham (Not Spam)
Source: Kaggle / Public GitHub repository
The dataset contains real SMS messages, which makes the model more reliable and practical.


->How the Project Works:

The project follows a complete machine learning pipeline:
The dataset is loaded and explored
Text data is cleaned by removing special characters and stopwords
Messages are converted into numerical features using TF-IDF
The data is split into training and testing sets

Two models are trained:

Naive Bayes
Logistic Regression

Both models are evaluated and compared
The best-performing model is used for prediction

Models Used
Naive Bayes:

Naive Bayes is a probabilistic model that works very well for text classification problems.
It is fast, simple, and gives good results on large text datasets.

Logistic Regression:

Logistic Regression is a linear classification algorithm.
It serves as a strong baseline model and performs well when combined with TF-IDF features.

After comparison, Naive Bayes performed slightly better, so it was selected as the final model.

Results:
Accuracy achieved: around 95% – 97%

Evaluation metrics used:

Accuracy
Precision
Recall
F1-score

Example Prediction
predict_spam_final("Congratulations! You won a free prize")

Output:
SPAM

How to Run the Project:
Open the notebook using the Open in Colab button in GitHub
Run all the cells from top to bottom
View the model evaluation results
Test the model using your own custom messages

What I Learned:
How to work with real-world text datasets
Importance of text preprocessing in NLP
How to compare multiple machine learning models
How to host and share projects using GitHub and Google Colab

Future Improvements:
Add visualization such as confusion matrix
Build a simple web interface using Streamlit
Save the trained model for reuse
Try additional machine learning algorithms
