# flight-prediction

The goal of this project is to develop a machine learning model capable of predicting flight prices based on historical data. The challenge involves handling a dataset that includes various features related to flights, making it a regression problem since the output variable (flight price) is continuous.

## Dataset

The dataset comprises two Excel files: Data_Train.xlsx for training and Test_set.xlsx for testing. These files contain records of flight details, including airlines, departure and arrival times, and prices. Key features include:

**Airline**: The flight's operating airline.

**Date_of_Journey**: The flight's departure date.

**Source**: The departure location.

**Destination**: The arrival location.

**Duration**: Flight duration.

**Total_Stops**: The number of stops before reaching the destination.

**Price**: The cost of the flight (target variable).

## Approach

The approach to solving this regression problem involves several steps:

Data Cleaning: Identifying and handling missing values, removing unnecessary columns, and correcting inconsistencies in categorical data.

Feature Engineering: Extracting useful information from existing features, such as converting the 'Duration' from hours and minutes to minutes only, and splitting 'Date_of_Journey' into day, month, and weekday.

Data Preprocessing: Standardizing the case of categorical variables to avoid duplicates, and handling categorical variables through encoding.

Model Development: Splitting the data into training and testing sets, selecting appropriate regression models, and tuning hyperparameters for optimal performance.

Evaluation: Using metrics like mean absolute error and mean squared error to assess model performance.

## Required Python Libraries

Pandas and Numpy for data manipulation.

Matplotlib and Seaborn for data visualization.

Scikit-Learn for model selection, training, and evaluation.

The project emphasizes the importance of thorough data preprocessing and feature engineering to improve model accuracy and performance in predicting flight prices.
