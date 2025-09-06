# Diabetes Prediction 🩺🤖  

This project is a **machine learning-based diabetes prediction system** built using Python and Jupyter Notebook.  
It uses medical parameters (like glucose level, BMI, age, etc.) from the **PIMA Indian Diabetes Dataset** to predict whether a patient is likely to have diabetes.  

---

## 📌 Features  
- Data preprocessing & cleaning  
- Exploratory Data Analysis (EDA)  
- Model training using **Support Vector Machine (SVM)**  
- Performance evaluation with **Accuracy Score**  
- Easy-to-understand Jupyter Notebook format  

---

## 📂 Project Structure  
```
├── diabeties_prediction.ipynb # Main Jupyter Notebook
├── README.md # Project Documentation
└── requirements.txt # Python dependencies (optional)

```

---

### ⚙️ Installation & Setup  

1. Clone the repository:  
    ```bash
   git clone https://github.com/<your-username>/<your-repo>.git
   cd <your-repo>
2. Create and activate a virtual environment (recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate   # On Mac/Linux
    venv\Scripts\activate      # On Windows

3. Install dependencies:
    ```bash
    pip install -r requirements.txt



📊 Dataset

The project uses the PIMA Indian Diabetes Dataset from Kaggle.
It contains medical data for 768 patients with the following features:

    -Pregnancies
    
    -Glucose
    
    -Blood Pressure
    
    -Skin Thickness
    
    -Insulin
    
    -BMI
    
    -Diabetes Pedigree Function
    
    -Age
    
    -Outcome → 0 = No Diabetes, 1 = Diabetes

📈 Results

Model Used: Support Vector Machine (SVM)

Evaluation Metric: Accuracy Score -> 77%

Reported metrics include training accuracy and testing accuracy (see notebook for exact values).
