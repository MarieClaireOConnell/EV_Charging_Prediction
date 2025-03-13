# EV Charging Prediction Project

## Overview
This project explores the use of machine learning and deep learning models to predict energy consumption and regenerated energy for electric vehicles (EVs). By leveraging a publicly available dataset containing various EV performance metrics, the study aims to optimize battery usage and assist EV users in better managing their vehicle's energy consumption.

## Authors
- Amber J. Lee
- Marie Claire O'Connell
- Paul C. Vose

## Course Information
**IMT 575 A Au 24: Data Science III: Scaling, Applications, and Ethics**  
Date: November 24, 2024

## Project Goals
1. Predict **Regenerated Energy** using machine learning models.
2. Predict **Total Energy Consumed (kWh)** using machine learning and deep learning models.
3. Optimize hyperparameters to improve model accuracy.
4. Provide insights for **battery management** and **driving optimization**.

## Dataset
- **Source**: [DOE EV Data Collection - Livewire Energy](https://livewire.energy.gov/ds/calstart/vehicle)
- **Features**: Includes driving time, idling time, total distance, SOC used, and other onboard recorded metrics.

## Machine Learning Models
1. **Linear Regression** – Used for initial exploratory analysis.
2. **Gradient Boosting Regression** – Built to predict regenerated energy.
3. **Random Forest Regression** – Created to predict total energy consumption.

## Deep Learning Model
- **Fully Connected Neural Network (FCNN)**
  - Iterative hyperparameter tuning improved model performance.
  - Achieved a reduction in **Mean Absolute Error (MAE)** from **21.19 → 0.2198** through multiple iterations.
  - Included optimizations like **batch normalization**, **dropout regularization**, and **log transformation**.

## Project Files
- `EV_vehicle_11_23.ipynb` - Initial model training and evaluation.
- `EV_vehicle_Third_Iteration_Fully_Connected_Neural_Network_number_of_trips.ipynb` - Final FCNN iteration with hyperparameter tuning.
- `9.11 Final Project Write-Up.docx` - Detailed project report.

## Results & Insights
- **Regression models** successfully predicted regenerated energy and total energy consumption.
- **Hyperparameter tuning** significantly improved the accuracy of the FCNN model.
- The project demonstrated **practical applications** for battery management and EV optimization.

## Future Work
- Deploying the model for real-time EV monitoring.
- Incorporating additional features like weather conditions and traffic data.
- Further fine-tuning model architectures for better accuracy.

## Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/EV_Charging_Prediction.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter notebooks to explore and test models.


This project was completed as part of the University of Washington's MSIM—Data Science III: Scaling, Applications, and Ethics.

