DiabetesPrediction
A Machine Learning Project for Predicting Diabetes Risk

Developed by Kommana Pavani as part of the Machine Learning 100‑Hour Course under Think AI CEO.

🚀 Overview
This project implements a predictive model to determine the likelihood of diabetes in individuals based on health parameters. 
Leveraging the well-known Pima Indians dataset and machine learning techniques, it aims to facilitate early detection and promote health awareness.

🛠 Features
Data Preprocessing: Handling missing values, feature scaling and normalization.

Exploratory Data Analysis (EDA): Visualization and correlation analyses.

Multiple Classification Models: Logistic Regression, Decision Tree, K‑Nearest Neighbors, Random Forest, Support Vector Machine.

Evaluation Metrics: Accuracy, Precision, Recall, F1‑score, ROC‑AUC.

Model Comparison: Cross-validation to identify the best-performing classifier.

📁 Project Structure
graphql
Copy
Edit
DiabetesPrediction/
├── data/                 # Dataset (e.g. diabetes.csv)
├── notebooks/            # Jupyter notebooks for EDA and modeling
├── models/               # Saved trained model(s) and scaler(s)
├── utils/                # Utility scripts (optional)
├── app.py / interface.py # Web interface (Streamlit/Flask) – if available
├── requirements.txt
└── README.md
🧪 Dataset
The project uses the Pima Indians Diabetes Database with features including:

-> Pregnancies

-> Glucose

-> BloodPressure

-> SkinThickness

-> Insulin

-> BMI

-> DiabetesPedigreeFunction

-> Age

Labels indicate diabetes onset status.

🚧 Installation
Clone this repository:

bash
Copy
Edit
git clone https://github.com/KommanaPavani/DiabetesPrediction.git
cd DiabetesPrediction
(Optional) Create and activate a virtual environment:

bash
Copy
Edit
python3 -m venv venv
source venv/bin/activate
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
📊 Usage
Notebooks: Open and run the .ipynb files to reproduce analysis and modeling steps.

Trained Model: Load saved model(s) from models/ for inference.


Model performance typically includes:

Accuracy

Precision, Recall, F1‑score

ROC‑AUC Curve Analysis

For example: Random Forest or XGBoost often achieves ~75–85% accuracy depending on preprocessing and tuning.

🧭 Future Improvements
Hyperparameter tuning (GridSearchCV / RandomSearch)

Feature selection / dimensionality reduction

Incorporating additional datasets or data augmentation



👤 About the Developer
I developed this project during the Machine Learning 100-Hour Course led by Think AI CEO. Special thanks to the course mentors for guidance and support during the learning journey.

📄 License
This project is released under the MIT License. See the LICENSE file for details.

🤝 Contributing
Contributions are welcome!

Fork the repo

Create a feature branch (git checkout -b feature‑name)

Commit your changes (git commit -m "Add feature")

Push to your branch (git push origin feature‑name)

Submit a Pull Request

📬 Contact
Feel free to reach out for feedback or collaboration opportunities!
