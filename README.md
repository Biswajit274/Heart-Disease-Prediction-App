# Heart Disease Prediction App

This project is a modern Python application for predicting the risk of heart disease using a pre-trained Support Vector Machine (SVM) model. The model is stored in `svm_model.pkl` and was trained on heart disease data.

## Features
- Predicts the likelihood of heart disease based on user input.
- Uses a pre-trained SVM model for fast and accurate predictions.
- User-friendly interface.

## Requirements
- Python 3.7+
- Required packages (install with pip):
  - pandas
  - numpy
  - scikit-learn
  - flask

## Setup
1. Clone or download this repository.
2. Ensure `svm_model.pkl` is in the project directory.
3. (Optional) Review the `Heart_Disease_Prediction.ipynb` notebook to understand the input features expected by the model.
4. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Run the app:
   ```bash
   python app_modern.py
   ```
2. Open your browser and go to `http://localhost:5000`.
3. Enter the required features in the app interface. **The input features must match those used during model training.**
4. Click the predict button to see the result.

## Model Input Features
- The app requires the same features as used during model training. If you are unsure, open `Heart_Disease_Prediction.ipynb` and look for the line where `X` is defined (e.g., `X = df[[...]]`).
- Typical features for heart disease prediction include: `age`, `sex`, `cp`, `trestbps`, `chol`, `fbs`, `restecg`, `thalach`, `exang`, `oldpeak`, `slope`, `ca`, `thal`. Please confirm with your notebook.

## Files
- `svm_model.pkl`: Pre-trained SVM model.
- `Heart_Disease_Prediction.ipynb`: Notebook with data exploration, model training, and feature details.
- `app_modern.py`: The main app file.

## License
This project is for educational purposes. 
