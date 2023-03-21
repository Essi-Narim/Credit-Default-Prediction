# Credit Default Prediction Project

This project aims to predict credit defaults using a dataset from Lending Club. Various machine learning and deep learning models are employed to achieve this goal.

## Dataset

The dataset contains loan and borrower information, including the loan status, which is the target variable for this project. The dataset can be downloaded from this [Google Drive link](https://drive.google.com/drive/folders/1R1w6EgE0tZl265KAd8fqeFev9p29AMoP). The dataset is loaded from two CSV files:

- lending_club_loan_two.csv: Contains the main loan and borrower data.
- lending_club_info.csv: Contains metadata about the dataset.

## Data Exploration and Analysis

The project includes extensive data exploration and analysis, including:

- Investigating the target variable (loan_status).
- Exploring the relationship between various features and the target variable.
- Analyzing the correlation between numerical features.
- Investigating missing values and handling them appropriately.

## Data Cleaning and Feature Engineering

The data is cleaned and prepared for machine learning algorithms, including:

- Handling missing values.
- Feature engineering to create new, relevant features from the existing data.
- Ordinal encoding to convert categorical variables into numerical variables.

## Modeling

Several machine learning and deep learning models are used to predict credit defaults:

- TensorFlow (Deep Learning): A neural network model is implemented using TensorFlow's Sequential API. The model includes multiple dense layers and dropout layers to prevent overfitting.
- Machine Learning (Classification): Several machine learning models are compared, including LinearSVC, LogisticRegression, GaussianNB, RandomForestClassifier, and MLPClassifier.

## Evaluation

The models are evaluated based on their accuracy and other performance metrics provided by classification reports. In this project, RandomForestClassifier is found to be an efficient alternative to the deep learning model, providing comparable performance with less computational complexity.

## Usage

To use this project, you can clone the repository and run the Jupyter Notebook file in your preferred environment. Make sure to install the necessary dependencies, such as pandas, seaborn, scikit-learn, and TensorFlow.

## Conclusion

This project demonstrates how to use various machine learning and deep learning models for credit default prediction. The RandomForestClassifier is found to be an efficient and interpretable alternative to the deep learning model, making it more suitable for certain applications where computational resources or interpretability are important considerations.

## Acknowledgments

Special thanks to the [DS Novice YouTube channel](https://www.youtube.com/@DSNovice) for their valuable guidance and assistance in the development of this project.
