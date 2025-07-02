# Linear-Regression---Machine-Learning-Project
Synthetic Data Creation and Predictive Modeling using Python

Project Description:
This project focuses on the complete lifecycle of building a predictive data model—from data creation to visualization, statistical analysis, data splitting, and model building.

The project is divided into five parts:

Part 1 – Data Creation:
Using Python’s random number generators and distribution functions, I will create a synthetic dataset with four numerical variables:
Two variables will follow a Normal Distribution with the same mean but different standard deviations.
One variable will be based on a different distribution, such as uniform, exponential, or binomial.
The fourth variable will be a non-linear combination of the other three variables (not just a simple sum).
To ensure code reusability and clarity, all data generation steps will be written as modular Python functions.

Part 2 – Data Visualization:
I will use Matplotlib and Seaborn to create a 4x4 scatterplot matrix, visualizing relationships between all four variables.
The plots will include:
Axis labels
Titles
Distinct colors for each variable pair
The entire visualization process will also be modularized into a separate Python function.

Part 3 – Descriptive Statistics:
For each variable, I will calculate and display the following statistical measures:
Mean
Median
Mode
Standard Deviation
Range
The code will be organized into a single function that takes the dataset as input and returns a clean, readable summary table of statistics.

Part 4 – Data Splitting:
The dataset will be split into Training (60%), Validation (20%), and Test (20%) sets using Scikit-learn’s train_test_split function.
This splitting logic will be modularized into a reusable function that accepts the dataset and desired split ratios as arguments.

Part 5 – Linear Regression Model:
Using the training set, I will build a Linear Regression Model using sklearn.linear_model.LinearRegression to predict the derived variable (fourth variable) based on the other three.
Key steps include:
Training the model on the training set
Validating the model on the validation set
Testing and reporting model performance on the test set
Visualizing predicted vs. actual values using a scatter plot
Model building and evaluation will also be written inside a clean, reusable function.
