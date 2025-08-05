# 💳 Financial Fraud Detection using Batch Processing and Machine Learning

Every day, millions of credit card transactions occur, and while most are legitimate, some are fraudulent. Detecting these transactions is a significant challenge—especially when dealing with massive data volumes.

This project implements a batch processing pipeline to detect fraudulent transactions using scalable big data tools and machine learning models.

---

## 🧠 Problem Statement

- **Challenge:** Detect fraudulent transactions from large-scale datasets, where real-time detection is difficult.
- **Goal:** Build a batch system that identifies suspicious patterns, flags fraud early, and minimizes financial losses.

---

## 🚀 Agile Sprint Plan

| Day | Task |
|-----|------|
| 1   | Data Ingestion into HDFS |
| 2   | Data Processing using Apache Spark |
| 3   | Data Querying with Hive |
| 4   | ML Model Development |
| 5   | Data Visualization and Reporting |
| 6   | Testing, Debugging, Deployment |
| 7   | Final Presentation & Documentation |

---

## 🔍 Models and Performance Summary

| Model              | Precision | Recall | F1 Score | Summary |
|--------------------|-----------|--------|----------|---------|
| Logistic Regression | 0.91     | 0.76   | 0.83     | Simple & interpretable, but missed more fraud cases |
| SVM                | 0.95     | 0.77   | 0.85     | Good at reducing false positives, but low recall |
| Random Forest      | 0.96     | 0.92   | 0.94     | Highly accurate, missed a few fraud cases |
| Decision Tree      | 0.95     | 0.97   | 0.96     | Best trade-off model — excellent recall and precision |

✅ **Best Model:** **Decision Tree** — High recall and precision make it the most balanced and effective model for detecting fraud.

---

## 📊 Visual Insights

- 📈 **Fraud Over Time**: Analyzes when fraudulent transactions spike (days/months).
- 🧍‍♂️ **Fraud by Demographics**: Tracks fraud by age, gender, profession, etc.
- 🦠 **Pandemic Impact**: How COVID-19 and online shopping trends accelerated fraud.
- 💡 **Tactics**: Uncovered evolving fraud strategies from data.

---

## 🛡️ Precision-Recall Trade-Off

- **High Recall** = Better fraud capture, but may flag normal transactions.
- **High Precision** = Fewer false positives, but may miss real fraud.
- **Best F1 Score** = Balanced error minimization.

---

## 📈 Achievements

- ✅ Built a scalable fraud detection pipeline
- ✅ Evaluated multiple ML models on financial data
- ✅ Identified optimal model for future integration
- ✅ Reduced false positives/negatives

---

## 🔮 Future Work

- Integrate **real-time** fraud detection using stream processing (Kafka/Spark Streaming)
- Extend pipeline to other financial sectors (e.g., loans, insurance)
- Incorporate deep learning models
- Improve model explainability

---

## 🧠 Fraud Prevention Tips (User Education)

🔐 **Verify the Website:**  
Ensure URLs start with `https` and the site is reputable.

📢 **Read Reviews:**  
Check what others say before purchasing.

⚠️ **Too Good to Be True?**  
Overly generous offers are often scams.

📲 **Use Official Apps:**  
Always use official brand apps or websites.

👀 **Monitor Your Bank Account:**  
Check for unauthorized activity after every transaction.

---

## 🔗 Resources

- 💻 **Colab Notebook**: [View Full Code & Notebook](https://colab.research.google.com/drive/1AZVJ00vlSJKcPWF0ThbwV5My4stIRYDA?usp=sharing)

---

## 📁 Project Structure

financial-fraud-detection-batch-ml/
│
├── notebook.ipynb # Full EDA + model training
├── requirements.txt # Required Python packages
└── README.md # Project documentation

## 💡 Tech Stack

- **Data Ingestion**: HDFS
- **Data Processing**: Apache Spark
- **Querying**: Hive
- **Modeling**: scikit-learn (Logistic Regression, SVM, Random Forest, Decision Tree)
- **Visualization**: Matplotlib, Seaborn
- **Deployment**: Batch mode, extendable to real-time


## ⭐️ If you found this helpful, give it a ⭐️ and share it!
