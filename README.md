# 🌾 AgriGo-ML  
### Smart Agriculture Recommendation System using Machine Learning

AgriGo-ML is a machine learning–based smart agriculture system that helps farmers and users make informed decisions by providing **crop recommendations**, **fertilizer suggestions**, and **plant disease detection**.  
The project focuses on improving agricultural productivity using data-driven insights.

---

## 🚀 Key Highlights
- 🌱 Intelligent **Crop Recommendation**
- 🧪 Accurate **Fertilizer Recommendation**
- 🦠 **Plant Disease Detection** using image processing
- 🖥️ Simple and user-friendly web interface
- 📊 Machine Learning–powered predictions

---

## 🎯 Problem Statement
Farmers often face challenges in choosing the right crop, fertilizer, and identifying plant diseases at the right time.  
AgriGo-ML addresses this problem by using machine learning models to provide **reliable and fast recommendations**, reducing guesswork and improving yield.

---

## 💡 Solution Overview
The system takes soil, environmental, and image-based inputs from the user and processes them through trained machine learning models to generate accurate recommendations and predictions.

---

## 🛠️ Tech Stack
**Programming & Frameworks**
- Python  
- Flask  

**Machine Learning & Data Processing**
- Scikit-learn  
- NumPy  
- Pandas  

**Image Processing**
- OpenCV  

**Frontend**
- HTML  
- CSS  
- Bootstrap  

**Tools**
- PyCharm  
- Git & GitHub  

---
## 📂 Project Structure
```
Agrigo-ML/
│
├── app.py                       # Main Flask application
├── crop_recommendation.py       # Crop recommendation logic
├── fertilizer_recommendation.py # Fertilizer recommendation logic
├── disease_detection.py         # Plant disease detection module
│
├── models/
│   ├── crop_model.pkl
│   └── fertilizer_model.pkl
│
├── templates/                   # HTML templates
├── static/                      # CSS and images
├── requirements.txt
└── README.md
 ```

## ⚙️ How It Works

### 🌱 Input Details
The user provides **soil and environmental parameters**:
- Nitrogen (N)
- Phosphorus (P)
- Potassium (K)
- Temperature
- Humidity
- Rainfall

### 🤖 Processing
- Machine learning models analyze the provided input data
- Models are trained on agricultural datasets for accurate predictions

### ✅ Output Recommendations
The system provides:
- Best crop to grow
- Suitable fertilizer

### 🦠 Plant Disease Detection
- User uploads a plant leaf image
- Image is processed and classified
- Detected disease result is displayed to the user

---

## ▶️ How to Run Locally

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/safiyashaik123/Agrigo-ML.git cd Agrigo-ML
cd Agrigo-ML
```

### 2️⃣ Create a Virtual Environment
```bash
python -m venv venv
```

### 3️⃣ Activate the Virtual Environment
```bash
Windows

venv\Scripts\activate
```
```bash
Mac / Linux

source venv/bin/activate
```
### 4️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 5️⃣ Run the Application
```bash
python app.py
```

### 🌐 Open in Browser
```bash
http://127.0.0.1:5000/
```
## 📈 Machine Learning Details

- Supervised machine learning models trained on agricultural datasets  
- Feature-based prediction for:
  - Crop recommendation
  - Fertilizer recommendation  
- Image-based classification used for plant disease detection  
- Data preprocessing and model evaluation were performed to improve accuracy


## 🔮 Future Enhancements

- Integration with real-time weather APIs  
- Use of deep learning models for improved disease detection  
- Cloud deployment for wider accessibility  
- Multilingual support for farmers  

## 👩‍💻 Author

**Safiya Shaik**  
- GitHub: https://github.com/safiyashaik123  
- Repository: https://github.com/safiyashaik123/Agrigo-ML  

## 📄 License

This project is developed for **educational and learning purposes**.




