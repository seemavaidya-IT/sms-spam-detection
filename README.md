 SMS Spam Detection using Machine Learning

📖 Project Overview

This project is an end-to-end SMS Spam Detection System that classifies SMS text messages as Spam or Ham (Not Spam) using Machine Learning and Natural Language Processing (NLP). A web interface built using Flask allows users to input any message and get a real-time prediction.

🚀 Features

✔ SMS text preprocessing & cleaning

✔ TF-IDF vectorization

✔ Machine Learning model (Naive Bayes / Logistic Regression)

✔ High accuracy & fast prediction

✔ Model saved using pickle

✔ Flask web app for prediction

✔ Simple UI & easy deployment

🧠 Tech Stack

Languages & Libraries

Python

Pandas, NumPy

Scikit-Learn

NLTK

Flask

Pickle

Tools

Jupyter Notebook

VS Code

Git / GitHub

📂 Project Structure

SMS-Spam-Detection/ │ ├── app.py # Flask web app ├── model.pkl # Trained ML model ├── vectorizer.pkl # TF-IDF vectorizer ├── notebook.ipynb # ML model training notebook ├── templates/ │ └── index.html # Web UI ├── static/ │ └── style.css # Optional styling └── README.md

🧪 Machine Learning Process

Import and clean dataset

Remove stopwords, punctuation & apply stemming

Convert text to numerical form using TF-IDF

Train ML models (Naive Bayes performs best)

Evaluate (Accuracy, Precision, Recall, F1-score)

Save model & vectorizer using pickle

Use Flask for deployment

📊 Model Performance

Example metrics (your results may vary):

Metric Score

Accuracy 97% Precision 98% Recall 96% F1 Score 97%

🌐 How to Run the Project

Install Requirements
pip install -r requirements.txt

Start Flask App
python app.py

Open in Browser
http://127.0.0.1:5000/

📬 Example Output

Input: "Congratulations! You have won a lottery worth $5000!"

Prediction: Spam

Input: "Are we meeting today at 5 PM?"

Prediction: Ham

💡 Future Enhancements

Deploy on Render / AWS / HuggingFace

Multi-language spam detection

Mobile-friendly UI

🏅 Author

Seema vaidya (B.Tech Student | Data Science & Machine Learning Enthusiast)
