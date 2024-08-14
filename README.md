# LAB_Machine-Learning-Supervised-Models-Classification

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
Imagine you are a data scientist at a marketing firm. Your manager has asked you to predict whether a customer will make a purchase based on several features, such as age, income, and browsing behavior. Your task is to apply and compare different classification models to determine which one performs the best on this dataset.

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

### Inspect the dataset
- Display the basic information about the dataset, such as the number of rows, columns, and data types of each column.
- Use descriptive statistics to understand the distribution of numerical and categorical variables.

[describe - Pandas Documentation](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.describe.html)

This initial inspection is crucial as it sets the stage for the next steps of data cleaning and visualization.

## Iteration 2: Data Cleaning
With a solid understanding of the dataset's structure, it's time to focus on cleaning the data. Data cleaning ensures that the dataset is accurate, consistent, and ready for analysis. This step is essential to avoid misleading results and ensure that your insights are based on high-quality data.



## Iteration 3: Data Visualization with Matplotlib and Seaborn
Having cleaned the data, you're now ready to explore it visually. Visualization is a powerful tool for uncovering patterns, trends, and anomalies in the data. In this iteration, you'll create various plots to get a better understanding of the dataset.




## Iteration 4: Advanced Visualizations and Insights


## Iteration 5:  
 
Standardizing numerical variables is an important step, especially when preparing data for machine learning models. This iteration focuses on scaling your data to ensure that all features contribute equally to the analysis.



## Iteration 6: Hypothesis Testing

Hypothesis testing allows you to make statistical inferences about the data. In this iteration, you'll compare variables between groups to determine if observed differences are statistically significant.



## Iteration 7: Dimensionality Reduction with PCA

In this iteration, you'll apply Principal Component Analysis (PCA) to reduce the dimensionality of the dataset. This technique helps simplify the dataset by transforming it into a lower-dimensional space while retaining the most important features.



## Submission
Once you have completed your analysis and visualizations, push your Jupyter notebook to your forked GitHub repository. Ensure that your final submission includes narratives explaining your visualizations and insights.


```bash
$ git add .
$ git commit -m "done"
$ git push origin main
```

Then create a Pull Request!!

## Additional Resources

- [Pandas Documentation](https://pandas.pydata.org/pandas-docs/stable/)
- [Matplotlib Documentation](https://matplotlib.org/)
- [Seaborn Documentation](https://seaborn.pydata.org/)
- [Ploty Documentation](https://plotly.com/python/).
- [Mann-Whitney U test - Scipy Documentation](https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.mannwhitneyu.html).

![happy_coding](https://user-images.githubusercontent.com/970858/63899010-c23fc480-c9ea-11e9-84a2-542907e42362.png)
