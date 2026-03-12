# ✈️ Airline Performance & Flight Delay Prediction Dashboard

## 🚀 Project Overview
This project analyzes airline operations and predicts flight delays using historical flight data. It combines **data analysis, machine learning, and visualization** to provide actionable insights for airlines, airports, and passengers. Users can explore **flight performance KPIs** and predict **flight delays** with expected minutes using an interactive web app.

---

## 🎯 Objectives
- Predict whether a flight is likely to be delayed (Yes/No).  
- Estimate the expected delay in minutes if a delay occurs.  
- Analyze airline and airport performance using key metrics such as total flights, cancellation rate, delay causes, and average delay.  
- Provide an interactive dashboard for data-driven decision-making.

---

## 📊 Features
- **Multi-Task Machine Learning Model**:
  - **Random Forest Classifier**: Predicts if a flight will be delayed.  
  - **Random Forest Regressor**: Estimates average delay minutes for delayed flights.  
- **Feature Engineering**:  
  - Calculated KPIs: `delay_ratio`, `cancel_ratio`, `divert_ratio`, `avg_delay_per_flight`  
  - Encoded categorical features: `carrier_name`, `airport_name`  
- **Interactive Gradio Web App**: Input flight details to get real-time predictions.  
- **Power BI Dashboard**:
  - KPI Cards: Total Flights, % Delayed Flights, Avg Delay Minutes, % Cancelled  
  - Visualizations: Monthly delay trends, delays by carrier, airport-wise delay analysis, delay cause breakdown  
  - Filters/Slicers for Year, Month, Carrier, and Airport

---

## 🗂️ Folder Structure


airline-delay-prediction/

│
├── app.py # Gradio web app for real-time prediction

├── flight_delay.csv # Dataset (or sample dataset)

├── requirements.txt # Python dependencies

├── README.md # Project documentation

├── powerbi_dashboard/ # Optional: Power BI files (.pbix, screenshots)

└── screenshots/ # Optional: Images of dashboard and app


---
## 📌 Dataset Description

Column	Description

year	Year of the flight record

month	Month of the flight record

carrier_name	Airline name

airport_name	Airport name

arr_flights	Number of arriving flights

arr_del15	Flights delayed ≥15 minutes

arr_delay	Total arrival delay (minutes)

arr_cancelled	Number of cancelled flights

arr_diverted	Number of diverted flights

carrier_delay	Delay due to carrier

weather_delay	Delay due to weather

nas_delay	Delay due to NAS

security_delay	Delay due to security

late_aircraft_delay	Delay due to late aircraft arrival




## 🔧 Technologies Used

Python: Pandas, NumPy, scikit-learn, Gradio

Machine Learning: Random Forest Classifier & Regressor

Visualization: Power BI (KPIs, charts, maps)


## 📄 References

Kaggle Flight Delay Dataset: Link

Python & Scikit-learn Documentation: https://scikit-learn.org

Gradio Documentation: https://gradio.app


## 👤 Author
👨‍💻 Rohit Kolage

📧 Email: rohitkolage091@gmail.com

🔗 LinkedIn: https://www.linkedin.com/in/rohitkolage/

