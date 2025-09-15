# DA5401 – Assignment 3

**Name:** Anan Madhav T V  
**Roll Number:** MM22B013  

---

## 📂 Folder Structure  

├── DA5401_A3_MM22B013.ipynb           # Main Jupyter Notebook  
├── README.md                          # Documentation file  
└── creditcard.csv                     # Dataset

⚠️ **Note**: The `creditcard.csv` dataset (~144 MB) exceeds GitHub’s 100 MB file size limit, so it is not included in this repository.  
You can download the dataset from [Kaggle – Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud). 

---

## ⚙️ How to Run  
1. Open the notebook `DA5401_A3_MM22B013.ipynb` in **Jupyter Notebook** or **Google Colab**.  
2. Ensure the `creditcard.csv` file is present in the same directory.  

---

## 📊 Project Overview  

This assignment focuses on **credit card fraud detection** using machine learning techniques on a highly imbalanced dataset.  

### 🔎 Key Steps  

- **Baseline Model:**  
  - Trained using the original dataset without resampling  

- **Resampling Techniques:**  
  - **SMOTE** (Synthetic Minority Oversampling Technique)  
  - **CBO** (Clustering-Based Oversampling)  
  - **CBU** (Clustering-Based Undersampling)  

- **Evaluation Metrics:**  
  - Precision  
  - Recall  
  - F1-score  
  - Accuracy  

---

## ✅ Results Summary  

- **Baseline:** High precision, very low recall → misses most fraud cases  
- **SMOTE:** Very high recall but very low precision → too many false positives  
- **CBO:** Best overall performance → high recall and strongest F1-score  
- **CBU:** Good recall but weaker precision compared to CBO  

📌 **Conclusion:**  
CBO is the most effective method for this dataset, achieving the best balance between recall and F1-score.  

