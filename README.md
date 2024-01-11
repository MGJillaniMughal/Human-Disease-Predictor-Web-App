# Human-Disease Predictor Web App


## Description

The Human-Disease Predictor Web App is a Flask-based application that uses machine learning models to predict various diseases, including COVID-19, brain tumors, Alzheimer's, diabetes, pneumonia, and breast cancer.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Models and Data](#models-and-data)
- [Technologies Used](#technologies-used)
- [Deployment](#deployment)
- [Credits](#credits)
- [License](#license)
- [Contact](#contact)

## Installation

To run the web app locally, follow these steps:

1. Clone the repository: `git clone https://github.com/MGJillaniMughal/Human-Disease-Predictor-Web-App.git`
2. Install the required dependencies: `pip install -r requirements.txt`
3. Run the Flask application: `python app.py`

## Usage

1. Access the web app by visiting http://localhost:5000 in your web browser.
2. Choose the disease you want to predict from the homepage.
3. Enter the required information or upload an image as per the disease prediction requirements.
4. Click on the "Submit" button to get the prediction result.

## Models and Data

The web app uses various machine learning models for disease prediction. The models and data used for each disease are as follows:

- COVID-19: Trained deep learning model (covid.h5).
- Brain Tumor: Trained deep learning model (braintumor.h5).
- Alzheimer's: Trained deep learning model (alzheimer_model.h5).
- Diabetes: Trained sklearn model (diabetes.sav).
- Pneumonia: Trained deep learning model (pneumonia_model.h5).
- Breast Cancer: Trained sklearn model (cancer_model.pkl).

## Technologies Used

- Flask
- OpenCV
- TensorFlow
- scikit-learn
- Bootstrap
- JavaScript
- jQuery

## Deployment

The web app is deployed on Heroku. You can access it at [Heroku App Link](https://your-heroku-app-link).

## Credits

- The machine learning models used in this project were trained on publicly available datasets from various sources.
- Special thanks to [Contributor Name](https://github.com/username) for providing support and feedback during the development process.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

If you have any questions or feedback, feel free to contact me at your-email@example.com or [create an issue](https://github.com/MGJillaniMughal/Human-Disease-Predictor-Web-App/issues).
