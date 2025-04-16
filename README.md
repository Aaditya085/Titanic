Titanic - Survival Prediction (Kaggle Competition)
This project explores the classic Titanic dataset from the Kaggle competition, aiming to predict passenger survival. The notebook walks through data exploration, preprocessing.

Each passenger record includes:

Demographics: Name, Sex, Age

Ticket details: Pclass, Ticket number, Fare

Family info: SibSp (siblings/spouses aboard), Parch (parents/children aboard)

Embarked location

Cabin info (sparse)

Project Structure & Approach

1. Exploratory Data Analysis (EDA)
Investigated class imbalance in the Survived column.

Plotted survival rates by gender, age, passenger class, and family size.

Identified missing values in Age, Cabin, and Embarked.

2. Data Cleaning & Feature Engineering

Converted Sex, Embarked, and other categorical columns to numerical.

Engineered new features like:

FamilySize = SibSp + Parch + 1


Key Insights

Sex is the strongest predictor: females had much higher survival rates.

Ticket class matters a lot – higher-class passengers had better chances.

Passengers traveling alone were less likely to survive.


