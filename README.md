Healthcare Insurance Premium Prediction

A machine-learning web application that predicts an estimated health insurance premium from user-provided information. The app provides an interactive interface built with Streamlit and connects the interface to the project's prediction logic.

Live Demo
Try the deployed app:
https://ml-project-health-insurance-premium-prediction-bypk.streamlit.app/

Project Overview
This project demonstrates an end-to-end machine-learning application: users enter details in the web interface, the application passes the input to the prediction helper, and the model returns an estimated insurance premium.

Note: Predictions are estimates from the project's model and should not be treated as official insurance quotes or financial advice.

Technology Stack
- Python — application and prediction logic
- Streamlit — interactive web interface
- Pandas / NumPy — data handling and numerical operations
- Scikit-learn — machine-learning utilities
- XGBoost — model support, if used by the saved model in this project
- PyArrow — data interchange dependency
- Git and GitHub — version control and source code hosting
- Streamlit Community Cloud — deployment

- ML-Project-Health-Insurance-premium-prediction/
  
├── artifacts/              # Saved model and/or supporting artifacts

├── main.py                 # Streamlit application entry point

├── prediction_helper.py    # Prediction and preprocessing logic

├── requirements.txt        # Python dependencies

└── README.md               # Project documentation

Disclaimer

This application is intended for learning and demonstration purposes. Actual insurance premiums depend on insurer-specific rules, underwriting, policy details, and other factors not necessarily represented by this model.
