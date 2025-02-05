# Maternal-Health-Risk

Overview
This project aims to predict potential health risks during pregnancy using multiple machine learning algorithms. The model takes health-related data, including blood pressure (BP), heart rate, age of conception, and more, to provide accurate predictions about health risks. The system uses Artificial Neural Networks (ANNs), Support Vector Machines (SVMs), Decision Trees, and Random Forests to achieve high accuracy, with over 80% accuracy in all models.

# Features
Multiple ML Algorithms: Includes implementations of ANNs, SVMs, Decision Trees, and Random Forest models.
Data Preprocessing: Cleans and preprocesses raw health data for better model performance.
Model Evaluation: Compares the performance of multiple models to select the best one.
Accurate Predictions: Provides accurate health risk information based on various health indicators.
Dataset
The project uses a dataset that includes features such as:

Blood Pressure (BP)
Heart Rate
Age of Conception
Other relevant health data (e.g., weight, BMI, etc.)
Installation
To run the project locally, follow the steps below:

# Prerequisites
Make sure you have Python 3.x and the following libraries installed:

numpy
pandas
scikit-learn
tensorflow (for ANNs)
matplotlib
seaborn (for data visualization)

# Usage
Once the model is trained, you can input new health data to predict the health risks associated with pregnancy. The prediction results will be displayed, along with the corresponding risk level.


# Sample data format
input_data = {
    "BP": 120,
    "Heart_Rate": 75,
    "Age_of_Conception": 29,
    # Add other relevant health data here
}


# Output:
The model will return a risk level prediction along with an explanation based on the input data.

# Model Performance
Accuracy: Over 80% accuracy in all tested models.
Best Performing Model: A detailed comparison of model performance is available in the model_comparison.py script.
Contributing
Feel free to fork this repository, submit issues, and create pull requests to contribute improvements or add new features.

# License
This project is licensed under the MIT License.
