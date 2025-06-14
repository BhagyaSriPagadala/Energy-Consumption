Energy Consumption Forecasting (Building A)

This project forecasts hourly energy usage of a building using machine learning and time-series data. Built in Google Colab using Random Forest, the model uses weather and time-based features to predict future energy consumption.



Features
- Time & lag-based feature engineering
- Model trained on historical data, tested on last 30 days
- Evaluated using MAE and RMSE
- Visualizations: actual vs predicted, error distribution, feature importance


 Results
- **MAE**: 9.13 kWh  
- **RMSE**: 15.17 kWh  


 Tech Stack
- Python, Pandas, Scikit-learn, Matplotlib

 📁 Files
- `notebook/energy_forecast.ipynb` – main notebook
- `requirements.txt` – dependencies
- `README.md` – project overview

> Dataset (`db_building_A.csv`) is excluded due to size/privacy.

 Run the Project
Clone the repo and run the notebook in Google Colab or Jupyter.
```bash
pip install -r requirements.txt
