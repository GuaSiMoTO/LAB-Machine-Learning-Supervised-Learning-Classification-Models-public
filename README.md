# LAB-Machine-Learning-Supervised-Models-Classification-Models

![Image](https://user-images.githubusercontent.com/970858/63474771-d6734700-c469-11e9-83bb-9429da563909.png)

## Wine Quality Prediction

Introduction
In this project, we will walk through a comprehensive Machine Learning workflow using a wine quality dataset. Our goal is to build and compare different supervised classification models to predict wine quality based on several features such as acidity, alcohol level, and pH. We will explore and evaluate models including Logistic Regression, K-Nearest Neighbors, Decision Trees, Support Vector Machines, and Random Forest. Additionally, we will apply cross-validation techniques to optimize the model performance.

You will work with a dataset that includes various attributes of wines and their quality ratings. Your goal is to evaluate different classification models, assess their performance, and select the best model for predicting wine quality.

## Initial Setup

### Requirements
Start by forking the provided GitHub repository to your account and then clone it locally. This will be your workspace for completing the lab exercises.
- [Learn how to fork this repo](https://docs.github.com/en/get-started/exploring-projects-on-github/contributing-to-a-project)
- Clone this repo into your code/labs folder.

### Setup Instructions
To run the notebook and reproduce the results, follow these steps:
1. Clone the repository:
    ```bash
    git clone https://github.com/codeskills-ai/LAB-Machine-Learning-Supervised-Models-Classification-Models.git
    cd LAB-Machine-Learning-Supervised-Models-Classification-Models
    ```

2. Create a virtual environment and install the required packages:

    ```bash
    pip install -r requirements.txt
    ```

3. Start Jupyter Notebook:
   ```bash
   jupyter notebook
   ``` 

To test that everything is set up correctly, run the first cell in the notebook. This cell usually contains import statements and initial setup code. If it runs without errors, you are ready to start solving the exercises.

You can write and execute your code in the provided cells within the notebook. Any outputs, including print statements and visualizations, will be displayed directly in the notebook, making it easy to debug and verify your solutions.

## Workflow

### Iteration 1: Data Load

Load the Wine Quality dataset, which contains various attributes of wines and their quality ratings. Use Python libraries to load the dataset into a pandas DataFrame for further analysis.

- Import the necessary Python libraries: `pandas` and `sklearn.datasets`.
- Load the `load_wine` dataset, which includes data on wine features and quality.
- Display the first few rows of the dataset to understand its structure and the type of data it contains.

**NOTE**: This initial inspection is crucial as it sets the stage for the next steps of data cleaning and visualization.

### Iteration 2: Data Exploration

In this section, we will explore the dataset visually to understand the distribution of the target variable (`target`) and its relationship with other features.

- Import the necessary visualization libraries: `seaborn` and `matplotlib.pyplot`.
- Visualize the distribution of the target variable (`target`) using a histogram.
- Use a pairplot to generate scatter plots for some features (e.g., `alcohol`, `malic_acid`, `ash`) against the target variable (`target`).

### Iteration 3: Feature Selection

- **Feature Selection**: Select relevant features from the dataset that will be used for model training. Features include chemical properties such as:
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
  
- **Target Variable**: The target variable `target` indicates the quality class of the wine, categorized into three classes: 0, 1, or 2.

### Iteration 4: Data Splitting

- **Split the Data**: Split the dataset into training and testing sets using `train_test_split` from `sklearn.model_selection`. The split ensures that the model is trained on one portion of the data and tested on a separate portion to evaluate its performance.

### Iteration 5: Train and Evaluate Classification Models

Train and evaluate various classification models on the wine dataset to predict the quality class.

- **Logistic Regression**: Train and evaluate a Logistic Regression model.
- **K-Nearest Neighbors (K-NN)**: Train and evaluate a K-NN model.
- **Decision Tree**: Train and evaluate a Decision Tree model.
- **Support Vector Machine (SVM)**: Train and evaluate an SVM model.
- **Random Forest**: Train and evaluate a Random Forest model.

### Iteration 6: Model Comparison

Compare the trained models in terms of accuracy. Use a bar chart to visualize the accuracy of each model to identify which one performs best.

### Iteration 7: Cross-Validation

Apply cross-validation to each model to evaluate their mean accuracy and standard deviation. This step ensures the robustness of the models by testing them on different subsets of the data.

### Iteration 8: Conclusions

Analyze and discuss which model is the most suitable for the wine dataset classification task based on the accuracy, cross-validation results, and overall model performance.



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
