# Random Forest Digit Classifier 

![tom-hanks-forest-gump](https://user-images.githubusercontent.com/57488820/232581309-205fcd08-20a1-4a59-9768-cedc7512dd6c.gif)


This project is a Python implementation of a random forest digit classifier using scikit-learn library. The code takes images of handwritten digits from the load_digits dataset and trains a random forest model to classify them.

## Installation 🚀
To run this code, you will need to have Python 3.x installed on your machine along with the following libraries:

- matplotlib
- seaborn
- scikit-learn

You can install these libraries using pip by running the following command in your terminal:

- pip install matplotlib seaborn scikit-learn

## Usage 👨🏼‍💻
To use this code, simply run the random_forest_digit_classifier.py file in your Python environment. The code will load the load_digits dataset, plot the digits and train a random forest model with 1000 estimators.

After training the model, the code will display a confusion matrix using the confusion_matrix function from scikit-learn and heatmap function from seaborn. The confusion matrix shows the number of true and predicted labels for each digit class.

You can modify the code to change the number of estimators used for training the model or to use a different dataset.
