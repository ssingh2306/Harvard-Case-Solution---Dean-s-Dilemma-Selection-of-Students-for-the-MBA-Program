# Student Placement Prediction

This project aims to predict student placement outcomes based on various academic and other factors. It involves data preparation, exploratory data analysis (EDA), feature engineering, model training, and evaluation.

## Summary

This Python script performs the following steps:

1. **Data Preparation**:
   - Reads an Excel file named "Dean's Dilemma" into a DataFrame.
   - Displays the first 10 rows of the DataFrame and checks for missing values.
   - Utilizes visualization techniques such as count plots, pair plots, and heatmaps to explore the data's characteristics and relationships between variables.
   - Performs one-hot encoding on categorical variables like "Stream_HSC", "Specialization_MBA", and "Experience_Yrs" to convert them into numerical format for modeling.
   - Modifies the DataFrame by dropping unnecessary columns and adding one-hot encoded columns.

2. **Modeling**:
   - Defines independent variables (`X`) and the target variable (`y`).
   - Splits the dataset into training and testing sets using `train_test_split`.
   - Trains a Logistic Regression model on the training data (`X_train`, `y_train`).
   - Makes predictions on the testing data (`X_test`).
   - Computes performance metrics such as classification report, confusion matrix, and accuracy score to evaluate the model's effectiveness in predicting placement outcomes.

## Usage

1. Clone the repository.
2. Install the required libraries (`pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, etc.).
3. Ensure the Excel file "Dean's Dilemma" is in the correct directory.
4. Run the Python script to perform data preparation, modeling, and evaluation.
5. Explore the generated visualizations and performance metrics to understand the model's performance.

## Contributions

Contributions are welcome! Feel free to submit pull requests or open issues for any enhancements, bug fixes, or additional features.

## License

This project is licensed under the [MIT License](LICENSE).

---

This readme provides an overview of the project, its features, usage instructions, contribution guidelines, and licensing information, enabling users to understand and utilize the student placement prediction tool effectively.
