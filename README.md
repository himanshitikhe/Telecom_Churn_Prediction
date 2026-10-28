📊 Telecom Customer Churn Prediction

 A Machine Learning web application built with Python, Scikit-learn, and Streamlit that predicts whether a telecom customer is likely to churn (leave the service)  based on customer information.

📌 Features
- Predicts customer churn using a trained Machine Learning model.
- Interactive Streamlit web interface.
- User-friendly input forms.
- Displays churn prediction and probability.
- Fast and easy to use.

🛠️ Technologies Used
- Python
- Streamlit
- Pandas
- NumPy
- Scikit-learn
- Joblib

📂 Project Structure

Telecom_Churn_Prediction

│── app.py

│── best_model.pkl

│── scaler.pkl

│── requirements.txt

│── README.md

│── Telecom_Customer_Churn.csv



⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/himanshitikhe/Telecom_Churn_Prediction.git
```

Move into the project folder:

```bash
cd Telecom_Churn_Prediction
```

Install the required packages:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
streamlit run app.py
```

📊 Input Features

The model uses customer information such as:
- Gender
- Senior Citizen
- Partner
- Dependents
- Tenure
- Phone Service
- Multiple Lines
- Internet Service
- Online Security
- Online Backup
- Device Protection
- Tech Support
- Streaming TV
- Streaming Movies
- Contract Type
- Paperless Billing
- Payment Method
- Monthly Charges
- Total Charges

🎯 Output

The application predicts:

- ✅ Customer is likely to stay
- ⚠️ Customer is likely to churn

It also displays the churn probability.

📈 Machine Learning Model

- Algorithm: Random Forest Classifier *(or replace with the algorithm you actually used)*
- Data Preprocessing:
  - Label Encoding
  - Feature Scaling
- Evaluation Metrics:
  - Accuracy
  - Precision
  - Recall
  - F1 Score

👩‍💻 Author

Himanshi Tikhe

LinkedIn: https:www.linkedin.com/in/hptikhe

GitHub: https://github.com/himanshitikhe

⭐ If you found this project useful, consider giving it a star!
