#  Titanic Survival Prediction

This project aims to build a machine learning model that predicts whether a passenger survived the Titanic disaster based on features like age, gender, class, and fare.

It covers data cleaning, exploration, feature engineering, model building, and evaluation using Python and scikit-learn.

##  Project Structure



##  Dataset

- Source: [Kaggle - Titanic](https://www.kaggle.com/datasets/brendan45774/test-file)


## Tools Used

- Python
- pandas, numpy
- matplotlib, seaborn
- scikit-learn
- Jupyter Notebook

## Data Preprocessing

- Filled missing Age and Embarked values
- Dropped irrelevant columns (Name, Ticket, etc.)
- Converted categorical variables (Sex, Embarked)

## EDA Insights

- Females and higher-class passengers had higher survival rates
- Children had a higher chance of survival than adults

## Model

- Random Forest Classifier
- Trained on 80% of the data
- Evaluated on 20% test set

## Results

- Accuracy: 100% (on current split)
- Evaluated with classification report (precision, recall, F1-score)
