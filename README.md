# Titanic Survival Prediction

This project aims to predict the survival of passengers aboard the Titanic using machine learning techniques. It analyzes the Titanic dataset, which contains information about passengers' demographic data, ticket information, and survival status.

**Dataset Description:**

- The dataset consists of features such as PassengerId, Survived, Pclass, Name, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin, and Embarked.
- The target variable is "Survived", indicating whether a passenger survived (1) or not (0).

**Project Overview:**

**1. Data Cleaning and Preprocessing:** Handled missing values, converted categorical variables into the numeric format, and performed feature engineering to create new features like "FamilySize" and "Title".

**2. Exploratory Data Analysis (EDA):** Conducted EDA to understand the distribution of survival across different features and visualize relationships between survival and other variables.

**3. Feature Engineering:** One-hot encoded categorical features like "Title" to prepare the data for modelling.

**4. Model Building:** Split the data into training and testing sets, trained a Random Forest classifier, and evaluated the model's performance using accuracy score, classification report, and confusion matrix.

**Challenges Faced and Solutions:** Addressed issues with missing values, categorical variables, and feature extraction using appropriate techniques.

**Conclusion and Future Scope:** Summarized findings, suggested improvements and outlined potential areas for future exploration, such as advanced feature engineering and deployment of the model into production.

**Usage:**

1. Clone the repository: `git clone https://github.com/abhi534/Predictive-Analysis-of-House-Prices-Leveraging-Python-Libraries-for-Accuracy.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the notebook: `jupyter notebook Predictive Analysis of Breast Cancer Diagnosis.ipynb`

**Dependencies:**

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

**References:**

Dataset source: Kaggle - Titanic: Machine Learning from Disaster

Feel free to explore the project, contribute improvements, or use it as a learning resource for machine learning and data analysis. If you encounter any issues or have suggestions, please open an issue or pull request. Happy coding!
