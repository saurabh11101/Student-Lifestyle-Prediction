# Student Lifestyle and Stress Prediction

This project predicts a student's stress level using a trained machine learning model and a Streamlit web UI.

## Project files

- `student_stress_model.py` - Streamlit app that collects input features and makes stress-level predictions.
- `student_stress_model.pkl` - Trained model used for prediction.
- `scaler.pkl` - Feature scaler required to transform input data before prediction.
- `student-lifestyle-and-stress-dataset.csv` - Dataset used for exploration and model building.
- `student lifestyle and stress prediction.ipynb` - Notebook for data analysis and modeling.

## Requirements

Install dependencies with:

```bash
pip install -r requirements.txt
```

## Run the app

From the project folder, run:

```bash
streamlit run student_stress_model.py
```

Then open the provided local URL in your browser.

## Usage

1. Select student type.
2. Enter sleep, study, social media, and attendance values.
3. Choose exam pressure and family support.
4. Click `Predict` to see `High Stress` or `Low Stress`.

## Notes

- The model expects the saved `student_stress_model.pkl` and `scaler.pkl` files to be in the same folder as the Streamlit app.
- The project uses a pre-trained classifier and scaler for input transformation.
