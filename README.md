# Predict COVID-19 Cases using Facebook Prophet

## Introduction
This project aims to predict COVID-19 cases using time series forecasting techniques, specifically leveraging Facebook Prophet. With the ongoing pandemic, accurate forecasting of COVID-19 cases is crucial for understanding trends, planning healthcare resources, and implementing effective public health interventions. Facebook Prophet provides a powerful toolset for time series forecasting, making it an ideal choice for this task.

## Installation
To run this project locally, follow these steps:

1. Clone this repository to your local machine.
   ```
   git clone https://github.com/vanshi-jain/covid19-project.git
   ```
   
2. Install the required dependencies using pip.
   ```
   pip install -r requirements.txt
   ```

3. Run the main script to generate predictions.
   ```
   python main.py
   ```

## Usage
Once the project is set up, you can customize the forecasting parameters, such as the time horizon for predictions, the granularity of data, and any additional features you want to incorporate into the model. You can also visualize the predictions using the provided plotting functions.

## Data
The data used in this project is sourced from reputable sources such as Johns Hopkins University Center for Systems Science and Engineering (JHU CSSE) COVID-19 Data Repository. It includes information on confirmed COVID-19 cases, deaths, and recoveries, aggregated by date and location.

## Methodology
1. **Data Preprocessing**: Cleaning and preprocessing the raw COVID-19 data to make it suitable for time series forecasting.
   
2. **Model Training**: Using Facebook Prophet to train time series forecasting models on historical COVID-19 data.

3. **Evaluation**: Evaluating the model performance using appropriate metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), or others.

4. **Prediction**: Generating predictions for future COVID-19 cases based on the trained models.

## Acknowledgements
I would like to thank Facebook for developing Prophet and the contributors to the COVID-19 datasets used in this project. Their efforts are instrumental in advancing our understanding of the pandemic and aiding in the development of effective response strategies.

---
