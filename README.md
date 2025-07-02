# Linear-Regression---Machine-Learning-Project
Synthetic Data Creation and Predictive Modeling using Python

Project Description:
This project focuses on the complete lifecycle of building a predictive data model—from data creation to visualization, statistical analysis, data splitting, and model building.

The project is divided into five parts:

Part 1 – Data Creation (30 points)
Using Python’s random number generators and distribution functions, I created a synthetic dataset with four numerical variables:
Two variables followed a Normal Distribution with the same mean but different standard deviations.
One variable was based on a different distribution, such as uniform, exponential, or binomial.
The fourth variable was a non-linear combination of the other three variables (not just a simple sum).
To ensure reusability and clarity, I modularized the data generation code into functions.

Part 2 – Data Visualization (10 points)
I used Matplotlib and Seaborn to create a 4x4 scatterplot matrix, visualizing relationships between all four variables.
The plots included:
Axis labels
Titles
Distinct colors for each variable pair
The entire visualization process was encapsulated in a separate Python function.

Part 3 – Descriptive Statistics (10 points)
For each variable, I calculated and displayed the following statistical measures:
Mean
Median
Mode
Standard Deviation
Range
I organized this code into a single function that took the dataset as input and returned a clean, readable summary table of statistics.

Part 4 – Data Splitting (20 points)
I split the dataset into Training (60%), Validation (20%), and Test (20%) sets using Scikit-learn’s train_test_split function.
The splitting logic was modularized into a reusable function that accepted the dataset and desired split ratios as arguments.

Part 5 – Linear Regression Model (30 points)
Using the training set, I built a Linear Regression Model with sklearn.linear_model.LinearRegression to predict the derived variable (fourth variable) based on the other three.
Key steps included:
Training the model on the training set
Validating the model on the validation set
Testing and reporting the model performance on the test set
Visualizing the predicted vs. actual values using a scatter plot
I wrote the model-building and evaluation steps inside a modular and reusable Python function.
