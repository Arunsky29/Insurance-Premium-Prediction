Insurance Premium Prediction
This project predicts insurance premium amounts using machine learning techniques. It processes train.csv and test.csv datasets through data exploration (EDA), data cleaning, feature encoding, and feature scaling. The final model uses XGBoost Regression to capture complex relationships between customer details and premium values.

📌 Project Workflow

flowchart LR
    A[Dataset: train.csv, test.csv] --> B[Data Preprocessing]
    B --> C[Exploratory Data Analysis (EDA)]
    C --> D[Feature Encoding & Scaling]
    D --> E[Model Training - XGBoost]
    E --> F[Prediction Generation - submission.csv]
📂 Dataset
The dataset used in this project can be accessed here: Google Drive Link

⚠️ Note: CSV files are not stored in this repository due to GitHub’s 100MB file size limit.

⚙️ Requirements
Install the required dependencies:
pip install -r requirements.txt
🚀 Usage
Clone this repository
git clone https://github.com/Arunsky29/Insurance-Premium-Prediction.git
Download the dataset from Google Drive and place it in the project folder.

Run the training script

python main.py
📊 Model Performance
Algorithm: XGBoost Regressor

Metric: Root Mean Squared Error (RMSE)

Optimization: Hyperparameter tuning to improve prediction accuracy.

✨ Features
Step-by-step modular data processing pipeline.

Ready for retraining with updated datasets.

Easy to adapt for other regression problems.

Documentation for each stage of the workflow.

📜 License
This project is licensed under the MIT License.


## Dataset
The dataset used in this project can be accessed here: [Google Drive Link](https://drive.google.com/drive/folders/1HKBjaOIVIcJ3hu5LuXmlMfWPVOeAGreG?usp=sharing)
