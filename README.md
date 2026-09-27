# Hotel Booking Prediction

Machine learning project predicting hotel booking cancellations and average daily room rates using Python and scikit-learn.

## Tasks

- **Classification:** Predict cancellation status (`is_canceled`).
- **Regression:** Estimate average daily room rate (`adr`).

## Approach

Data cleaning, one-hot encoding, model comparison, five-fold cross-validation, hyperparameter tuning, and feature selection.

**Classification models:** Logistic Regression, KNN, Decision Tree, Random Forest, Gradient Boosting, and Naive Bayes.

**Regression models:** Linear Regression, Ridge, Lasso, Random Forest, and Gradient Boosting.

## Run

Install dependencies:

```bash
python -m pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

Run the notebooks in order: **data cleaning → classification → regression**. Place `hotel_bookings_clean.csv` beside the modeling notebooks.

## Scope

Regression estimates historical room rates using available booking information. Predicting at booking time requires excluding information only known later.

**Author:** Michael Zang
