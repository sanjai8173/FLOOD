# Real-Time Flood Prediction using Machine Learning and IoT

This project aims to predict flood occurrences in urban areas in real-time using machine learning techniques and IoT devices. By leveraging data from IoT sensors, such as maximum temperature, rain level, and humidity, the project provides timely and accurate flood occurrence predictions, contributing to effective early warning systems.

## Features

- Real-time data collection from IoT devices for maximum temperature, rain level, and humidity.
- Data preprocessing and cleaning to ensure data quality and reliability.
- Feature engineering and selection to extract meaningful features for modeling.
- Random Forest machine learning model for flood prediction.
- Real-time data processing and integration for up-to-date predictions.
- Visualization of predictions and sensor data through interactive dashboards.

## Requirements

- Python 3.x
- Libraries: pandas, scikit-learn, matplotlib, requests, BeautifulSoup

## Installation

1. Clone the repository:

```shell
git clone https://github.com/your-username/real-time-flood-prediction.git

    Install the required dependencies:

shell

pip install -r requirements.txt

Usage

    Configure the IoT devices to collect real-time data for maximum temperature, rain level, and humidity.

    Run the data collection script to gather the sensor data:

shell

python data_collection.py

    Preprocess the collected data to handle missing values and normalize the features:

shell

python data_preprocessing.py
