# 📧 Phishing Email Detector Using AI — ML-Powered Email Security

_An intelligent machine learning system that detects phishing emails using Python and Flask to enhance cybersecurity and protect users from email-based attacks._

---

## Table of Contents
- [Overview](#overview)
- [Project Objective](#project-objective)
- [Dataset](#dataset)
- [Tools & Technologies](#tools--technologies)
- [Methodology](#methodology)
- [Model Performance](#model-performance)
- [Web Application](#web-application)
- [Future Enhancements](#future-enhancements)
- [Conclusion](#conclusion)
- [Role & Contribution](#role--contribution)
- [Authors](#authors)

---

## Overview
Phishing emails are one of the most common cybersecurity threats, often deceiving users into revealing sensitive information or downloading malicious software.  

This project presents a **machine learning-based phishing email detector** that analyzes the email text and classifies it as **Phishing** or **Legitimate** through an interactive Flask web application.

---

## Project Objective
The primary goals of this project are:

- Build a reliable phishing email classification model  
- Transform raw email text into meaningful numerical features  
- Achieve high accuracy and recall in detection  
- Deploy a user-friendly web interface for real-time predictions  
- Demonstrate an end-to-end ML pipeline  

---

## Dataset
🗂️ **Dataset File Used:** CEAS_08.csv  

The dataset contains **39,154 email records** with labeled phishing and legitimate emails.

### Key Features
- Sender  
- receiver  
- date  
- subject  
- body  
- urls  
- Label (1 = Phishing, 0 = Legitimate)

---

## Tools & Technologies
- **Python**
- **Scikit-learn**
- **Flask**
- **HTML**
- **CSS**
- **CountVectorizer**
- **Logistic Regression**
- **GitHub**

---

## Methodology

### Data Preprocessing
- Text cleaning and normalization  
- Feature extraction using **CountVectorizer**  
- Train-test split (80/20)  

### Feature Engineering
CountVectorizer was used because it:

- Converts text into numerical vectors  
- Captures word frequency patterns  
- Works efficiently for email classification  

### Model Selection
Models evaluated:

- Logistic Regression ✅ (Selected)  
- Random Forest ❌ (Higher complexity)  
- SVM ❌ (Higher computational cost)  

**Final Choice:** Logistic Regression due to its simplicity, speed, and strong binary classification performance.

---

## Model Performance

| Metric | Score |
|--------|-------|
| Accuracy | **95%** |
| Precision | **93%** |
| Recall | **97%** |

✅ High recall ensures phishing emails are rarely missed.

---

## Web Application

The project includes a responsive **Flask-based web interface**.

### Features
- Enter email content in a text box  
- Instant phishing classification  
- Clean and modern UI  
- Color-coded prediction results  
- Responsive layout  

<img width="498" height="437" alt="INTERFACE" src="https://github.com/user-attachments/assets/1ec27d5d-3b77-4b9e-8aab-72a5a3d3391f" />

### UI Improvements
- Centralized Design  
- Styled CSS Interface  
- Button hover Effects  
- Improved Usability  

---

## Future Enhancements

- 🌍 Multilingual email detection  
- 📬 Real-time email service integration  
- 🤖 Transformer-based models (BERT, etc.)  
- ☁️ Cloud deployment  
- 🔌 REST API support  

---

## Conclusion
The machine learning model successfully detects phishing emails with high accuracy and recall. The combination of **CountVectorizer** and **Logistic Regression** provides a fast and efficient baseline solution.

This system can help organizations to:

- Enhance overall email security 
- Reduce phishing risks  
- Automate threat detection  
- Boost user awareness and vigilance  

---

## Role & Contribution
- Problem Understanding  
- Data Preprocessing  
- Feature Engineering  
- Model Training & Evaluation  
- Flask App Development  
- UI Styling (HTML/CSS)  
- Performance Analysis  
- End-to-End ML Implementation  

---

## Authors
**Mian Shakar Afzal**   &   **Muhammad Salman**  

[LinkedIn](https://www.linkedin.com/in/mian-shakar-afzal-959b443a8/) | [GitHub](https://github.com/SHAKAR-AFZAL) | [Email](mailto:mianshakarafzal@gmail.com)

---
