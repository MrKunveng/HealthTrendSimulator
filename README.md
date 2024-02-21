HealthTrendSimulator

Overview

HealthTrendSimulator is an advanced Python tool designed to generate synthetic health data for a large number of patients over time. It simulates various health metrics such as temperature, blood pressure, heart rate, respiration rate, height, weight, Body Mass Index (BMI), and assigns risk levels for cardiovascular diseases (CVD) and diabetes based on these simulated metrics. Additionally, it proposes recommended actions based on the risk levels identified, creating a comprehensive dataset that mimics real-world medical patient data.

Purpose

The tool serves as a vital resource for:

Training Reinforcement Learning (RL) models for remote healthcare monitoring systems, facilitating the development of algorithms that can predict health risks and recommend interventions without direct human oversight.
Providing researchers, data scientists, healthcare professionals, and developers working in the medical field with a rich dataset for developing and testing medical data analysis tools.
Enhancing health monitoring systems through the simulation of realistic patient scenarios, especially in environments where access to real patient data is restricted.
This tool is particularly useful in scenarios where access to real patient data is limited due to privacy concerns, regulatory restrictions, or ethical considerations.

Features

Synthetic Patient Data Generation: Generates data for 5000 patients with configurable parameters.
Health Metrics Simulation: Simulates temperature, blood pressure, heart rate, respiration rate, and BMI.
Risk Level Assessment: Determines risk levels for CVD and diabetes.
Treatment Action Simulation: Recommends actions based on risk levels, perfect for RL model training.
Time Series Data: Produces data over a specified period, simulating changes in health metrics and risk levels.
Installation

Ensure you have Python 3.6 or later installed on your system. You can then install the required dependencies using pip:

bash
Copy code
pip install numpy pandas
Usage

To generate the dataset, simply run the script:

bash
Copy code
python HealthTrendSimulator.py
The output will be a CSV file named medical_data_with_trend.csv, located in the same directory as the script. This file contains the simulated health data for analysis or model training.

Customization

Users can customize the constants at the top of the script to simulate different patient demographics or health conditions. These constants include number of patients, age range, normal and abnormal ranges for temperature and blood pressure, and more.

Contribution

Contributions to HealthTrendSimulator are welcome, including feature enhancements, bug fixes, and documentation improvements. Please feel free to fork the repository, make your changes, and submit a pull request.
