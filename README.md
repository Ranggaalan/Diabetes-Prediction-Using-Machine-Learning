# **Diabetes Prediction Using Machine Learning**  
![Image](https://github.com/user-attachments/assets/b64de0f9-d64f-4273-bc17-7152dde27be4)

## **Project Description**  
This project applies **machine learning classification models** to predict **diabetes** based on **medical records** from a hospital in Kediri. The dataset consists of **399 records and 6 features**, and the classification models are evaluated to determine the best-performing model.  

## **Dataset**  
The dataset contains patient medical records with the following features:  
- **ID**: Unique identifier for each patient  
- **Usia (Age)**: Patient's age  
- **Kelamin (Gender)**: Male/Female  
- **Hasil Lab (Lab Results)**: Relevant laboratory test results  
- **Hipertensi (Hypertension)**: Presence of high blood pressure (Yes/No)  
- **Diagnosis**: Diabetes status (Positive/Negative)  

## **Methodology**  
### **1. Data Preprocessing**  
- Handling missing values  
- Encoding categorical variables  
- Normalization and scaling  
- Splitting dataset into **training (70%) and testing (30%)**  

### **2. Classification Models**  
The following **5 machine learning models** were implemented:  
1. **K-Nearest Neighbors (KNN)**  
2. **Random Forest Classifier**  
3. **Decisions Tree**  
4. **Logistic Regression**  
5. **Naive Bayes**  

### **3. Model Evaluation**  
The models were evaluated using **accuracy, precision, recall, and F1-score**.  

## **Results**  
- **KNN achieved the highest test accuracy of 90%.**  
- Random Forest and Gradient Boosting also performed well, but with slightly lower accuracy.  
- Logistic Regression and SVM had moderate performance, indicating potential **non-linearity in the dataset**.  

## **Technologies Used**  
- **Python**: Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn  
- **Machine Learning**: Classification models for diabetes prediction  
- **Jupyter Notebook**: Data analysis and model evaluation  


## **Conclusion**  
The **KNN model achieved the best performance** with **90% accuracy**, making it the most suitable model for this dataset. This project demonstrates how machine learning can be applied to **predict diabetes** using medical records, which can assist in early detection and intervention.  
