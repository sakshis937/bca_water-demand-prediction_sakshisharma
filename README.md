# 💧 Water Demand Prediction System

## 📌 Overview
The Water Demand Prediction System is a Machine Learning-based web application that predicts water demand based on environmental and social factors. The system helps in analyzing water usage patterns and supports better decision-making for water resource management.

---

## 🚀 Features
- 🔐 User Authentication (Login & Signup)
- 🤖 Machine Learning Prediction (Random Forest)
- 📊 Interactive Dashboard
- 📈 Water Usage Trend Visualization
- 📊 Zone-wise Demand Analysis
- 💡 Smart Insights based on inputs

---

## 🛠️ Technologies Used
- Python
- Streamlit (for web app)
- Pandas (data handling)
- Scikit-learn (ML model)
- Matplotlib (data visualization)

---

## 📂 Project Structure
water_project/
│
├── app.py # Main Streamlit app
├── model.py # Model training script
├── generate_data.py # Dataset generation
├── water_data_big.csv # Generated dataset
├── model.pkl # Trained model file
├── users.json # User login data
├── requirements.txt # Dependencies
└── README.md # Project documentation

---

## ⚙️ How It Works
1. Data is generated using `generate_data.py`
2. The model is trained using `model.py`
3. The trained model is saved as `model.pkl`
4. The Streamlit app (`app.py`) loads the model
5. Users input parameters to get predictions
6. Dashboard displays results and graphs

---

## ▶️ How to Run the Project

### Step 1: Install dependencies
pip install -r requirements.txt


### Step 2: Generate dataset
python generate_data.py


### Step 3: Train the model
python model.py


### Step 4: Run the application
streamlit run app.py


---

## 📊 Input Parameters
- Zone (Residential / Commercial / Industrial)
- Population
- Temperature
- Rainfall
- Weekend Indicator
- Festival Indicator
- Day and Month

---

## 🎯 Output
- Predicted Water Demand (in liters)
- Demand Category (Low / Medium / High)
- Insights based on conditions
- Graphical representation of trends

---

## 💡 Use Cases
- Urban water management
- Smart city planning
- Resource optimization
- Demand forecasting

---

## ⚠️ Note
- This project uses synthetic data for demonstration purposes
- User authentication is basic and not production-level secure

---

## 👨‍💻 Author
- SHREYA DUBEY
- SAKSHI SHARMA
- UNNATI CHAURASIA
- BHUBNESH SHARMA

---

## ⭐ Conclusion
This project demonstrates how Machine Learning can be integrated with a web application to solve real-world problems like water demand forecasting in an efficient and user-friendly way.
