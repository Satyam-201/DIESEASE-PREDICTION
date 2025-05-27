🧠 Disease Prediction System using Machine Learning
This is a web-based application built with Streamlit that uses machine learning models to predict the likelihood of the following diseases based on user input:

🩸 Diabetes

❤️ Heart Disease

🧬 Parkinson’s Disease

The system uses pre-trained ML models and StandardScaler to ensure accurate predictions, with a user-friendly interface for entering medical parameters. It's intended as a health-assisting tool for educational or demonstration purposes.

🔧 Features
Interactive and intuitive UI using Streamlit

Model support for:

Diabetes Prediction

Heart Disease Prediction

Parkinson's Disease Prediction

Real-time prediction with input validation

Scalable and modular code structure

Sidebar navigation menu for easy access to each prediction model

🧠 Tech Stack
Python

Streamlit

Scikit-learn

Numpy

Pickle (for saving/loading models and scalers)

📂 Project Structure
bash
Copy
Edit
├── app.py                        # Main Streamlit application
├── saved_demo_model/            # Contains pre-trained models and scalers
│   ├── diabetes_model.sav
│   ├── heart_model.sav
│   ├── parkinsons_model.sav
│   ├── Di_scaler.sav
│   ├── heart_scaler.sav
│   └── parkinsons_scaler.sav
🚀 How to Run
Clone the repository

bash
Copy
Edit
git clone https://github.com/Satyam-201/DIESEASE-PREDICTION.git
cd disease-prediction-system
Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
Run the app

bash
Copy
Edit
streamlit run app.py
⚠️ Disclaimer
This project is not intended for real-world medical diagnosis. It is designed for educational and demonstration purposes only. Please consult healthcare professionals for any medical concerns.
