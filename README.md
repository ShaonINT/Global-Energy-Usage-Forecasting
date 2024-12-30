# Global Energy Consumption Forecasting (2020-2040) Using LSTM and ARIMA

### Project Overview

This project demonstrates the application of machine learning and statistical models to forecast energy consumption across multiple countries and energy sources. By combining deep learning (LSTM) and ARIMA, it addresses challenges like limited data availability, ensuring accurate and reliable predictions. The dataset contains the global energy usage of different countries till 2019. This project deployed LSTM model for the time-series forecasting. LSTMs (Long Short-Term Memory) are considered excellent for time series analysis because they can effectively capture long-term dependencies within sequential data, meaning they can remember relevant information from previous time steps, making them ideal for predicting future values based on past trends and patterns in time series data.

Key Features
- **Hybrid Modeling Approach**:
  - **LSTM**: Used for datasets with adequate historical data, leveraging deep learning for time series forecasting.
  - **ARIMA**: Employed for datasets with limited historical data, showcasing flexibility and adaptability.
- **Comprehensive Analysis**:
  - Covers energy consumption forecasting for 8 energy sources.
- **Scalability**:
  - Designed to handle multiple datasets, ensuring robustness and generalizability.
- **Visualization**:
  - Presents historical and forecasted data through clear and concise visualizations.
Skills and Tools
- **Machine Learning**: LSTM (Bidirectional), Sequential Models, TimeSeriesSplit, Early Stopping, ReduceLROnPlateau.
- **Statistical Modeling**: ARIMA for low-data scenarios.
- **Libraries Used**: Python: `numpy`, `pandas`, `tensorflow`, `keras`, `statsmodels`, `scikit-learn`, `matplotlib`.
- **Data Preprocessing**: Scaling with `MinMaxScaler`. Time series sequence creation.
- **Visualization**: `matplotlib` for plotting historical vs. forecasted data.
Project Workflow
1. **Data Preparation**:
   - Cleaned and preprocessed energy consumption data of 8 energy sources.
   - Filtered historical data from 1989 to 2013 for training.
2. **Hybrid Modeling**:
   - Used LSTM models for sources with sufficient historical data.
   - Applied ARIMA models for sources with limited historical data.
3. **Model Evaluation**:
   - TimeSeriesSplit for cross-validation.
   - Metrics like RMSE for performance evaluation.
4. **Forecasting**:
   - Predicted energy consumption from 2020 to 2040 for each country and energy source.
5. **Visualization**:
   - Created intuitive plots comparing historical and forecasted data.

### Key Insights

- **Accurate Predictions**: LSTM performed well for datasets with abundant historical data.
- **Real-World Relevance**: Insights from this project can assist in energy policy-making, resource optimization, and sustainability planning.

Visualization Examples
### Historical vs. Forecasted Energy Consumption

![output](https://github.com/user-attachments/assets/62cbe882-26df-4734-be14-2f246203537f)


### Results
- **Hybrid Model Performance**: LSTM achieved low RMSE for datasets with sufficient data. ARIMA ensured reasonable accuracy for sparse datasets.
- **Scalability**: Successfully forecasted energy trends across multiple countries and sources.
Challenges and Solutions
- **Limited Historical Data**: Addressed by incorporating ARIMA models for low-data scenarios.
- **Overfitting in LSTM**: Mitigated using TimeSeriesSplit, Early Stopping, and ReduceLROnPlateau.
Future Work
- **Enrich Dataset**: Integrate additional features like population growth, GDP, or renewable energy investments.
- **Model Comparison**: Perform a detailed comparison of hybrid models vs. other approaches (e.g., XGBoost).
- **Deployment**: Build an interactive dashboard or web app for real-time forecasting.

### How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/ShaonINT/Global-Energy-Usage-Forecasting.git
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Energy_Consumption_Forecasting_Hybrid.ipynb
   ```

### Contact

For any questions or collaborations, feel free to reach out:
- **Name**: Shoan Biswas
- **Email**: biswas.shaon@gmail.com
- **LinkedIn**: https://www.linkedin.com/in/shaonbiswas/
