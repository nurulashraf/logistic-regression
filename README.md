# Heart Disease Prediction using Logistic Regression


This project applies logistic regression to predict the likelihood of heart disease based on a dataset of patient health records. It demonstrates a simple machine learning pipeline from data loading and preprocessing to model training, evaluation, and basic prediction.

---

## Project Structure

- **`data/`**: Contains the dataset used for analysis and prediction.
- **`notebooks/`**: Jupyter notebooks for data analysis, feature engineering, and model building.
- **`README.md`**: Project overview and usage instructions.

---

## Features

- Data cleaning and exploration.
- Feature selection and preprocessing.
- Model training using logistic regression.
- Model evaluation with accuracy, precision, recall, and F1 score.
- Confusion matrix visualisation.
- Simple prediction demo with sample input.

---

## Tools & Libraries

- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- scikit-learn
- seaborn
- matplotlib

---

## How to Use

1. **Clone the repository:**

   ```bash
   git clone https://github.com/nurulashraf/logistic-regression-heart-disease-prediction.git
   cd logistic-regression-heart-disease-prediction
   ```

2. **Set up a virtual environment (optional but recommended):**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the notebook:**

   ```bash
   jupyter notebook logistic_regression_heart_disease_prediction.ipynb
   ```

5. **Dataset:**

   The project uses the `heart_disease_prediction.csv` dataset stored in the `data/` folder. If it's missing, you can download a similar dataset from public repositories like Kaggle.

---

## License

This project is licensed under the [MIT License](LICENSE).
