Q1 — What is the difference between regression and classification? Give real-world examples.
>
Regression
Predicts continuous values
Example: Stock prices

Classification
Predicts categories
Example: Email spam detection

Q2 (Coding) — Implement a function: calculate_mse(y_true, y_pred)
>
def calculate_mse(y_true, y_pred):
    return sum((y_true - y_pred)**2) / len(y_true)
print(calculate_mse(np.array([1,2,3]), np.array([1,2,4])))

Q3 — Explain bias–variance tradeoff. What happens in:
● Underfitting
● Overfitting
>
Underfitting
Model too simple
High bias, low variance
Poor training & testing performance
Overfitting
Model too complex
Low bias, high variance
Good training, poor testing
