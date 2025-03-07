# Iris Classification with Streamlit

This project demonstrates the classification of Iris species using machine learning models, with the ability to interact with the model via a Streamlit web app.

## Project Structure

- `iris_classification.ipynb`: Jupyter notebook with the machine learning models and analysis.
- `streamlit_app.py`: Streamlit app for user interaction.
- `best_model.pkl`: The trained model saved using pickle.
- `requirements.txt`: List of dependencies.

## How to Run the Streamlit App

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

2. Run the Streamlit app:
   ```bash
   streamlit run streamlit_app.py
   ```

The app will be accessible in your browser at `http://localhost:8501`.

## Requirements

- Python 3.x
- scikit-learn
- numpy
- pandas
- streamlit
