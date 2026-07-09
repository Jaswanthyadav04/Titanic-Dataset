# Titanic Dataset Analysis

## 📊 Overview
This repository contains a comprehensive analysis of the Titanic dataset. The project explores passenger survival patterns from the RMS Titanic disaster using Python data analysis and visualization techniques.

## 📁 Contents
- **Titatnic_dataset.ipynb** - Main Jupyter Notebook containing the complete analysis

## 🎯 Project Structure

### Data Collection
- Downloads the Titanic test dataset using Kaggle API
- Dataset contains 418 passenger records

### Data Understanding (Part 1)
The analysis includes:
1. **Data Verification** - Confirms correct data import
   - Dataset shape: (418 rows, 12 columns)
   
2. **Exploratory Data Analysis** - Examines records from beginning and end of dataset

3. **Data Overview** - Shows first and last few passenger records

## 📋 Dataset Features

The dataset contains the following 12 columns for each passenger:
- **PassengerId** - Unique passenger identifier
- **Survived** - Survival status (0 = No, 1 = Yes)
- **Pclass** - Passenger class (1, 2, or 3)
- **Name** - Passenger name
- **Sex** - Gender (male/female)
- **Age** - Age in years
- **SibSp** - Number of siblings/spouses aboard
- **Parch** - Number of parents/children aboard
- **Ticket** - Ticket number
- **Fare** - Ticket fare paid
- **Cabin** - Cabin number
- **Embarked** - Port of embarkation (C, Q, or S)

## 🔧 Requirements
- pandas
- numpy
- kagglehub
- Google Colab (notebook is designed for Colab environment)

## 🚀 Usage

1. **Setup Kaggle API credentials** for downloading the dataset
2. **Run the notebook cells** in order:
   - Collection of data
   - Tabulation of data
   - Understanding the data
   - Further analysis (to be completed)

## 📊 Data Insights
- Total passengers in test set: 418
- Columns analyzed: PassengerId, Survived, Pclass, Name, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin, Embarked
- Some missing values present in Age and Cabin columns

## 📝 Notes
- This notebook uses Google Colab for execution
- Dataset is sourced from Kaggle's test-file dataset
- The analysis is designed to be extensible for further modeling and insights

## 🎓 Learning Objectives
- Data loading and exploration using pandas
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Understanding survival patterns in the Titanic disaster

---

**Repository**: [Jaswanthyadav04/Titanic-Dataset](https://github.com/Jaswanthyadav04/Titanic-Dataset)
