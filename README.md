# NYC Taxi Fare and Trip Duration Prediction 🚖

## 📌 Project Overview
This project aims to build a **machine learning model** that predicts both the **fare** and **duration** of taxi rides in New York City.  
Predictions are based on factors such as:
- Pick-up and drop-off locations  
- Date and time of the ride  
- Weather conditions  

This serves as the **capstone project** for the ML Developer Career path, consolidating skills in supervised learning, time-series analysis, and model deployment.

---

## 🎯 Goals
- Develop models to predict **fare** and **trip duration** from NYC taxi trip data.  
- Compare baseline models (Linear Regression, Decision Trees) with advanced algorithms (XGBoost, Random Forest, Neural Networks).  
- Deliver a **reproducible, containerized solution** with clear documentation and demo capabilities.  

---

## 📂 Main Deliverables
- **Exploratory Data Analysis (EDA):** Jupyter notebooks analyzing dataset structure, missing values, outliers, and correlations.  
- **Preprocessing Scripts:** Data cleaning and preparation pipelines.  
- **Training Scripts & Models:** Implementation of models for fare and duration prediction.  
- **Reproducibility:** Documentation of steps to reproduce results.  
- **Demo & Results Presentation:** Real-time predictions via API or interactive notebook.  
- **Containerization:** Dockerized environment for deployment.  

---

## 🔧 Suggested Approach
1. **Baseline Models:** Linear Regression, Decision Trees.  
2. **Advanced Models:** Random Forest, LightGBM, XGBoost, Neural Networks (MLP).  
3. **Evaluation Metrics:** MAE, MSE, training time, inference time.  
4. **Model Selection:** Choose best-performing model balancing accuracy and speed.  

---

## 🌐 Dataset
- Source: [NYC TLC Trip Record Data (2022)](https://www.nyc.gov/assets/tlc/downloads/pdf/trip_record_user_guide.pdf)  
- Focus: **Yellow Taxi Trip Records**  
- Format: PARQUET files, split by month  
- Recommended start: **May 2022 dataset** for initial experiments  

---

## 📈 Optional Extensions
- Add external features (traffic, weather, road closures) via APIs (e.g., OpenWeather).  
- Train a model for **taxi demand prediction** by region and time.  

---

## 🗺️ Milestones
- Setup repository and project structure  
- Literature review (state-of-the-art approaches)  
- Download and clean dataset  
- Train and evaluate models  
- Prepare demo (API or notebook with visualizations such as NYC maps)  
- Present results on Demo Day  

---

## 🚀 Tech Stack
- **Languages:** Python  
- **Libraries:** Pandas, Scikit-learn, XGBoost, LightGBM, TensorFlow/PyTorch  
- **Deployment:** Docker, Flask/FastAPI  
- **Visualization:** Matplotlib, Seaborn, Folium (NYC maps)  

---

## 📊 Evaluation
Models will be compared using:
- **Accuracy metrics:** MAE, MSE  
- **Efficiency metrics:** Training time, inference time  
- **Deployment readiness:** API performance and scalability  

---

## 👥 Contributors
This project is part of the **AnyoneAI ML Developer Career Path**.  
Collaborators and mentors are welcome to contribute improvements, extensions, and feedback.

---

## 📜 License
This project is licensed under the MIT License. See the LICENSE file for details.
