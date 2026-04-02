# Titanic-Survival-Prediction


This is an **interactive web app** built using **Python and Streamlit**.  
In this app, you can enter **Titanic passenger details** and it will predict whether the passenger **survived or not (Survived/Not Survived)**.

## Features

- Enter passenger details:
  - Passenger Class (1st, 2nd, 3rd)
  - Sex (Male/Female)
  - Age
  - Fare
  - Port of Embarkation (C, Q, S)

- Predict survival:
  - **Survived ✅** or **Not Survived ❌**
  - Probability and Confidence displayed

## How to Run

1. Install required Python libraries:
```bash
pip install pandas scikit-learn streamlit
streamlit run app.py
