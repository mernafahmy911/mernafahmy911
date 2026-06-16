
## NeuralStroke: An AI-Powered Stroke Risk Prediction System

I'm excited to share our final project, NeuralStroke — a machine learning system designed to predict stroke risk with high accuracy and clinical relevance, now deployed as an interactive web application.

🎯 The Challenge
Stroke is a leading cause of death and long-term disability worldwide. Early detection is difficult due to complex relationships between risk factors.

💡 Our Solution
An automated screening system that:
Uses 35,000 medically validated samples
Balances data: 61.6% at-risk, 38.4% healthy
Includes 16 comprehensive features covering symptoms and demographics
Applies feature engineering and advanced ML models
Implements Gradient Boosting, AdaBoost, Random Forest, SVM, and Neural Networks
Achieves 96.4% precision in stroke risk classification
Provides explainable results to support medical decisions

🛠️ Tech Stack
Python, Pandas, NumPy, Scikit-Learn, TensorFlow/Keras, Matplotlib, Seaborn, Streamlit.

🔧 Data Processing
Cleaning, handling missing values, deduplication, and label encoding.

📊 Exploratory Data Analysis (EDA)
Using Matplotlib and Seaborn, we visualized data distributions and identified key correlations between features, which informed feature selection.

⚙️ Feature Engineering & Selection
We applied Recursive Feature Elimination (RFE) to systematically identify and retain the most predictive clinical and demographic features, optimizing model performance and reducing complexity.

📈 Model Training & Validation
All models were rigorously validated using ROC-AUC curves, Classification Reports, and Confusion Matrices to ensure robust performance and high recall.

🏆 Results
Best model (Logistic Regression) achieved 96.4% accuracy.
Neural Network reached 95.9% accuracy with clear feature interpretability.

🔮 Future Work
Real-time biometric integration, mobile app, wearable compatibility, and EHR connectivity.

🌐 Streamlit Web Application Deployment
📊 Four Key Modules:
Dashboard – Overview & metrics
Data Explorer – Interactive charts & correlations
Risk Predictor – Real-time assessment with recommendations
Model Insights – Performance visualizations & feature importance

✨ User Experience:
Clean, medical-themed UI
Real-time input processing
Privacy-first local computation
Designed for patients, doctors, and researchers

🚀 Why Streamlit?
Rapid prototyping & deployment
Seamless Python integration
Interactive visualizations with Plotly
Responsive & mobile-friendly
