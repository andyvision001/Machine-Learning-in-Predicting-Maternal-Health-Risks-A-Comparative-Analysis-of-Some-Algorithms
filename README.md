Maternal Health Risk Prediction Using Machine Learning

This repository contains the implementation and analysis of three supervised machine learning algorithms—Logistic Regression, Support Vector Machine (SVM), and K-Nearest Neighbor (K-NN)—for predicting maternal health risks. The goal is to enable early detection of maternal health risks to help reduce maternal mortality rates, a critical challenge in healthcare delivery.

Dataset

The dataset used in this study is sourced from the UCI Machine Learning Repository. It consists of seven features:





Age: Age of the patient



SystolicBP: Systolic Blood Pressure



DiastolicBP: Diastolic Blood Pressure



BS: Blood Sugar



BodyTemp: Body Temperature



HeartRate: Heart Rate



RiskLevel: Target label (Low, Medium, High risk)

Methodology

The study evaluates the performance of the following algorithms:





Logistic Regression



Support Vector Machine (SVM)



K-Nearest Neighbor (K-NN)

Performance metrics include:





Accuracy



Precision



Recall



F1 Score



Area Under the Curve (AUC)

Results

The evaluation results are as follows:





K-NN:





Accuracy: 78%



Precision: 78%



Recall: 78%



F1 Score: 78%



AUC: 0.93



SVM:





Accuracy: 76%



Precision: 77%



Recall: 76%



F1 Score: 76%



AUC: 0.88



Logistic Regression:





Accuracy: 60%



Precision: 62%



Recall: 59%



F1 Score: 60%



AUC: 0.74

While the algorithms did not achieve state-of-the-art accuracy, the results highlight the potential of machine learning in maternal healthcare applications.

Repository Contents





data/: Dataset from UCI repository



notebooks/: Jupyter notebooks with data preprocessing, model training, and evaluation



scripts/: Python scripts for model implementation



results/: Performance metrics and visualizations

Getting Started





Clone the repository:

git clone https://github.com/yourusername/maternal-health-risk-prediction.git



Install dependencies:

pip install -r requirements.txt



Run the Jupyter notebooks in the notebooks/ directory to explore the analysis.

Requirements





Python 3.x



Libraries: scikit-learn, pandas, numpy, matplotlib, seaborn

Contributing

Contributions are welcome! Please submit a pull request or open an issue to discuss improvements or suggestions.

