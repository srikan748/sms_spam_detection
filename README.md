# SMS Spam Detection using Machine Learning

## 📌 Project Overview

SMS Spam Detection is a machine learning project that classifies SMS messages as **Spam** or **Ham (Not Spam)**.
The project uses **Natural Language Processing (NLP)** techniques and machine learning algorithms to analyze message text and predict whether a message is spam.

This type of system is useful for **email filtering, messaging applications, and cybersecurity systems** to automatically block unwanted or fraudulent messages.

---

## 📂 Dataset

The dataset contains labeled SMS messages with two columns:

* **Status** → Label of the message (spam or ham)
* **Text** → The actual SMS message content

Example:

| Status | Text                                  |
| ------ | ------------------------------------- |
| ham    | I'm going to attend the meeting       |
| spam   | Congratulations! You won a free prize |

---

## ⚙️ Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Scikit-learn**

---

## 🧠 Machine Learning Techniques

The following techniques are used in the project:

* Text preprocessing
* Label encoding
* Train-test split
* TF-IDF vectorization
* Machine learning classification

---

## 🤖 Algorithms Used

* **Naive Bayes**
* **Logistic Regression**

These algorithms are commonly used in text classification tasks.

---

## 🚀 Project Workflow

1. Import required libraries
2. Load dataset using Pandas
3. Handle missing values
4. Convert labels (spam / ham) to numerical values
5. Split dataset into training and testing sets
6. Convert text data using **TF-IDF Vectorization**
7. Train machine learning models
8. Evaluate model performance using accuracy score

---

## 📁 Project Structure

sms-spam-detection
│
├── dataset
│   └── spam.csv
│
├── notebook
│   └── sms_spam_detection.ipynb
│
├── requirements.txt
└── README.md

---

## ▶️ How to Run the Project

1. Clone the repository

```bash
git clone https://github.com/yourusername/sms-spam-detection.git
```

2. Install required libraries

```bash
pip install -r requirements.txt
```

3. Open the Jupyter Notebook

```bash
jupyter notebook
```

4. Run the notebook **sms_spam_detection.ipynb**

---

## 🎯 Conclusion

This project demonstrates how **machine learning and NLP techniques can be used to detect spam messages automatically**.
The model can effectively classify SMS messages and can be extended to real-world messaging or email filtering systems.

---

## 👨‍💻 Author

**Gunji Srikanth**
MCA Student 
