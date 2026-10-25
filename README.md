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

Project Structure

ML-Project-Health-Insurance-premium-prediction/
├── artifacts/              # Saved model and/or supporting artifacts
├── main.py                 # Streamlit application entry point
├── prediction_helper.py    # Prediction and preprocessing logic
├── requirements.txt        # Python dependencies
└── README.md               # Project documentation

Run Locally
1. Clone the repository:
   
   git clone https://github.com/iampavank2003-sys/ML-Project-Health-Insurance-premium-prediction.git

   cd ML-Project-Health-Insurance-premium-prediction
   
3. Create and activate a virtual environment (Windows Command Prompt):
   
   python -m venv venv
   
   venv\Scripts\activate
   
5. Install dependencies:
   
   python -m pip install -r requirements.txt
   
6. Start the Streamlit app:
   
   python -m streamlit run main.py
   
7. Open the local URL shown in your terminal (usually http://localhost:8501).

Repository

Source code:

https://github.com/iampavank2003-sys/ML-Project-Health-Insurance-premium-prediction

Future Improvements

- Add model evaluation metrics and a clear explanation of the training process.
- Improve input validation and error handling.
- Add more test cases and document the model's limitations.
- Add screenshots and example inputs/outputs to this README.

Disclaimer

This application is intended for learning and demonstration purposes. Actual insurance premiums depend on insurer-specific rules, underwriting, policy details, and other factors not necessarily represented by this model.
