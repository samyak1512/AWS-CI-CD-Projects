<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/93/Amazon_Web_Services_Logo.svg/1200px-Amazon_Web_Services_Logo.svg.png" width="100" alt="project-logo">
</p>
<p align="center">
    <h1 align="center">AWS-CI-CD-PROJECTS</h1>
</p>
<p align="center">
	<img src="https://img.shields.io/github/license/samyak1512/AWS-CI-CD-Projects?style=default&logo=opensourceinitiative&logoColor=white&color=0080ff" alt="license">
	<img src="https://img.shields.io/github/last-commit/samyak1512/AWS-CI-CD-Projects?style=default&logo=git&logoColor=white&color=0080ff" alt="last-commit">
	<img src="https://img.shields.io/github/languages/top/samyak1512/AWS-CI-CD-Projects?style=default&color=0080ff" alt="repo-top-language">
	<img src="https://img.shields.io/github/languages/count/samyak1512/AWS-CI-CD-Projects?style=default&color=0080ff" alt="repo-language-count">
<p>
<p align="center">
	<!-- default option, no dependency badges. -->
</p>

## Examination Score Predictor - [Online Link](http://13.233.152.180:8080/predictdata) 
This project aims to understand how a student’s performance (test scores) is affected by other variables such as Gender, Ethnicity, Parental level of education, Lunch, and Test preparation course.

## Life cycle of Machine learning Project
1. Understanding the Problem Statement
2. Data Collection
3. Data Checks to perform
4. Exploratory data analysis
5. Data Pre-Processing
6. Model Training
7. Choose best model
8. Save the best model
9. Pipline for data ingestion
10. Pipeline for base model training
11. Prediction pipeline
12. Creating index and home pages
13. Docker Image generation and uploading on AWS ECR
14. Configuring Github Workflows
15. Deploying Docker Image on EC2 instance

## 1) Problem statement
This project understands how the student’s performance (test scores) is affected by other variables such as Gender, Ethnicity, Parental level of education, Lunch, and Test preparation course.
## 2) Data Collection
The data was collected from Student_Performance_Data on Kaggle
## 3) Data Checks to perform
1. Check Missing values
2. Check Duplicates
3. Check data type
4. Check the number of unique values of each column
5. Check statistics of data set
6. Check various categories present in the different categorical column
## 4) Exploratory Data Analysis
<img width="903" alt="image" src="https://github.com/samyak1512/AWS-CI-CD-Projects/assets/43640144/c9512b4a-252f-4613-9744-084c3c398145">
<img width="907" alt="image" src="https://github.com/samyak1512/AWS-CI-CD-Projects/assets/43640144/c5c734d4-900f-4a8e-936a-3ce926794ba3">

## 6) Model Training
Tested various different regressors, including Linear, Lasso, Ridge, KNN, Decision Tree, Random Forest, XGBoost, Caboost and Adabaoost regressor and calculated R^2 for each of them.
<img width="695" alt="image" src="https://github.com/samyak1512/AWS-CI-CD-Projects/assets/43640144/b222beb6-92fd-4648-bc54-5e15b865a0e4">

## 7) Perfomance of each model
<img width="281" alt="image" src="https://github.com/samyak1512/AWS-CI-CD-Projects/assets/43640144/978399f6-1657-4abe-83bb-4646356fc21a">

## 8) Plotting y_pred and y_test
<img width="450" alt="image" src="https://github.com/samyak1512/AWS-CI-CD-Projects/assets/43640144/3452321c-f686-4c5b-89cb-d4827b50a95e">                <img width="450" alt="image" src="https://github.com/samyak1512/AWS-CI-CD-Projects/assets/43640144/cf4f7d3c-b0b8-49a9-9d4d-b213c4562de7">

## 9) Data Ingestion Pipeline
It utilizes various modules and components such as data ingestion, transformation, and model training. The DataIngestion class reads a CSV dataset, performs a train-test split, and saves the split data into separate CSV files. Subsequently, the DataTransformation class transforms the data, and finally, the ModelTrainer class is employed to train a machine learning model. This script offers a structured approach to streamline the process of data preprocessing and model training, making it suitable for machine learning projects.

## 10) Pipeline for base model training
Defines a ModelTrainer class responsible for training machine learning models and selecting the best performing model based on evaluation metrics. It initializes various regression models and their corresponding hyperparameters. The initiate_model_trainer method splits the input data into training and testing sets, evaluates each model's performance using cross-validation, selects the best performing model, and saves it to a file. If the best model's performance does not meet a specified threshold, an exception is raised. Finally, the R-squared score of the best model on the test set is returned. The script demonstrates a robust approach to model training and selection suitable for regression tasks.

