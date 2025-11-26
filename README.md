# 🫀 Heart Disease Prediction using Machine Learning
## 🔍 Predicting Heart Disease Risk from Patient Health Data

This project focuses on building and evaluating Machine Learning models to detect whether a person is at risk of heart disease based on clinical attributes such as age, cholesterol levels, chest pain type, resting blood pressure, and more.

The goal is to provide a decision support tool to assist in early detection and prevention of heart disease — the leading cause of death worldwide. 💔➡️❤️‍🩹

# 🚀 Technologies & Concepts Used
Category	Tools
1. Python 🐍
2. Libraries : Pandas, NumPy, Matplotlib, Seaborn
3. ML Algorithms : 	Logistic Regression, Random Forest Classifier
4. Preprocessing  :	StandardScaler
5. Evaluation : Confusion Matrix, Classification Report, Accuracy Score

#  📊 Dataset Details
### 📌 Dataset Name: Heart Disease Dataset

##### 🎯 Target Column: target
1 → Heart Disease Present

0 → No Heart Disease

🧩 Contains medical features like:

age, sex, cp, chol, trestbps, thalach, ca, thal etc.

Dataset obtained from a publicly available UCI repository version uploaded as heart_disease.csv.

# 🧠 Workflow / Project Pipeline
## graph TD;

    A[Import Dataset] --> B[Data Preprocessing];
    
    B --> C[Feature Scaling];
    
    C --> D[Train-Test Split];
    
    D --> E[Model Training];
    
    E --> F[Evaluation & Comparison];
    
    F --> G[Best Model Selection];
    
    G --> H[Prediction on New Patient];

# 🤖 Machine Learning Models Used
## Model	Accuracy
1. Logistic Regression	value%
2. Random Forest Classifier	value%

📌 Accuracy values will auto-update when running the code in notebook.

🎯 Best Model Selected: Random Forest Classifier (based on performance)

## 📈 Model Performance Visualization
Heatmap of confusion matrix for best model is plotted to analyze classification accuracy visually.

# 🧪 Predicting New Patient Result

The model can take new patient data as input and classify based on heart disease risk:

Result:

"At Risk of Heart Disease" 😟

or

"No Heart Disease" 😄


Real-world usage support for doctors and hospitals. 🏥

# 🔧 How to Run the Project
Step 1: Clone the repository
https://github.com/Amirul-Ali/Dieases-Prediction-using-ML-Algorithms

Step 2 : 2️⃣ Install required dependencies
- pip install -r requirements.txt

Step 3:  3️⃣ Run the Jupyter Notebook
- jupyter notebook

# 📦 Folder Structure
📂 Heart-Disease-Prediction
│

├── 📄 heart_disease.csv

├── 📓 Heart_Disease_Prediction.ipynb

├── 📄 README.md

└── 📄 requirements.txt

# 🌟 Key Learnings & Takeaways
✔ Handling missing values

✔ Feature scaling & preprocessing

✔ Comparing ML models

✔ Making predictions on new unseen data

✔ Visualizing evaluation metrics

# 📌 Future Improvements
1. Expand dataset for higher accuracy
2. Add deep learning model (ANN)
3. Build a web app (Flask/Streamlit)
4. Feature engineering for improved detection
