# Predicting-Diabetes

Took a dataset and used several models taken from sckit-learn to to see which would be most efective at detecting diabetes. 

Models used:
- KNN
- Decision Tree
- Random Forest
- Logistic Regression
- KMeans

Pre-processed using pandas and numpy

## Pre-Processing

Replace missing data 0's with average column value for columns 'Glucose', 'BloodPressure', 'SkinThickness', 'Insulin', 'BMI'

Used StandardScalar to normalize training dataset.

Split dataset into training and testing splits, one version normalized and another without normalization.

## Results

### KMeans

KMeans had the lowest accuracy score of 53%

### Logistic Regression

Logistic Regression has an accuracy score of 75%

### KNN

KNN has an accuracy score of 77%

### Random Forest

Random Forest has an accuracy score of 78%

### Decision Tree
Decision Tree has the highest accuracy score at 79%


## Contributing

If you would like to improve upon this project or use it to as a base for your own you are free to use however you like and fork it.

If you want to directly contribute to this repo

1. Fork the Project
2. Create your Feature Branch (git checkout -b feature/YourFeature)
3. Commit your Changes (git commit -m 'Add some YourFeature')
4. Push to the Branch (git push origin feature/YourFeature)
5. Open a Pull Request

## License
Distributed under the MIT License. See LICENSE.txt for more information.