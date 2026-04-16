# Forest Fire Weather Index (FWI) Prediction

A Flask web application that predicts the Fire Weather Index (FWI) based on meteorological and fire-related inputs using a Ridge Regression model.



## Overview
This application uses a pre-trained Ridge Regression model to estimate the FWI – a numerical rating of fire potential – from nine input variables. The backend is built with Flask, and the frontend provides a simple HTML form for user input.

## Features
- Accepts 9 numerical inputs via a web form
- Scales input features using a fitted `StandardScaler`
- Returns a predicted FWI value
- Handles common errors gracefully

## Installation
- Flask
- numpy 
- pandas
- scikit-learn

### Prerequisites
- Python 3.8 or higher
- pip package manager

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/adamimoro/fwi-prediction.git
   cd fwi-prediction