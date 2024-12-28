Iris Species Classification Using Logistic Regression
Overview
This project demonstrates the use of logistic regression to classify iris species based on sepal length, sepal width, petal length, and petal width. The dataset contains three classes of 50 instances each, where each class refers to a type of iris plant.

Dataset Information
The dataset includes:

sepal_length: Sepal length in cm

sepal_width: Sepal width in cm

petal_length: Petal length in cm

petal_width: Petal width in cm

species: Target variable with three classes - Iris Setosa, Iris Versicolour, Iris Virginica

Project Structure
IRIS.csv: The dataset file.

iris_classification.ipynb: Jupyter Notebook with the complete workflow.

Requirements
Python 3.x

numpy

pandas

matplotlib

seaborn

scikit-learn

Install the required packages using:

bash
pip install numpy pandas matplotlib seaborn scikit-learn
Steps to Execute
Import Modules:

Import necessary libraries for data manipulation, visualization, and model building.

Load the Dataset:

Load the dataset into a pandas DataFrame and inspect the first few rows.

Data Preprocessing:

Check for missing values and handle them if any.

Encode categorical labels using LabelEncoder.

Exploratory Data Analysis (EDA):

Visualize feature distributions using histograms.

Compute the correlation matrix and plot a heatmap.

Model Training:

Split the data into training and testing sets.

Train a logistic regression model on the training data.

Model Evaluation:

Evaluate model performance using accuracy and classification report on both training and testing sets.

Usage
Clone the repository:

bash
git clone https://github.com/RAGUL1531/Irsis-Flowers-detection
cd iris-classification
Open and run the Jupyter Notebook:

bash
jupyter notebook iris_classification.ipynb
Results
The logistic regression model achieved the following accuracy:

Training Accuracy: 96.67%

Testing Accuracy: 100%

Conclusion
The logistic regression model performed exceptionally well on the Iris dataset, demonstrating its effectiveness in multi-class classification tasks. Further improvements can include trying different algorithms or hyperparameter tuning for even better results.

License
This project is licensed under the MIT License. See the LICENSE file for more details.

Acknowledgements
The Iris dataset is a well-known dataset in the machine learning community, provided by the UCI Machine Learning Repository.

Special thanks to the open-source community for providing the tools and libraries used in this project.
 
