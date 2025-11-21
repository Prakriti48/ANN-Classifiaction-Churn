
📊 ANN Classification – Customer Churn Prediction

This project builds an **Artificial Neural Network (ANN)** model to predict **customer churn** using a bank dataset.  
The project includes:

- Data preprocessing  
- Encoding (Label Encoding + One-Hot Encoding)  
- Feature scaling  
- ANN model training using TensorFlow/Keras  
- Streamlit application for real-time prediction  

---

## 🚀 Project Structure

```

├── app.py                     # Streamlit app
├── model.h5                   # Trained ANN model
├── requirements.txt           # Dependencies for Streamlit Cloud
├── label_encoder_gender.pkl   # Label Encoder for Gender
├── onehot_encoder_geo.pkl     # One-Hot Encoder for Geography
├── scaler.pkl                 # StandardScaler for numerical features
└── README.md                  # Documentation

````

---

## 🧠 ANN Model Overview

The Artificial Neural Network includes:

- Dense Layer (ReLU)
- Dense Layer (ReLU)
- Output Layer (Sigmoid)
- Optimizer → **Adam**
- Loss → **Binary Crossentropy**
- Metric → **Accuracy**

The model predicts if a customer will **Exit (Churn)** or **Stay**.

---

## 🛠 Technologies Used

- Python  
- TensorFlow / Keras  
- Numpy  
- Pandas  
- Scikit-Learn  
- Matplotlib  
- Streamlit  

---

## 🧩 Running the Project Locally

### 1. Clone the repository

```bash
git clone https://github.com/Prakriti48/ANN-Classifiaction-Churn.git
cd ANN-Classifiaction-Churn
````

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run Streamlit App

```bash
streamlit run app.py
```

---

## 🌐 Live Demo

Add your Streamlit app URL here once deployment completes:

```
https://your-app-name.streamlit.app/
```

---

## 📦 Deployment Notes (Important)

Streamlit Cloud uses **Python 3.13**, so TensorFlow 2.15 doesn’t work.
Use:

```
tensorflow-cpu==2.20.0
```

in requirements.txt for successful deployment.

---

## 📘 Dataset Information

The dataset includes features like:

* CreditScore
* Geography
* Gender
* Age
* Tenure
* Balance
* NumOfProducts
* HasCrCard
* IsActiveMember
* EstimatedSalary

Target variable:

* **Exited** → 1 (Churned)
* **Exited** → 0 (Not Churned)

---

## 🔧 Preprocessing

* Label Encoding for Gender
* One-Hot Encoding for Geography
* Standard Scaling for numerical data
* Train-Test split (80/20)

Encoders and scaler are saved as `.pkl` files and loaded during prediction.

---

## 🎯 Model Results

The ANN provides solid accuracy and can predict whether a customer will churn based on the given input features.

---

## 🤝 Contributing

Pull requests are welcome!
Feel free to fork and improve the project.

---

## 📬 Contact

Created by **Prakriti**
For any questions, contact via GitHub.

```

---

If you want a **more advanced README with badges, images, diagrams, or a preview GIF**, tell me — I can generate it!
```
