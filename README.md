
# Weather Prediction using Machine Learning
This project focuses on predicting daily maximum temperatures using machine learning techniques. The dataset used for training and testing the model is stored in the "local_Weather.csv" file.

![Logo](https://img.freepik.com/premium-vector/rain-season-icon-colored-shapes_1076610-3498.jpg?w=740)


## Code Description 
The source code is written in Python using the pandas library for data manipulation and scikit-learn for machine learning. Here's the roadmap for the code:


## Roadmap

-  Data Preprocessing: Reads the weather data from a CSV file (local_weather.csv). Handles missing values and removes unnecessary columns.Converts the date column to a datetime index.

- Exploratory Data Analysis: Analyzes precipitation and temperature data. Plots temperature data over time.

- Model Training: Utilizes the Ridge regression model for temperature prediction. Defines predictors, splits data into training and testing sets, and trains the model.

- Model Evaluation: Uses Mean Squared Error (MSE) as the evaluation metric. Plots the actual vs. predicted temperatures.

- Feature Engineering: Creates additional features such as monthly averages, day-of-year averages, etc. Incorporates these features into the model for improved predictions.

- Results Analysis: Calculates correlation coefficients and identifies the largest prediction errors.




## Installation

- Ensure you have Python installed on your machine.

- Install the required libraries using 

```bash
  pip install pandas scikit-learn
```
- Download the 'local_weather.csv' and Upload it with Project.

- Execute the code in a Python environment.
## Documentation

Make sure to look at this documentation for understanding purpose.

[Documentation](https://www1.ncdc.noaa.gov/pub/data/cdo/documentation/GHCND_documentation.pdf)


## Dependencies

- pandas

- scikit-learn
## Authors

Feel free to edit the code according to your needs. If you face any issue or have suggestions for improvement, please open an issue or submit a pull request. 

Happy coding 🌦️

