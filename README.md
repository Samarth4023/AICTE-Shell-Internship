# **🌱 Crop & Fertilizer Recommendation System**  

## **📌 Introduction**  
This project is a **AI Powered Crop & Fertilizer Recommendation System**, developed as part of my **AICTE-Shell Internship**. The system provides **personalized crop and fertilizer recommendations** based on soil composition, weather conditions, and crop requirements.  

🔗 **Deployed Application:** [Crop & Fertilizer Recommendation System](https://samarth4023-aicte-shell-internship-rs-app-nhp1xt.streamlit.app/)  

## **🎯 Project Goals**  
✅ Integrate **AI and Green Skills** into agriculture.  
✅ Explore **Machine Learning techniques** for precision farming.  
✅ Develop a **real-time recommendation system** for farmers.  
✅ Enhance **data preprocessing, model selection, and optimization skills**.  
✅ Deploy an **interactive web app** using **Streamlit**.  

## **📂 Datasets Used**  
The project uses two datasets:  

### **1️⃣ Crop Dataset**  
- **Features:** Nitrogen, Phosphorous, Potassium, Temperature, Humidity, pH, Rainfall  
- **Target Variable:** Crop Label (Crop Name)  

### **2️⃣ Fertilizer Dataset**  
- **Features:** Temperature, Humidity, Moisture, Soil Type, Crop Type, Nitrogen, Phosphorous, Potassium  
- **Target Variable:** Fertilizer Name  

## **📊 Methodology**  

### **Step 1: Data Collection & Preprocessing**  
🔹 **Performed Exploratory Data Analysis (EDA)** to understand data distributions.  
🔹 **Encoded categorical variables** using Label Encoding.  
🔹 **Split the dataset** into **train & test sets** using Scikit-Learn.  

### **Step 2: Model Selection & Training**  
🔹 Tested multiple **ML algorithms**, including:  
   - Logistic Regression, GaussianNB, SVC, KNN, DecisionTree, ExtraTree, RandomForest, Bagging, Gradient Boosting, AdaBoost, CatBoost, and LGBM.  
🔹 Compared **model performance** based on accuracy & validation metrics.  

### **Step 3: Ensemble Learning for Optimization**  
🔹 Evaluated different ensemble techniques:  
   - **Voting Classifier, Stacking, Averaging Probabilities, Weighted Ensemble, Blend Ensemble (Custom Blending).**  
🔹 **Blend Ensemble provided the best results**, so it was selected.  
🔹 **Cross-validation** was performed to validate model performance.  

### **Step 4: Deployment & Integration**  
🔹 Exported trained models as **.pkl files** (`crop_recommendation.pkl`, `fertilizer_recommendation.pkl`).  
🔹 Integrated models into a **Streamlit app** for real-time predictions.  
🔹 **Deployed the application on Streamlit Cloud.**  

## **🔍 Key Features**  
✅ **Real-time Model Performance Metrics** (Accuracy Tracking).  
✅ **Feature Importance Analysis** for better interpretability.  
✅ **Feature Distributions** to understand data variations.  
✅ **Prediction Probabilities** to assess model confidence.  

## **🚀 Technologies Used**  
| Category            | Tools & Libraries |
|---------------------|------------------|
| **Development**    | Python, Jupyter Notebook, Anaconda |
| **ML Frameworks**  | Scikit-Learn, CatBoost, LGBM, XGBoost |
| **Data Processing**| Pandas, NumPy |
| **Visualization**  | Matplotlib, Seaborn |
| **Deployment**     | Streamlit, Streamlit Cloud |

## **📷 Screenshots**  

| **Streamlit App - Crop Recommendation** | **Streamlit App - Fertilizer Recommendation** |
|-----------------------------------------|-----------------------------------------------|
| ![Screenshot_20250207_165105_Chrome](https://github.com/user-attachments/assets/4eeaf812-9861-42cc-8da0-99ae5b6ce7ef) ![Screenshot_20250207_165127_Chrome](https://github.com/user-attachments/assets/f56d75d4-f525-49b1-a96f-b7069d636e3e) ![Screenshot_20250207_165152_Chrome](https://github.com/user-attachments/assets/1c6fd4d8-76b6-4296-9de8-fa58c1d595ef) ![Screenshot_20250207_165206_Chrome](https://github.com/user-attachments/assets/e687b035-bebc-48ec-be2f-54bb6f653b6a) | ![Screenshot_20250207_170147_Chrome](https://github.com/user-attachments/assets/9f82901f-deeb-4a58-aa01-add4115f0860) ![Screenshot_20250207_170221_Chrome](https://github.com/user-attachments/assets/d5cbca1f-d954-4145-86e3-6c596a58a5a6) ![Screenshot_20250207_170235_Chrome](https://github.com/user-attachments/assets/34f968ad-3d02-411c-94e2-a0dd28de92a6) ![Screenshot_20250207_170245_Chrome](https://github.com/user-attachments/assets/cfc8bfc5-5890-46da-a636-257ac68d411b) |

## **🎯 Future Improvements**  
🔹 Expand the dataset to include **more crop varieties & soil types**.  
🔹 Integrate **real-time weather data** for better recommendations.  
🔹 Incorporate **IoT & satellite data** for advanced precision farming.  
🔹 Optimize **model efficiency & deployment** for faster predictions.  

## **📥 Installation & Setup**  

### **🔹 Clone the Repository**  
```bash
git clone https://github.com/Samarth4023/Shell-Internship.git
cd Shell-Internship
```

### **🔹 Install Required Dependencies**  
```bash
pip install -r requirements.txt
```

### **🔹 Run the Streamlit App**  
```bash
streamlit run app.py
```

## **📜 License**  
This project is **open-source** and free to use. Feel free to contribute!  

## **📧 Contact**  
📌 **Author:** Samarth Pujari  
📌 **GitHub:** [Samarth4023](https://github.com/Samarth4023)  
📌 **LinkedIn:** [Samarth Pujari](www.linkedin.com/in/samarth-pujari-328a1326a)  
