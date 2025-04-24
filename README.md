🧠 Objective:
Clean and preprocess the Titanic dataset to make it suitable for machine learning models.

📁 Files Included
Untitled3.ipynb – Contains all preprocessing code with output.
Titanic Dataset (titanic.csv) – Raw dataset used.

🛠 Tools Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn (for scaling)

✅ Steps Performed
Imported Libraries
Used pandas, numpy, matplotlib.pyplot, seaborn, and StandardScaler from sklearn.

Loaded the Dataset
Dataset path: C:/Users/katta/Downloads/titanic.csv

Explored Missing Data
Used .isnull().sum() to identify missing values.

Handled Missing Values
Filled missing Age values with the mean.

Filled missing Embarked values with the most frequent category (mode).
Encoded Categorical Features
Converted Sex to numeric using manual mapping (male = 1, female = 0).
Converted Embarked using pd.get_dummies() and dropped the first column to avoid multicollinearity.
Feature Scaling
Standardized Age and Fare using StandardScaler() for better model performance.
Visualized Outliers
Plotted a boxplot for Fare using Seaborn to detect outliers.
Removed Outliers
Applied IQR (Interquartile Range) method to remove outliers in Fare.
Final Cleaned Dataset
Displayed the first few rows of the cleaned dataset with all transformations.

📈 Output Visuals
Boxplot of Fare (before removing outliers)
Cleaned data preview (with encoded and scaled values)

🎓 What I Learned
How to detect and handle missing values.
Encoding techniques for categorical data.
Scaling/normalizing data for ML.
Outlier detection and removal using boxplots and IQR.
Preparing a complete, clean dataset for machine learning.

Downloaded the dataset from 
GitHub - datasets/titanic.csv at master
https://github.com/datasciencedojo/datasets/blob/master/titanic.csv
