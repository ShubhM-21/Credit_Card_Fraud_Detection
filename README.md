# **Credit Card Fraud Detection using Logistic Regression**  

## **📄 Overview**  
This project focuses on detecting fraudulent credit card transactions using **Logistic Regression**. The dataset contains transaction details, including anonymized features, and is highly imbalanced. The objective is to build a model that effectively classifies fraudulent transactions while minimizing false positives.  

---

## **🛠 Key Features**  
- **Exploratory Data Analysis (EDA)**:  
  - Analyzed transaction patterns and identified key differences between **legitimate vs. fraudulent** transactions.  
  - Visualized fraud distribution and correlations among key features.  

- **Data Preprocessing**:  
  - Handled **missing values** and scaled numerical features using **StandardScaler**.  
  - Addressed **class imbalance** using **SMOTE (Synthetic Minority Over-sampling Technique)** to improve fraud detection.  

- **Machine Learning Model**:  
  - **Built and trained a Logistic Regression model** for fraud classification.  
  - Tuned hyperparameters to optimize performance.  

- **Evaluation Metrics**:  
  - Assessed model effectiveness using **Accuracy, Precision, Recall, F1-Score, and AUC-ROC Curve**.  
  - Focused on **Recall** to prioritize fraud detection while minimizing false negatives.  

---

## **📊 Dataset**  
The dataset used for this project is available here:  
[Download Dataset](https://drive.google.com/file/d/1avOwlW4LitctN4CPaFqBjZsc983VI3tn/view?usp=sharing)  

---

## **📂 Project Structure**  
```
├── Credit Card Fraud Detection.ipynb  # Jupyter Notebook with full analysis
├── Dataset/                           # Folder containing the dataset
├── README.md                          # Project documentation
```

---

## **🚀 How to Run the Project**  
1. **Clone the Repository**  
   ```bash
   git clone <repository-link>
   ```
2. **Install Dependencies**  
   ```bash
   pip install pandas numpy scikit-learn imbalanced-learn matplotlib seaborn
   ```
3. **Run the Jupyter Notebook**  
   ```bash
   jupyter notebook
   ```
4. **Evaluate Model Performance**  
   - Execute the notebook to preprocess data, train the model, and analyze results.  

---

## **📈 Model Performance & Insights**  
- **Logistic Regression effectively classified fraudulent transactions**, achieving high recall scores.  
- **Data imbalance handling** using **SMOTE** improved fraud detection rates.  
- **Feature importance analysis** helped understand key indicators of fraud.  

---

## **🔗 Project Links**  
- **Jupyter Notebook**: [View Notebook](https://github.com/ShubhM-21/Credit_Card_Fraud_Detection/blob/main/Credit%20Card%20Fraud%20Detection.ipynb)  
---

Let me know if you'd like any refinements! 😊
