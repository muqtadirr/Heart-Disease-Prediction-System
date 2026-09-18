# Heart Disease Prediction System

> **An AI-powered healthcare web application for heart disease risk prediction using Machine Learning.**

The **Heart Disease Prediction System** is a full-stack healthcare application designed to provide a machine-learning-based prediction of potential heart disease risk from patient-related input data.

The project combines a modern web frontend, backend API, and dedicated Machine Learning service into a single application architecture.

---

## 🚀 Project Overview

Heart disease is one of the major health concerns worldwide, and early identification of potential risk factors can support better healthcare decision-making.

This project aims to provide a simple and accessible platform where users can submit relevant health information and receive a machine-learning-based prediction.

### 🎯 Main Objectives

*  Apply **Machine Learning** to healthcare prediction
*  Process and analyze patient-related data
*  Provide an AI-based heart disease risk prediction
*  Build a user-friendly web application
* 🔗 Connect frontend, backend, and ML services
* 🗄️ Support database integration for application data

---

##  Features

*  Heart disease risk prediction
*  Machine Learning-powered prediction system
* 🌐 Web-based user interface
* ⚛️ React frontend
*  Node.js backend
*  Flask-based ML API
*  Data processing with Pandas and NumPy
*  Scikit-learn machine learning support
*  MongoDB database integration
*  JWT-based authentication configuration
*  Separate frontend, backend, and ML architecture

---

##  System Architecture

```text
                    ┌─────────────────────┐
                    │       User          │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │   React Frontend    │
                    │      (Frontend)      │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │   Node.js Backend   │
                    │       (API)         │
                    └───────┬───────┬─────┘
                            │       │
                            │       ▼
                            │  ┌─────────────┐
                            │  │   MongoDB   │
                            │  │   Database  │
                            │  └─────────────┘
                            │
                            ▼
                    ┌─────────────────────┐
                    │    Flask ML API     │
                    │    (ML Service)     │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │ Machine Learning    │
                    │      Model          │
                    └─────────────────────┘
```

---

## 🛠️ Tech Stack

### Frontend

*  **React.js**
*  JavaScript
*  HTML / CSS

### Backend

*  **Node.js**
*  Express.js architecture
*  JWT Authentication
*  REST API

### Machine Learning

*  **Python**
*  **Scikit-learn**
*  **Pandas**
*  **NumPy**
*  **Joblib**
*  **Flask**

### Database

*  **MongoDB**

---

## 📁 Project Structure

```text
heart-disease-prediction-system/
│
├── frontend/
│   ├── src/
│   │   └── App.jsx
│   └── package.json
│
├── backend/
│   ├── server.js
│   └── .env.example
│
├── ml-model/
│   ├── app.py
│   └── requirements.txt
│
├── .gitignore
└── README.md
```

---

## 🔄 Application Workflow

```text
1. User enters health-related information
                  ↓
2. React frontend collects the input
                  ↓
3. Request is sent to the backend
                  ↓
4. Backend communicates with ML API
                  ↓
5. ML model processes the input
                  ↓
6. Prediction is generated
                  ↓
7. Result is returned to the application
                  ↓
8. User receives the prediction
```

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/heart-disease-prediction-system.git

cd heart-disease-prediction-system
```

---

### 2. Setup the Frontend

Navigate to the frontend directory:

```bash
cd frontend
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

---

### 3. Setup the Backend

Open another terminal and navigate to:

```bash
cd backend
```

Install the required Node.js packages:

```bash
npm install
```

Create a `.env` file based on `.env.example`:

```env
PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_secret
```

Start the backend:

```bash
node server.js
```

---

### 4. Setup the Machine Learning API

Navigate to the ML directory:

```bash
cd ml-model
```

Install Python dependencies:

```bash
pip install -r requirements.txt
```

Run the Flask application:

```bash
python app.py
```

---

## 🧠 Machine Learning Pipeline

The Machine Learning component is designed around the following workflow:

```text
Patient Data
     ↓
Data Preprocessing
     ↓
Feature Preparation
     ↓
Machine Learning Model
     ↓
Prediction
     ↓
Heart Disease Risk Result
```

The ML environment includes:

* **NumPy** for numerical computation
* **Pandas** for data processing
* **Scikit-learn** for machine learning
* **Joblib** for model persistence
* **Flask** for exposing the ML model through an API

---

## 🔐 Environment Variables

The backend uses environment variables for configuration.

Create a `.env` file inside the `backend` directory:

```env
PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_secret
```

> ⚠️ Never commit your actual `.env` file or private credentials to GitHub.

---

## 📊 Future Improvements

The project can be further enhanced with:

* 📈 Model performance dashboard
* 🧪 Multiple ML algorithm comparison
* 📊 Accuracy, Precision, Recall and F1-score visualization
* 🔬 Model evaluation and cross-validation
* 📋 Patient prediction history
* 👤 User authentication and profile management
* 🗄️ Complete MongoDB integration
* 📱 Responsive mobile interface
* 📄 Downloadable prediction reports
* 📉 Health-risk visualization
* 🚀 Cloud deployment
* 🔒 Improved security and input validation

---

## ⚠️ Medical Disclaimer

This project is developed for **educational and research purposes only**.

The predictions generated by this application should **not be considered medical advice, diagnosis, or a substitute for professional medical consultation**.

Users should always consult a qualified healthcare professional for medical decisions.

---

## 👨‍💻 Author

### **Md. Abu Muktadir**

🎓 **Data Science Undergraduate | AI/ML Enthusiast**

📌 Interested in:

**Artificial Intelligence • Machine Learning • Data Science • Deep Learning • Computer Vision • Healthcare AI**

---

## ⭐ Support

If you find this project useful or interesting, consider giving it a ⭐ on GitHub.

**Thank you for visiting the project! ❤️**
