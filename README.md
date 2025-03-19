# Diamond Price Prediction

## 🚀 Project Overview
Diamond Price Prediction is a **machine learning-powered web application** that predicts diamond prices based on attributes like **carat, cut, color, clarity, and dimensions**. This project is fully **automated using pipelines**, ensuring efficient data processing, model training, and real-time predictions.

## 🔥 Features
- **Automated Machine Learning Pipelines** (Training & Prediction)
- **Data Preprocessing** (Handling missing values, feature encoding & scaling)
- **Multiple Model Training & Evaluation** (Linear Regression, Ridge, Lasso, Decision Tree, etc.)
- **Best Model Selection & Deployment**
- **Flask-based Web Interface** for user input and prediction

## 🛠️ Tech Stack
- **Programming Language:** Python
- **Machine Learning:** Scikit-learn
- **Web Framework:** Flask
- **Data Handling:** Pandas, NumPy
- **Logging & Exception Handling:** Python Logging, Custom Exception
- **Deployment:** Flask Web App

## 📂 Project Structure
```
DiamondPricePrediction/
│── artifacts/               # Stores trained models & processed data
│── notebooks/               # Jupyter notebooks for EDA & Model Training
│── src/                     # Source code
│   ├── components/          # Data ingestion, transformation, model training
│   ├── pipelines/           # Training & Prediction pipelines
│   ├── utils.py             # Helper functions
│   ├── logger.py            # Logging configuration
│   ├── exception.py         # Custom exception handling
│── templates/               # HTML templates for the web app
│── logs/                    # Stores log files
│── requirements.txt         # Dependencies
│── setup.py                 # Package setup file
│── application.py           # Flask web app
│── README.md                # Project documentation
```
Visit `http://127.0.0.1:5000/` to access the app.

## 🎯 Usage
1. Enter **diamond attributes** in the web form (carat, cut, color, clarity, etc.).
2. Click **Submit** to get the **predicted price**.

## 🚀 Future Enhancements
- 🏗️ **Deploy on Cloud (AWS/GCP/Heroku)**
- 📊 **Integrate More Advanced ML Models**
- 🎨 **Improve Web UI with Streamlit or React**
- 🔥 **Enable API-based Predictions**

## 🤝 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## 📜 License
This project is licensed under the MIT License.

---

🎉 **Developed by [Aditya Kumar Arya](https://www.linkedin.com/in/aditya-kumar-arya-25b154260/)** 🚀

