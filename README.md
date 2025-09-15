🩺 Breast Cancer Predictor App

This project is an interactive Breast Cancer Predictor web app built with Streamlit. It uses a Logistic Regression model trained on the Breast Cancer Wisconsin dataset to predict whether a breast mass is benign or malignant based on cytology lab measurements.

🚀 Features

📊 Interactive Sliders: Input cell nuclei measurements such as radius, texture, perimeter, smoothness, etc.

🤖 Machine Learning Model: Logistic Regression trained on preprocessed breast cancer dataset.

⚡ Real-time Prediction: Instantly shows prediction results when user adjusts input values.

🌐 Web-based UI: Built with Streamlit, lightweight, and easy to deploy.

📂 Project Structure
BreastCancerPredictorApp/
│── data/
│   └── data.csv                # Dataset used for training
│── model/
│   ├── model.pkl               # Trained logistic regression model
│   └── scaler.pkl              # Scaler for input normalization
│── app/
│   └── main.py                 # Streamlit app code
│── README.md                   # Project documentation

⚙️ Installation

Clone the repository and install dependencies:

git clone https://github.com/yourusername/BreastCancerPredictorApp.git
cd BreastCancerPredictorApp
pip install -r requirements.txt

▶️ Usage

Run the Streamlit app with:

streamlit run app/main.py


The app will open in your browser at http://localhost:8501.

📊 Dataset

Source: Breast Cancer Wisconsin (Diagnostic) Dataset

Features: 30 cell nuclei measurements (radius, texture, perimeter, smoothness, etc.)

Target:

0 = Benign

1 = Malignant

🧠 Model

Algorithm: Logistic Regression

Libraries: scikit-learn, pandas, numpy, plotly, pickle

Preprocessing: Feature scaling using StandardScaler.

💡 Future Improvements

Add more ML models (Random Forest, SVM, Neural Networks).

Improve UI with probability outputs and confidence scores.

Deploy to Streamlit Cloud or Heroku.

📜 License

This project is open-source and available under the MIT License.
