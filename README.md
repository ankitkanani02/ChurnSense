# ChurnSense

## Description
ChurnSense is a project aimed at predicting customer churn. The dataset used for this project is the Telco Customer Churn dataset, which provides information about customers who left within the last month, services they signed up for, customer account information, and demographic data. The project's goal is to analyze relevant customer data and develop focused customer retention programs.

## Installation
1. Clone the repository: `git clone https://github.com/ankitkanani02/ChurnSense.git`
2. Install the required dependencies: `pip install -r requirements.txt`

## Technology and Libraries Used
- Python programming language
- Libraries:
  - pandas
  - numpy
  - matplotlib.pyplot
  - seaborn
  - sklearn (train_test_split, LogisticRegression, DecisionTreeClassifier, RandomForestClassifier, GaussianNB, SVC, StandardScaler, AdaBoostClassifier, XGBClassifier, BaggingClassifier)
  - tensorflow
  - keras (Sequential, Dense, Dropout)

## Results
Model Performance:
- LogisticRegression: Accuracy = 0.81, ROC AUC = 0.76, F1 Score = 0.82
- AdaBoostClassifier: Accuracy = 0.82, ROC AUC = 0.76, F1 Score = 0.82
- RidgeClassifierCV: Accuracy = 0.81, ROC AUC = 0.74, F1 Score = 0.81
- RidgeClassifier: Accuracy = 0.81, ROC AUC = 0.74, F1 Score = 0.81
- LinearSVC: Accuracy = 0.81, ROC AUC = 0.74, F1 Score = 0.81
- CalibratedClassifierCV: Accuracy = 0.82, ROC AUC = 0.74, F1 Score = 0.82
- GaussianNB: Accuracy = 0.67, ROC AUC = 0.50, F1 Score = 0.62

Balanced Accuracy:
- NearestCentroid: 0.76
- BernoulliNB: 0.76
- LinearDiscriminantAnalysis: 0.76

ROC AUC:
- BernoulliNB: 0.76
- NearestCentroid: 0.76
- LogisticRegression: 0.76
- Perceptron: 0.76

F1 Score:
- LogisticRegression: 0.82
- AdaBoostClassifier: 0.82
- RidgeClassifierCV: 0.82
- RidgeClassifier: 0.82
- LinearSVC: 0.82

Time Taken:
- Training and inference times range from 0.02 to 2.98 seconds.

Based on the results, LogisticRegression, AdaBoostClassifier, RidgeClassifierCV, RidgeClassifier, and LinearSVC consistently performed well across different evaluation metrics, including accuracy, balanced accuracy, ROC AUC, and F1 score. Further analysis and optimization can be performed on these models. Additionally, investigation into the poor performance of the GaussianNB model and potential improvements through alternative approaches or feature engineering is recommended.

## Project Outline
1. EDA
2. Training various ML models mentioned above
3. Hyperparameter tuning of selected ML algorithms such as ANN
4. Evaluation of Models


## Documentation
For detailed information on the project, dataset, methodology, and evaluation metrics, please refer to the [project documentation](docs/README.md).

## Contributing
Contributions are welcome! If you have any suggestions, improvements, or bug fixes, please open an issue or submit a pull request.


## Acknowledgements
- The Telco Customer Churn dataset used in this project is provided by [IBM Sample Data Sets](https://www.ibm.com/communities/analytics/watson-analytics-blog/guide-to-sample-datasets/).
- Special thanks to the contributors and maintainers of the libraries used in this project.
