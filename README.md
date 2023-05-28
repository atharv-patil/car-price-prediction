# Car Price Predictor

![image](https://github.com/atharv-patil/carPricePrediction/assets/83455141/51ccdea6-2f6b-4da3-8d55-2d6d1de00ea1)


Car Price Predictor is a project that aims to predict the prices of used cars based on various features. The project utilizes data obtained from the Quikr website in the form of a CSV file. The data is then processed and cleaned using the NumPy and Pandas libraries, resulting in a cleaned data CSV file. A linear regression model is built using the Scikit-learn library to predict the prices of cars based on the available features.

## Table of Contents
- [Data Cleaning and Model Creation Notebooks](#data-cleaning-and-model-creation-notebooks)
- [Web Application](#web-application)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Installation](#installation)
- [Contributing](#contributing)
- [License](#license)

## Data Cleaning and Model Creation Notebooks

The data cleaning and model creation process is documented in one Jupyter notebooks:

- [Data Cleaning Notebook](https://github.com/atharv-patil/carPricePrediction/blob/main/usedCarPricePrediction.ipynb): This notebook showcases the steps taken to clean and preprocess the raw data obtained from the Quikr website. Various techniques from the NumPy and Pandas libraries are employed to handle missing values, remove duplicates, and ensure the data is suitable for modeling.

- [Model Creation Notebook](https://github.com/atharv-patil/carPricePrediction/blob/main/usedCarPricePrediction.ipynb): This notebook details the creation of the linear regression model using the Scikit-learn library. It includes steps such as feature selection, model training, and evaluation.

## Web Application

The project also includes a small [web application](https://github.com/atharv-patil/carPricePrediction/tree/main/app) built using Flask, HTML, and CSS. The web app allows users to input the necessary car features and obtain a predicted price based on the trained linear regression model. Below is an image of the final web application:

![image](https://github.com/atharv-patil/carPricePrediction/assets/83455141/54c69d32-3b7c-423b-b28e-29ee03a4a629)

## Usage

To use the Car Price Predictor, follow these steps:

1. Install the required dependencies (see [Dependencies](#dependencies) section).
2. Clone the repository: `git clone https://github.com/atharv-patil/carPricePrediction.git`.
3. Navigate to the project directory: `cd car-price-predictor`.
4. Run the web application: `python app.py`.
5. Open your web browser and visit: `http://localhost:5000`.

## Dependencies

The following dependencies are required to run the project:

- Python (version 3.7 or above)
- Flask (version 2.0.1 or above)
- NumPy (version 1.21.0 or above)
- Pandas (version 1.3.0 or above)
- Scikit-learn (version 0.24.2 or above)
- HTML
- CSS

## Installation

1. Clone the repository: `git clone https://github.com/atharv-patil/carPricePrediction`.
2. Navigate to the project directory: `cd carPricePrediction`.
3. Install the required dependencies: `pip install -r requirements.txt`.

## Contributing

Contributions to the Car Price Predictor project are welcome. If you encounter any issues or have suggestions for improvement, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to modify and use the code according to your needs.
