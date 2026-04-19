# 📰 Fake News Detection Project

A machine learning project that detects whether a news article is **FAKE** or **REAL** using Natural Language Processing (NLP) techniques and a **Passive Aggressive Classifier**.

This project uses text data from news articles, converts the content into numerical features using **TF-IDF Vectorization**, and trains a model to classify fake news with high accuracy.

---

## 🚀 Features

- Detects fake vs real news articles
- Uses NLP text preprocessing
- TF-IDF Vectorizer for feature extraction
- Passive Aggressive Classifier for training
- Accuracy score evaluation
- Confusion matrix for model performance

---

## 📂 Project Structure

```bash
fake-news-project/
│── news.csv               # Dataset file
│── news_detection_.py      # Main Python script
│── README.md              # Project documentation
🛠️ Technologies Used
Python 🐍
Pandas
NumPy
Scikit-learn
📊 Machine Learning Workflow
Load Dataset (news.csv)
Extract labels (FAKE / REAL)
Split data into training and testing sets
Convert text into TF-IDF vectors
Train model using PassiveAggressiveClassifier
Predict results
Evaluate accuracy and confusion matrix
📌 Installation

Clone the repository:

git clone https://github.com/your-username/fake-news-project.git
cd fake-news-project

Install dependencies:

pip install pandas numpy scikit-learn
▶️ Run the Project
python news_detection_.py
📈 Example Output
Accuracy: 92.45%

(Accuracy may vary depending on dataset split)

🧠 Model Used
Passive Aggressive Classifier

A powerful online learning algorithm used for large-scale learning. Great for text classification problems like fake news detection.

📷 Dataset

Dataset file:

news.csv

Contains:

title
text
label
🔮 Future Improvements
Build Streamlit Web App
Add Real-time News URL Detection
Improve preprocessing
Try Deep Learning models (LSTM / BERT)
Deploy on Hugging Face / Render
🤝 Contributing

Pull requests are welcome. For major changes, open an issue first.

📜 License

This project is open-source and free to use.

👑 Author

Made with code and curiosity by Lakshay Pal
