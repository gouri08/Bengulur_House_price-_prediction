🏠 Bengaluru Home Price Predictor

A Machine Learning-powered web app to predict house prices in Bengaluru based on location, square footage, number of bathrooms, and bedrooms. Built using Python, Streamlit, and scikit-learn.

🚀 Live Demo
🔗 https://homepricepredictor-n2z3vpznys3ymt3o5vbtmt.streamlit.app/

📌 Features
Predicts house price instantly.

User-friendly Streamlit UI.

Select location from preloaded dataset.

Accepts inputs for:

Location

Square footage (min 300 sqft)

Number of bathrooms (min 1)

Number of bedrooms (min 1)

Displays price in Indian Rupees (₹).

📂 Project Structure
bash
Copy
Edit
.

├── Bengaluru_House_Data.csv      # Raw dataset

├── copied.csv                    # Processed dataset for prediction

├── model.ipynb                   # Jupyter Notebook for model building

├── model.pkl                     # Trained ML model

├── frontend.py                   # Streamlit frontend code

└── README.md                     # Project documentation
