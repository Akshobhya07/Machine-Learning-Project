# Machine-Learning-Project

🚴 Bike Sharing Demand Prediction using Machine Learning


📌 Project Overview
This project predicts **bike sharing demand** using multiple machine learning models.  
The goal is to classify demand into **Low** and **High** categories based on features like weather, season, and time.

The dataset used is the **UCI Bike Sharing Dataset** (`day.csv` and `hour.csv`).



🎯 Objectives
- Convert continuous demand (`cnt`) into binary classification (Low / High)
- Train and compare **12 machine learning models**
- Evaluate performance using **80:20 and 70:30 splits**
- Visualize results using **confusion matrix and graphs**


📂 Dataset
- `day.csv` → Daily data  
- `hour.csv` → Hourly data  

🔑 Key Features
- Season  
- Weather  
- Temperature  
- Humidity  
- Working Day  
- Holiday  
- Demand Count (`cnt`)  



⚙️ Methodology

1. Data Loading  
2. Data Cleaning  
3. Drop unnecessary columns  
4. Convert `cnt → target (0 = Low, 1 = High)`  
5. Encoding (Label Encoding)  
6. Feature Scaling (StandardScaler)  
7. Train-Test Split  
   - 80:20  
   - 70:30  
8. Model Training  
9. Evaluation using metrics  



🤖 Machine Learning Models Used

- Logistic Regression  
- Decision Tree  
- Random Forest  
- Support Vector Machine (SVM)  
- K-Nearest Neighbors (KNN)  
- Naive Bayes  
- Gradient Boosting  
- AdaBoost  
- Extra Trees  
- XGBoost  
- LightGBM  
- Ridge Classifier  



📊 Evaluation Metrics

- Accuracy  
- Precision  
- Recall  
- F1 Score  
- Confusion Matrix (2×2)



📈 Results & Insights

- ✅ Ensemble models (**Random Forest, Gradient Boosting, XGBoost**) performed best  
- ✅ Binary classification ensures clear interpretation  
- ✅ Both **80:20 and 70:30 splits** used for comparison  


📊 Sample Output
