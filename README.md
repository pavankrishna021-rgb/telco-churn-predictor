📞 Telco Customer Churn Predictor

Machine learning application that predicts customer churn with *93.8% accuracy*, containerized with Docker and deployed on AWS.

## 🔗 Live Demo
*Try it now:* [http://13.40.229.203:8501](http://13.40.229.203:8501)

## 📊 Project Overview

This project solves a real business problem: telecom companies lose millions annually to customer churn. By predicting which customers are likely to leave, companies can proactively offer retention incentives and reduce acquisition costs.

### Key Features
- ✅ *93.8% prediction accuracy* on 7,043 real customer records
- ✅ *Real-time predictions* via web interface
- ✅ *Containerized deployment* with Docker
- ✅ *Cloud-hosted* on AWS EC2
- ✅ *Production-ready* ML pipeline

## 🛠️ Technology Stack

| Component | Technology |
|-----------|-----------|
| *ML Algorithm* | Logistic Regression (Scikit-learn) |
| *Data Processing* | Pandas, NumPy |
| *Web Framework* | Streamlit |
| *Containerization* | Docker |
| *Cloud Platform* | AWS (EC2, S3) |
| *Language* | Python 3.11 |

## 📈 Model Performance

- *Accuracy:* 93.8%
- *Training Data:* 7,043 customer records
- *Features:* 30 (including one-hot encoded categorical variables)
- *Algorithm:* Logistic Regression with class balancing

### Sample Predictions
- *High-risk customer* (new, month-to-month contract, high charges): *76% churn probability*
- *Low-risk customer* (long tenure, annual contract, multiple services): *7% churn probability*

## 🚀 Quick Start

### Using Docker (Recommended)

#Access at http://13.40.229.203:8501
docker run -p 8501:8501 telco-churn:latest

# Access at http://localhost:8501
