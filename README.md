# LAB-Machine-Learning-Supervised-Models-Classification-Models

![Image](https://user-images.githubusercontent.com/970858/63474771-d6734700-c469-11e9-83bb-9429da563909.png)

## Introduction
Welcome to the Supervised Learning Classification Models lab! In this lab, you will apply various classification models to a real-world dataset. As a data scientist at a marketing firm, your task is to analyze customer data and predict whether a customer will make a purchase based on several features.

You will work with a dataset that includes customer information and their purchase behavior. Your goal is to apply different classification models, evaluate their performance, and select the best model for predicting customer purchases.

## Initial Setup
### Requirements
Start by forking the provided GitHub repository to your account and then clone it locally. This will be your workspace for completing the lab exercises.
- [Learn how to fork this repo](https://docs.github.com/en/get-started/exploring-projects-on-github/contributing-to-a-project)
- Clone this repo into your code/labs folder.

### Scenario
Imagine you are a data scientist at a winery. Your manager has asked you to predict the quality of a wine based on several features, such as acidity, alcohol level, and pH. Your task is to apply and compare different classification models to determine which one performs the best on this wine dataset.

### Starter Code
You have to solve the different problems in the LAB-Classification-Models.ipynb notebook.

1. Open your terminal and navigate to the `cloned-repo` directory:

    ```bash
    cd path/to/your/cloned-repo/
    ```

2. Launch Jupyter Notebook:

    ```bash
    jupyter lab
    ```

3. In the Jupyter Notebook interface, open the `LAB-Exploratory-Data-Analysis.ipynb` file.

To test that everything is set up correctly, run the first cell in the notebook. This cell usually contains import statements and initial setup code. If it runs without errors, you are ready to start solving the exercises.

You can write and execute your code in the provided cells within the notebook. Any outputs, including print statements and visualizations, will be displayed directly in the notebook, making it easy to debug and verify your solutions.


### Iteration 0: Install Dependencies

Make sure you have all the necessary libraries installed by using the `requirements.txt` file provided. You can install the dependencies with the following command:

```bash
pip install -r requirements.txt
```

## Iteration 1: Load and Inspect the Dataset
Now that you've set up your environment, let's dive into the heart of our data analysis task. Our first step is to load and inspect the dataset, which is crucial for understanding its structure and contents. This foundational step will help you get acquainted with the data, allowing you to identify what needs to be cleaned or further explored.

### Load the dataset
Using pandas, we will load the provided CSV file. This will give us an initial glimpse into the dataset, including the columns and the first few rows of data.

```python
from sklearn.datasets import load_wine

# Load the digits dataset
wine = load_wine()
```

### Inspect the dataset
- Display the basic information about the dataset, such as the number of rows, columns, and data types of each column.
- Use descriptive statistics to understand the distribution of numerical and categorical variables.

This initial inspection is crucial as it sets the stage for the next steps of data cleaning and visualization.

## Iteration 1: Dataset Splitting

- **Features (`X`)**: Select all columns from the dataset that contain information about the chemical properties of the wine. This includes the following variables:

  - `alcohol`
  - `malic_acid`
  - `ash`
  - `alcalinity_of_ash`
  - `magnesium`
  - `total_phenols`
  - `flavanoids`
  - `nonflavanoid_phenols`
  - `proanthocyanins`
  - `color_intensity`
  - `hue`
  - `od280/od315_of_diluted_wines`
  - `proline`

- **Target Variable (`y`)**: Select the column that corresponds to the wine class, which identifies the category of each wine into one of the three possible classes.

  - `target` (This is the target variable that indicates which class each wine sample belongs to: 0, 1, or 2).

## Iteration 2: Training and Evaluation of Models
- Train and evaluate a Logistic Regression model.
- Train and evaluate a K-Nearest Neighbors (K-NN) model.
- Train and evaluate a Decision Tree model.
- Train and evaluate a Support Vector Machine (SVM) model.
- Train and evaluate a Random Forest model.

## Iteration 3: Model Comparison
- Compare the trained models in terms of accuracy using a bar chart to visualize the results.

## Iteration 4: Cross-Validation
- Perform cross-validation for each model, evaluating their mean accuracy and standard deviation.

## Iteration 5: Conclusions
- Analyze and discuss which model is the most suitable for the Wine dataset classification task based on the obtained metrics.


## Submission
Once you have completed your analysis and visualizations, push your Jupyter notebook to your forked GitHub repository. Ensure that your final submission includes narratives explaining your visualizations and insights.


```bash
$ git add .
$ git commit -m "done"
$ git push origin main
```

Then create a Pull Request!!

## Additional Resources

- [ ]()
- [ ](/)
- [ ]()
- [ ]().
- [ ]().

![happy_coding](https://user-images.githubusercontent.com/970858/63899010-c23fc480-c9ea-11e9-84a2-542907e42362.png)
