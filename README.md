🏠 House Price Prediction System( ML + MLOps)

This project is a production-grade House Price Prediction System built using Machine Learning, MLOps, and software engineering design patterns. Inspired by enterprise-level workflows, it covers everything from data ingestion, EDA, feature engineering, and model training, to CI/CD, pipeline orchestration, and experiment tracking.

Core ML techniques:- 
Strong coding architecture
Design patterns (Factory, Strategy, Template)
Production-ready MLOps
The model predicts house prices based on multiple features while ensuring robustness, reproducibility, and scalability.

🛠 Tech Stack
Core ML: Python, Pandas, NumPy, Scikit-learn
Visualization: Matplotlib, Seaborn
MLOps: ZenML, MLflow
Architecture: Factory Pattern, Strategy Pattern, Template Pattern
Tools: VS Code / Jupyter, Git, CI/CD

✨ Key Features
Advanced Data Ingestion System
Factory Pattern to handle multiple data formats (ZIP, CSV, JSON, etc.)
Automated validation & error handling
Deep Exploratory Data Analysis (EDA)
Strategy Pattern for switching inspection methods
Missing value heatmaps, distribution plots, multivariate analysis
Feature Engineering & Model Development
Outlier detection
Handling skewness
Encoding categorical variables
Algorithm assumptions checks
MLOps Integration
ZenML pipelines for orchestration
MLflow for experiment tracking & deployment
CI/CD for automated testing & production deployment
Clean & Scalable Codebase
Template Pattern-based workflows
Well-documented modules and reusable components

📁 Project Structure
project/
│── data/
│── src/
│   ├── ingestion/
│   ├── analysis/
│   ├── processing/
│   ├── model/
│   ├── pipelines/
│── notebooks/
│── mlruns/  (MLflow)
│── README.md

⚙️ Pipeline Workflow:-
Data Ingestion
EDA & Insight Generation
Missing Value & Outlier Handling
Feature Engineering
Model Training
Assumption Checks & Iterative Refinement
MLOps Pipeline (ZenML + MLflow)
Model Deployment & CI/CD

▶️ How to Run :- 
git clone <repo-url>
cd house-price-prediction

pip install -r requirements.txt
zenml init
mlflow ui

python run_pipeline.py


