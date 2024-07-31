
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

##  The Fire Weather Index (FWI) is a numerical representation of fire danger, and its interpretation depends on its value. Here’s a breakdown of how to interpret FWI values and their implications:

## Interpreting FWI Values
Negative Values

Implication: In practice, FWI values are typically non-negative, as they are derived from a combination of indices that are inherently positive. A negative value might indicate an issue with the data or calculations.
Action: Verify data inputs and calculation methods if a negative value appears.
Low FWI Values (e.g., 0 to 5)

Implication: Indicates low fire risk. Conditions are generally moist or unfavorable for fire ignition and spread.
Action: Normal fire management practices; low concern for wildfire outbreaks.
Moderate FWI Values (e.g., 6 to 15)

Implication: Represents moderate fire risk. Fire danger is present but manageable with typical fire prevention and control measures.
Action: Stay alert and monitor conditions closely; prepare for potential fire activity.
High FWI Values (e.g., 16 to 30)

Implication: Indicates high fire risk. Conditions are dry and conducive to fire spread. Fire behavior can be aggressive.
Action: Implement enhanced fire prevention measures; be prepared for rapid response if fires occur.
Very High to Extreme FWI Values (e.g., 31 and above)

Implication: Represents very high to extreme fire risk. Conditions are highly favorable for fire spread and can lead to significant fire behavior.
Action: Exercise extreme caution; implement robust fire management strategies and prepare for potential large-scale fires.  

## Author

Naman Bhasin
