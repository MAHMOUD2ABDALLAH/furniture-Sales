

# Furniture Sales Prediction

This project focuses on predicting categories of furniture products using various machine learning regression models. The goal is to evaluate the performance of different models and identify the best one for this task.

## Dataset

The dataset consists of two CSV files:
- `train.csv`: Training data with features and target labels.
- `test.csv`: Test data for making predictions.

## Features

- **Title - F1**: A categorical feature representing the title of the furniture product.
- **Category - F2**: The target variable representing the category of the furniture product.

## Preprocessing

- **Encoding**: Categorical variables are encoded using `LabelEncoder`.
- **Imputation**: Missing values are handled using `SimpleImputer` with a mean strategy.

## Models

The following regression models are implemented and evaluated:
- Linear Regression
- Lasso Regression
- Ridge Regression
- ElasticNet Regression
- Random Forest Regressor
- Gradient Boosting Regressor

## Results

The Random Forest model achieved the best performance with a Mean Squared Error (MSE) of 31.99.

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/MAHMOUD2ABDALLAH/furniture-Sales.git
   ```
2. Navigate to the project directory:
   ```bash
   cd furniture-Sales
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the script:
   ```bash
   python main.py
   ```

## Visualization
The script includes a function to plot actual vs. predicted values, providing a visual comparison of the model's performance.
![1](https://github.com/user-attachments/assets/f6dcac1b-df13-40e1-8265-5582503fe446)

## Acknowledgments

- Thanks to the contributors of the `scikit-learn` library for providing robust machine learning tools.

### Additional Notes:
1. **No License Section**: Since this was a freelancing task, you don't need to include a license. The project is specific to the task you completed on Upwork.
2. **Requirements File**: Ensure you include a `requirements.txt` file with the necessary libraries, as mentioned earlier.
3. **Example Data**: If you can share sample data (or a description of the data format), it will help others understand how to use the script.

Let me know if you need any further adjustments! 😊
