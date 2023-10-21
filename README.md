# Energy Consumption Prediction with K-Nearest Neighbors (KNN)

![GitHub repo size](https://img.shields.io/github/repo-size/hasali-coder/Building-Energy-Consumption-Model-Project)
![GitHub issues](https://img.shields.io/github/issues/hasali-coder/Building-Energy-Consumption-Model-Project)
![GitHub stars](https://img.shields.io/github/stars/hasali-coder/Building-Energy-Consumption-Model-Project)
![GitHub forks](https://img.shields.io/github/forks/hasali-coder/Building-Energy-Consumption-Model-Project)
## Overview

This project aims to predict energy consumption in buildings equipped with HVAC systems using the K-Nearest Neighbors (KNN) algorithm. The project leverages various features to estimate energy usage, helping homeowners, businesses, and energy providers optimize energy consumption and reduce costs.

## Table of Contents

- [Dataset](#dataset)
- [Usage](#usage)
- [Features](#features)
- [Model Training](#model-training)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Dataset

The dataset contains information on room area, the number of appliances, outside temperature, insulation thickness, building type, HVAC system type, and average temperature over the last 24 hours, as well as energy consumption (kWh) for various buildings. The dataset is available in [dataset.csv](dataset.csv).

## Usage

To use this project, follow these steps:

1. Clone this repository: `git clone https://github.com/hasali-coder/Building-Energy-Consumption-Model-Project/tree/main.git`
2. Navigate to the project directory: `Building-Energy-Consumption-Model-Project`
3. Install the required dependencies: `pip install -r requirements.txt`
4. Run the model training script: `python train_model.py`
5. Predict energy consumption for new buildings: `python predict_energy.py`

## Features

The project includes the following features:

- Room Area (sq. ft.)
- Number of Appliances
- Outside Temperature (°C)
- Insulation Thickness (inches)
- Building Type (Categorical)
- HVAC System (Categorical)
- Average Temperature in last 24 hours (°C)

## Model Training

I train a predictive model using the Random Forest Regressor to estimate energy consumption based on the provided features. The model's performance is evaluated using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R2).

## Results

The trained model achieved the following results:

- Mean Absolute Error: 7.61
- Mean Squared Error: 67.96
- Root Mean Squared Error: 8.24
- R-squared: 0.957

## Contributing

Contributions to this project are welcome. Feel free to open issues or pull requests. If you have suggestions or improvements, please let us know.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

