# ANN-Classifier-App
## Customer Churn Prediction App
This is an interactive Streamlit web app that predicts the probability of a bank customer churning (i.e., leaving the bank). The model is built using TensorFlow and uses various customer attributes such as age, geography, credit score, balance, etc., to make predictions.

# Features
Predicts churn probability using a trained neural network model (model.h5)

Encodes input using pre-saved:

LabelEncoder (for gender)

OneHotEncoder (for geography)

StandardScaler (for numerical features)

Interactive UI using Streamlit sliders and dropdowns

# Technologies Used
Python

TensorFlow / Keras

Scikit-learn (for preprocessing)

Streamlit (for UI)

Pandas / NumPy

Pickle (for saving encoders and scalers)

# How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/customer-churn-streamlit.git
cd customer-churn-streamlit
Install dependencies:

bash
Copy
Edit
pip install -r req.txt
Ensure the following files are present in the same directory:

model.h5

label_encoder.pkl

one_hot_encoder.pkl

scaler.pkl

Run the app:

bash
Copy
Edit
streamlit run app.py

## Model Input Features
Geography (One-hot encoded)

Gender (Label encoded)

Age

Tenure

Credit Score

Balance

Number of Products

Has Credit Card (0/1)

Is Active Member (0/1)

Estimated Salary

# Output
Churn Probability (0.00 to 1.00)

Human-readable message on whether the customer is likely to churn

