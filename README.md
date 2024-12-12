https://rain-prediction-auoi.onrender.com/

# Rain Prediction Application 🌧️  

## Overview  
This project is an end-to-end machine learning application designed to predict whether it will rain the next day in Australia. It is built using Python and Flask and includes a Power BI dashboard for visualizing insights derived from the dataset.  

The application processes historical weather data, applies machine learning algorithms, and provides predictions while enabling users to explore insights interactively through Power BI visualizations.  

---

## Features  
- **Rain Prediction**: Predicts the likelihood of rain for the next day based on user input or existing data.  
- **Power BI Dashboard**: Offers rich and interactive visualizations to analyze trends and patterns in the dataset.  
- **End-to-End Pipeline**: Covers data preprocessing, model training, evaluation, deployment, and visualization.  

---

## Dataset  
- **Source**: Australian weather dataset.  
- **Description**: Contains historical weather observations and rain data used for feature engineering and prediction.  

---

## Technologies Used  
- **Programming Language**: Python  
- **Framework**: Flask  
- **Machine Learning**: Scikit-learn  
- **Data Visualization**: Power BI  
- **Data Processing**: Pandas, NumPy  
- **Deployment**: Flask for backend integration  

---

## Application Workflow  
1. **Data Preprocessing**:  
   - Handles missing values, categorical encoding, and feature scaling.  
   - Splits data into training and testing sets.  

2. **Model Training**:  
   - Trained a classification model to predict rain using features such as temperature, humidity, and wind.  

3. **Prediction**:  
   - Allows users to input weather conditions to predict rain.  

4. **Power BI Dashboard**:  
   - Visualizations include:  
     - Rainfall trends over time.  
     - Correlation heatmaps.  
     - Feature importance and distribution analysis.  

5. **Deployment**:  
   - Flask serves the application, enabling interaction via a web interface.  

---

## Installation and Setup  
### Prerequisites  
- Python 3.7+  
- Power BI Desktop (for dashboard editing)  

### Steps  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/your-username/rain-prediction-app.git  
   cd rain-prediction-app  
   ```  

2. Install dependencies:  
   ```bash  
   pip install -r requirements.txt  
   ```  

3. Run the Flask app:  
   ```bash  
   python app.py  
   ```  

4. Access the application:  
   - Open your browser and go to `http://127.0.0.1:5000/`.  

5. Open Power BI:  
   - Load the `rain_prediction_dashboard.pbix` file to view insights.  

---

## Project Structure  
```plaintext  
rain-prediction-app/  
│  
├── static/             # Static files (CSS, JS)  
├── templates/          # HTML templates for Flask  
├── data/               # Dataset and preprocessing scripts  
├── models/             # Machine learning model files  
├── app.py              # Flask application script  
├── dashboard.pbix      # Power BI dashboard file  
├── requirements.txt    # Project dependencies  
└── README.md           # Project documentation  
```  

---

## Usage  
- **Prediction**: Input weather parameters on the web interface to predict rain for the next day.  
- **Dashboard**: Open the Power BI file to explore insights and visualizations.  

---

## Future Enhancements  
- Add real-time weather data integration.  
- Support for additional countries and datasets.  
- Enhance dashboard interactivity with advanced analytics.  

---

## Acknowledgments  
- Dataset provided by [Australian Bureau of Meteorology](http://www.bom.gov.au).  
- Libraries: Scikit-learn, Flask, Pandas, NumPy, Power BI.  

---