## 11) Prediction Pipeline
Defines a PredictPipeline class responsible for making predictions using a trained machine learning model. It also defines a CustomData class to create custom data instances for prediction.

The PredictPipeline class contains a predict method that loads the trained model and preprocessing pipeline from files, scales the input features using the preprocessing pipeline, makes predictions using the model, and returns the predictions.

The CustomData class represents custom data instances with attributes such as gender, race_ethnicity, parental_level_of_education, lunch, test_preparation_course, reading_score, and writing_score. It provides a method get_data_as_data_frame to convert the custom data instance into a pandas DataFrame.

These classes can be utilized to deploy the trained model for making predictions on new data instances efficiently.





##  Repository Structure

```sh
└── AWS-CI-CD-Projects/
    ├── .github
    │   └── workflows
    ├── Dockerfile
    ├── LICENSE
    ├── README.md
    ├── app.py
    ├── artifacts
    │   ├── data.csv
    │   ├── model.pkl
    │   ├── preprocessor.pkl
    │   ├── test.csv
    │   └── train.csv
    ├── notebook
    │   ├── 1 . EDA STUDENT PERFORMANCE .ipynb
    │   ├── 2. MODEL TRAINING.ipynb
    │   ├── catboost_info
    │   └── data
    ├── requirements.txt
    ├── setup.py
    ├── src
    │   ├── __init__.py
    │   ├── components
    │   ├── exception.py
    │   ├── logger.py
    │   ├── pipeline
    │   └── utils.py
    └── templates
        ├── home.html
        └── index.html
```

---



##  Getting Started

**System Requirements:**

* **Python**: `version 3.8`

###  Installation

<h4>From <code>source</code></h4>

> 1. Clone the AWS-CI-CD-Projects repository:
>
> ```console
> $ git clone https://github.com/samyak1512/AWS-CI-CD-Projects
> ```
>
> 2. Change to the project directory:
> ```console
> $ cd AWS-CI-CD-Projects
> ```
>
> 3. Install the dependencies:
> ```console
> $ pip install -r requirements.txt
> ```

###  Usage

<h4>From <code>source</code></h4>

> Run AWS-CI-CD-Projects using the command below:
> ```console
> $ python app.py
> ```

###  Tests

> Run the test suite using the command below:
> ```console
> $ pytest
> ```

---


##  Contributing

Contributions are welcome! Here are several ways you can contribute:

- **[Report Issues](https://github.com/samyak1512/AWS-CI-CD-Projects/issues)**: Submit bugs found or log feature requests for the `AWS-CI-CD-Projects` project.
- **[Submit Pull Requests](https://github.com/samyak1512/AWS-CI-CD-Projects/blob/main/CONTRIBUTING.md)**: Review open PRs, and submit your own PRs.
- **[Join the Discussions](https://github.com/samyak1512/AWS-CI-CD-Projects/discussions)**: Share your insights, provide feedback, or ask questions.

<details closed>
<summary>Contributing Guidelines</summary>

1. **Fork the Repository**: Start by forking the project repository to your github account.
2. **Clone Locally**: Clone the forked repository to your local machine using a git client.
   ```sh
   git clone https://github.com/samyak1512/AWS-CI-CD-Projects
   ```
3. **Create a New Branch**: Always work on a new branch, giving it a descriptive name.
   ```sh
   git checkout -b new-feature-x
   ```
4. **Make Your Changes**: Develop and test your changes locally.
5. **Commit Your Changes**: Commit with a clear message describing your updates.
   ```sh
   git commit -m 'Implemented new feature x.'
   ```
6. **Push to github**: Push the changes to your forked repository.
   ```sh
   git push origin new-feature-x
   ```
7. **Submit a Pull Request**: Create a PR against the original project repository. Clearly describe the changes and their motivations.
8. **Review**: Once your PR is reviewed and approved, it will be merged into the main branch. Congratulations on your contribution!
</details>

<details closed>
<summary>Contributor Graph</summary>
<br>
<p align="center">
   <a href="https://github.com{/samyak1512/AWS-CI-CD-Projects/}graphs/contributors">
      <img src="https://contrib.rocks/image?repo=samyak1512/AWS-CI-CD-Projects">
   </a>
</p>
</details>

---

##  License

This project is protected under the [MIT](https://github.com/samyak1512/AWS-CI-CD-Projects/blob/main/LICENSE) License.
---

##  Acknowledgments

- List any resources, contributors, inspiration, etc. here.

