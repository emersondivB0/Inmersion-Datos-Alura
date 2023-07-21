# Data Science Project: Real Estate Price Prediction

The objective of this project is to apply data science techniques to predict the prices of future real estate properties. A dataset containing information about property sales, including prices, areas, locations, number of bathrooms, bedrooms, and socio-economic data of people in the areas where these properties are located is used.

### Technologies Used
The following tools and technologies were used in this project:

- Google Drive
- Google Colaboratory
- Python 3
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

### Repository Structure
The repository is organized as follows:

**data/**: Folder containing CSV files with real estate sales data.
**notebooks/**: Folder containing the Jupyter Notebook file used for data analysis and processing, as well as creating and training the linear regression model.
**README.md**: This file, providing general information about the project.

### Analysis and Modeling Process
Data Loading: Data was loaded from the CSV files into Google Colaboratory.

Exploratory Analysis: Pandas, Matplotlib, and Seaborn were used to analyze the data, identify outliers, and explore relationships between variables.

Data Preprocessing: Data cleaning and transformation tasks were performed, including handling missing values, normalizing variables, and creating new derived variables.

Modeling: The scikit-learn library was used to create and train a linear regression model that predicts property prices based on predictor variables.

Model Validation: The model's accuracy was evaluated using metrics such as Mean Squared Error (MSE) and Coefficient of Determination (R2).

### Results and Conclusions
The linear regression model achieved moderate accuracy in predicting the prices of future real estate properties based on the predictor variables used. The most important variables for price prediction were identified, which can be useful for decision-making in the real estate market. However, there is room for improvement in the model's performance to achieve better predictions.

