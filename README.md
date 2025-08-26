# 💳 Financial Fraud Detection using Machine Learning

## 📌 Project Overview  
Financial fraud is a growing issue that results in billions of dollars in losses each year. Traditional rule-based fraud detection systems fail to adapt to evolving techniques used by fraudsters.  

This project leverages **Machine Learning (ML)** and **real-time data processing** to build an intelligent fraud detection system. It analyzes transaction patterns, detects anomalies, and minimizes false positives while ensuring scalability and compliance.  

---

## 🎯 Objectives  
- Detect fraudulent transactions in **real-time**.  
- Minimize **false positives** while maximizing fraud detection.  
- Implement **XGBoost** for fraud scoring and **Isolation Forest** for anomaly detection.  
- Provide **scalable and cloud-native deployment** using AWS.  
- Enable analysts with an **interactive dashboard** for fraud insights.  

---

## ⚙️ Technologies Used  
- **Programming & ML**: Python, Pandas, NumPy, Scikit-learn, TensorFlow, XGBoost  
- **Streaming & Processing**: Apache Kafka  
- **Database**: PostgreSQL (Relational), NoSQL (for logs & compliance checks)  
- **Cloud Platform**: AWS (EC2, S3, Lambda, KMS, IAM)  
- **Frontend**: React.js (Analyst/Admin dashboards)  
- **Backend**: Flask (REST APIs & ML integration)  
- **Visualization**: Power BI / Tableau  

---

## 🏗️ System Architecture  
1. **Data Ingestion** – Transaction data collected in real-time using Kafka.  
2. **Preprocessing** – Cleaning, feature engineering, and normalization.  
3. **Model Prediction** – ML models (XGBoost, Isolation Forest) analyze risk.  
4. **Alert Generation** – High-risk transactions flagged automatically.  
5. **Feedback Loop** – Analyst input improves future predictions.  

---

## 📊 Results  
- **Accuracy**: 99.4% with XGBoost  
- **False Positives Reduced**: By 40% compared to rule-based systems  
- **Processing Speed**: <100ms per transaction  
- **Scalability**: 100K+ transactions per second with AWS auto-scaling  
- **Compliance**: Automated sanctions list checks, reducing regulatory risks by 90%  

---

## ✅ Features  
- Real-time fraud detection (<100ms latency).  
- Dynamic fraud risk scoring.  
- Automated compliance checks (sanctions, high-risk countries).  
- Analyst & Admin dashboards for insights.  
- Role-based access control (Admin / Analyst / Auditor).  
- Secure data handling with AES-256 encryption and MFA.  

---

## 🚀 Future Enhancements  
- Integration of **Deep Learning models** for better accuracy.  
- Improved **model explainability** with SHAP values.  
- Handling of **ultra-high traffic (1M+ TPS)**.  
- Incorporating **user feedback loops** for continuous improvement.  


## 📌 Presentation
Refer to [Presentation_Of_Project.ppt](Presentation_Of_Project.ppt).


## 📌 Project Timeline 
Refer to Project Timeline Graph.png


## 📌 Project_Report.pdf
For more detailed explanantion, refer to [Project_Report.pdf](Project_Report.pdf).
