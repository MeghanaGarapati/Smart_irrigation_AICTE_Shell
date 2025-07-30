# Smart_irrigation_AICTE_Shell
This is an AICTE Internship Cycle-2
# Smart Irrigation System
An automated smart irrigation system that uses soil moisture sensors and machine learning to optimize water usage and improve crop productivity.
##  Project Overview
This project aims to tackle the common issue of over- or under-watering in agriculture by using real-time sensor data and predictive models. The system determines which zones of the farmland need irrigation and actuates pumps accordingly — reducing manual labor and conserving water.
## Features
- Monitors moisture from **19 soil sensors** across different land parcels
- Predicts sprinkler status using a **trained machine learning model**
- Controls **3 water pumps** automatically based on prediction
- Interactive **Streamlit web application** for user inputs and predictions
- Real-time and scalable solution for precision farming
##  Technologies Used
- **Python**
- **Machine Learning** – scikit-learn
- **Streamlit** – for UI
- **Joblib** – to load ML model
- **NumPy** – for array handling
- Optional: ESP32, Firebase, Arduino (for hardware extension)
##  Methodology
1. **Data Collection**: Moisture readings from 19 sensors
2. **Data Preprocessing**: Cleaned and scaled data
3. **Model Training**: ML model trained to classify sprinkler ON/OFF
4. **Web App Interface**: Developed using Streamlit
5. **Pump Control**: Based on model output, pumps are actuated automatically
