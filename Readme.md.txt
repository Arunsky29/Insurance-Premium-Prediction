# Insurance Premium Prediction

This project predicts insurance premium amounts for customers using machine learning. It processes `train.csv` and `test.csv` through EDA, data cleaning, encoding, and scaling. An XGBoost regression model is trained to capture patterns between customer details and premiums. Predictions are saved in `submission.csv` for evaluation or deployment.

## Files in this Repository
- `train.csv` – Training dataset with customer details and premium amounts.
- `test.csv` – Test dataset for which predictions are to be made.
- `sample_submission.csv` – Template showing the required submission format.
- `insurance_premium_prediction.ipynb` – Jupyter Notebook with the complete project code.
- `requirements.txt` – Python dependencies for running this project.

## How to Run
1. Install dependencies:
   ```bash
   pip install -r requirements.txt

2. Open the notebook:

bash
Copy
Edit
jupyter notebook insurance_premium_prediction.ipynb

3. Run all cells to train the model and generate submission.csv.