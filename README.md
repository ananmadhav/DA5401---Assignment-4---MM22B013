# DA5401 – Assignment 4

**Name:** Anan Madhav T V  
**Roll Number:** MM22B013  

---

## 📂 Folder Structure  

├── DA5401_A4_MM22B013.ipynb           # Main Jupyter Notebook  
├── README.md                          # Documentation file  
└── creditcard.csv                     # Dataset

⚠️ **Note**: The `creditcard.csv` dataset (~144 MB) exceeds GitHub’s 100 MB file size limit, so it is not included in this repository.  
You can download the dataset from [Kaggle – Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud). 

---

## ⚙️ How to Run  
1. Open the notebook `DA5401_A4_MM22B013.ipynb` in **Jupyter Notebook** or **Google Colab**.  
2. Ensure the `creditcard.csv` file is present in the same directory.  

---

## 📝 Assignment Work

In this assignment, I worked on **credit card fraud detection** using the provided dataset. The main steps I performed are:  

1. **Data Exploration:** Checked the dataset for class imbalance, missing values, and general statistics.  
2. **Baseline Model:** Built a simple model without resampling to understand its performance on imbalanced data.  
3. **GMM-based Oversampling:** Applied Gaussian Mixture Model (GMM) techniques to generate synthetic samples for the minority (fraud) class.  
4. **GMM-CBU (Cluster-Based Upsampling):** Combined clustering with GMM oversampling to try and improve minority class representation.  
5. **Evaluation:** Compared models using precision, recall, and F1-score, and analyzed the trade-offs between detecting fraud and avoiding false alarms.  
6. **Conclusion:** Summarized the results and highlighted which approach was most practical for credit card fraud detection.  

---

## ✅ Conclusion

- The **baseline model** works fairly well because it can detect fraud without flagging too many normal transactions.  

- The **GMM-only model** finds almost all frauds, but it also marks many normal transactions as fraud.  

- The **GMM-CBU model** is similar to GMM-only, catching most frauds but generating too many false alerts.  

**Overall:** For credit card fraud detection, the GMM-based models are better because they help catch most fraud cases, even though they produce more false positives.
