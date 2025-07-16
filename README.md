🔮 Customer Churn Prediction App
A machine learning web application developed with Streamlit to predict customer churn for a telecom service provider. The app uses a fully automated preprocessing pipeline and a Logistic Regression model trained on the Telco Customer Churn dataset. It offers real-time predictions and is deployable via Streamlit Cloud.

🚀 Live Demo
🔗 Launch the App
https://customerchurn-acb7ntfxbc6lnr3xtcox4i.streamlit.app/

💡 Key Features
📋 Intuitive web interface for customer input

⚡ Real-time churn prediction with probability scores

🧪 End-to-end ML pipeline from preprocessing to inference

🔁 Easily extendable to other models (e.g., Random Forest, XGBoost)

☁️ Fully deployed and accessible via Streamlit Cloud

📦 Tech Stack
Layer	Tools / Libraries
Frontend	Streamlit (UI and user interaction)
Backend / ML	Scikit-learn, Pandas, NumPy
Deployment	Streamlit Cloud
Serialization	Joblib (for model persistence)

🧠 Machine Learning Model
Algorithm: Logistic Regression with class_weight="balanced"

Preprocessing Pipeline:

Numerical Features:

Imputation: Median strategy

Scaling: StandardScaler

Categorical Features:

Imputation: Most frequent strategy

Encoding: OneHotEncoder

Hyperparameter Tuning: GridSearchCV

Performance Metrics:

Validation Accuracy: ~80%

Test Accuracy: ~79%

ROC AUC Score: ~82%

📊 Dataset Overview
Dataset: Telco Customer Churn

Source: Kaggle - Telco Churn Dataset

Size: ~7,000 records

Target Variable: Churn (Yes / No)

📁 Project Structure
graphql
Copy
Edit
📦 customer-churn-app/
├── 📁 data/                  # Raw or processed dataset files
├── 📁 model/                 # Saved models and transformers
├── 📁 notebook/              # EDA and training notebooks
├── 📁 app/                   # Streamlit app files
│   ├── app.py               # Main application script
│   └── utils.py             # Helper functions for inference
├── requirements.txt         # Project dependencies
├── README.md                # Project documentation
└── .gitignore               # Git ignore rules
📌 How to Run Locally
Clone the repository:

bash
Copy
Edit
git clone https://github.com/shah5676/customer_churn.git
cd customer-churn-app
Create a virtual environment and install dependencies:

bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
Launch the Streamlit app:

bash
Copy
Edit
streamlit run app/app.py
📬 Contact
For questions, feedback, or collaboration opportunities:

Name: Syed Muhammad Hassaan Shah
Email: hassaanshah728@gmail.com
GitHub: @shah5676



