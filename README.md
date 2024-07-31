
# Batman Forest Fire ML Model

## Description

This project utilizes machine learning to predict the Fire Weather Index (FWI) based on various meteorological parameters. The application is built using Flask, a lightweight web framework for Python, and incorporates a Ridge Regression model to make predictions. The model is trained on forest fire data to provide accurate and timely predictions for fire risk assessment.

### Features

- Web-based interface for predicting FWI based on user inputs.
- Suggestive values for each input field to guide users.
- Dynamic styling inspired by the Gotham City theme from the Batman universe.

## Getting Started

### Prerequisites

- Python 3.x
- Flask
- Scikit-learn
- Pickle (for model and scaler serialization)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/GamingFate/Batman_Forest_Fire_Ml_Model.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Batman_Forest_Fire_Ml_Model
   ```

3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the Flask application:
   ```bash
   python app.py
   ```

5. Open a web browser and go to `http://127.0.0.1:5000` to view the application.

## Usage

- Enter the meteorological parameters into the form fields.
- Click the "Predict" button to receive the FWI prediction.
- Suggested values for each parameter are provided to assist in entering data.

## Author

Naman Bhasin
