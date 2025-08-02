# 🔌 Power System Fault Detection & Classification using Machine Learning

## 📘 Project Overview

This project implements a machine learning-based approach for detecting and classifying faults in power distribution systems. Using electrical phasor data (voltage and current), the system can identify and categorize fault types such as:

- Line-to-Ground (L-G)
- Line-to-Line (L-L)
- Three-Phase Faults (L-L-L)
- Normal Operation

The solution uses a **Random Forest Classifier** trained on historical phasor measurements and is deployed using **IBM Cloud** for real-time inference and fault monitoring.

---

## 💡 Problem Statement

Modern power systems are highly sensitive to faults that may lead to equipment failure, power outages, and reduced reliability. Traditional rule-based fault detection methods often lack the speed and adaptability required in dynamic grid environments.

There is a need for an intelligent, automated system that:
- Detects faults rapidly and accurately
- Classifies fault types using real-time data
- Scales effectively with modern grid technologies

---

## 🧠 ML Approach

### Algorithm: Random Forest Classifier
- Ensemble-based model using decision trees
- High accuracy and robustness to noise
- Suitable for multi-class classification

### Input Features
- Voltage and current phasor magnitudes and phase angles

### Training Process
- Labeled dataset (normal + fault classes)
- Data split into training and test sets
- Cross-validation and hyperparameter tuning
- Model evaluation using accuracy, precision, recall, F1-score

---

## ☁️ IBM Cloud Deployment

- **IBM Watson Studio** for data preprocessing, training, and evaluation  
- **IBM Cloud Object Storage** for storing input datasets  
- **IBM Watson Machine Learning (WML)** for model deployment as REST API  
- **Real-time fault data** can be sent to the deployed API for classification  

---

## 🛠️ Tech Stack

| Component         | Technology                       |
|-------------------|----------------------------------|
| Language          | Python 3.8+                      |
| ML Library        | scikit-learn                     |
| Cloud Platform    | IBM Cloud                        |
| Model Deployment  | IBM Watson Machine Learning (WML)|
| Data Storage      | IBM Cloud Object Storage         |
| Dev Environment   | IBM Watson Studio / JupyterLab   |

---

## 📊 Results

- High classification accuracy on test data  
- Fast real-time response for live fault classification  
- Robust performance across multiple fault types  

---

## 🔮 Future Scope

- Deploy model on edge devices for faster local inference  
- Integrate with SCADA and fault response systems  
- Explore deep learning models (e.g., LSTM, CNN)  
- Enhance dataset with environmental and seasonal factors  
- Combine with cybersecurity detection for grid protection  

---

## 📚 References

1. Phadke, A. G., & Thorp, J. S. *"Synchronized Phasor Measurements and Their Applications."* Springer, 2008.  
2. Soman, S. A., et al. *"Fault Detection Using Machine Learning."* IEEE Transactions on Power Delivery, 2018.  
3. IBM Watson Studio: https://www.ibm.com/cloud/watson-studio  
4. scikit-learn Documentation: https://scikit-learn.org  
5. Towards Data Science: https://towardsdatascience.com/understanding-random-forest-58381e0602d2  

---

## 👤 Authors

- Vivek Chauhan — [LinkedIn](https://www.linkedin.com/in/vivek-chauhan-826998362?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app) 
