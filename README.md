# Health_Data_Cleaning_204
Here's a brief description of the code we implemented for healthcare data cleaning:

Input Data: We used a sample healthcare dataset containing patient details such as age, gender, blood pressure, cholesterol levels, and disease presence. The dataset included missing, inconsistent, and noisy values.

Handling Missing Data:

For numerical columns, missing values were replaced with the mean value of the respective column.

For categorical columns, missing values were replaced with the most frequent value.

Standardizing Inconsistent Data:

Inconsistent entries in categorical data (e.g., "M" and "Male") were standardized to a single consistent value (e.g., "Male").

Removing Noise (Outliers):

The Interquartile Range (IQR) method was used to identify and remove extreme outliers from numerical data.

Scaling Numerical Data:

Numerical columns were standardized using StandardScaler to ensure all numerical features were on the same scale, enhancing compatibility with machine learning models.

Output:

The cleaned data was saved to a CSV file named cleaned_healthcare_data.csv for further analysis or predictive modeling.

This code ensures the dataset is reliable, consistent, and ready to be used for machine learning tasks to improve disease prediction accuracy.
