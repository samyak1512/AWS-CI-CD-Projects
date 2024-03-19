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

<p align="center">
  <img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/ec559a9f6bfd399b82bb44393651661b08aaf7ba/icons/folder-markdown-open.svg" width="100" alt="project-logo">
</p>
<p align="center">
    <h1 align="center">AWS-CI-CD-PROJECTS</h1>
</p>
<p align="center">
    <em><code>► INSERT-TEXT-HERE</code></em>
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

<br><!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary><br>

- [ Overview](#-overview)
- [ Features](#-features)
- [ Repository Structure](#-repository-structure)
- [ Modules](#-modules)
- [ Getting Started](#-getting-started)
  - [ Installation](#-installation)
  - [ Usage](#-usage)
  - [ Tests](#-tests)
- [ Project Roadmap](#-project-roadmap)
- [ Contributing](#-contributing)
- [ License](#-license)
- [ Acknowledgments](#-acknowledgments)
</details>
<hr>

##  Overview

<code>► INSERT-TEXT-HERE</code>

---

##  Features

<code>► INSERT-TEXT-HERE</code>

---

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

##  Modules

<details closed><summary>.</summary>

| File                                                                                              | Summary                         |
| ---                                                                                               | ---                             |
| [requirements.txt](https://github.com/samyak1512/AWS-CI-CD-Projects/blob/master/requirements.txt) | <code>► INSERT-TEXT-HERE</code> |
| [Dockerfile](https://github.com/samyak1512/AWS-CI-CD-Projects/blob/master/Dockerfile)             | <code>► INSERT-TEXT-HERE</code> |
| [setup.py](https://github.com/samyak1512/AWS-CI-CD-Projects/blob/master/setup.py)                 | <code>► INSERT-TEXT-HERE</code> |
| [app.py](https://github.com/samyak1512/AWS-CI-CD-Projects/blob/master/app.py)                     | <code>► INSERT-TEXT-HERE</code> |

</details>

<details closed><summary>.github.workflows</summary>

| File                                                                                                                    | Summary                         |
| ---                                                                                                                     | ---                             |
| [docker-publish.yml](https://github.com/samyak1512/AWS-CI-CD-Projects/blob/master/.github/workflows/docker-publish.yml) | <code>► INSERT-TEXT-HERE</code> |
| [docker_hub.yml](https://github.com/samyak1512/AWS-CI-CD-Projects/blob/master/.github/workflows/docker_hub.yml)         | <code>► INSERT-TEXT-HERE</code> |
| [main.yaml](https://github.com/samyak1512/AWS-CI-CD-Projects/blob/master/.github/workflows/main.yaml)                   | <code>► INSERT-TEXT-HERE</code> |
| [docker-image.yml](https://github.com/samyak1512/AWS-CI-CD-Projects/blob/master/.github/workflows/docker-image.yml)     | <code>► INSERT-TEXT-HERE</code> |

</details>

<details closed><summary>templates</summary>

| File                                                                                            | Summary                         |
| ---                                                                                             | ---                             |
| [index.html](https://github.com/samyak1512/AWS-CI-CD-Projects/blob/master/templates/index.html) | <code>► INSERT-TEXT-HERE</code> |
| [home.html](https://github.com/samyak1512/AWS-CI-CD-Projects/blob/master/templates/home.html)   | <code>► INSERT-TEXT-HERE</code> |

</details>

<details closed><summary>notebook</summary>

| File                                                                                                                                           | Summary                         |
| ---                                                                                                                                            | ---                             |
| [1 . EDA STUDENT PERFORMANCE .ipynb](https://github.com/samyak1512/AWS-CI-CD-Projects/blob/master/notebook/1 . EDA STUDENT PERFORMANCE .ipynb) | <code>► INSERT-TEXT-HERE</code> |
| [2. MODEL TRAINING.ipynb](https://github.com/samyak1512/AWS-CI-CD-Projects/blob/master/notebook/2. MODEL TRAINING.ipynb)                       | <code>► INSERT-TEXT-HERE</code> |

</details>

<details closed><summary>notebook.catboost_info</summary>

| File                                                                                                                                 | Summary                         |
| ---                                                                                                                                  | ---                             |
| [catboost_training.json](https://github.com/samyak1512/AWS-CI-CD-Projects/blob/master/notebook/catboost_info/catboost_training.json) | <code>► INSERT-TEXT-HERE</code> |

</details>

<details closed><summary>src</summary>

| File                                                                                          | Summary                         |
| ---                                                                                           | ---                             |
| [exception.py](https://github.com/samyak1512/AWS-CI-CD-Projects/blob/master/src/exception.py) | <code>► INSERT-TEXT-HERE</code> |
| [logger.py](https://github.com/samyak1512/AWS-CI-CD-Projects/blob/master/src/logger.py)       | <code>► INSERT-TEXT-HERE</code> |
| [utils.py](https://github.com/samyak1512/AWS-CI-CD-Projects/blob/master/src/utils.py)         | <code>► INSERT-TEXT-HERE</code> |

</details>

<details closed><summary>src.pipeline</summary>

| File                                                                                                                 | Summary                         |
| ---                                                                                                                  | ---                             |
| [predict_pipeline.py](https://github.com/samyak1512/AWS-CI-CD-Projects/blob/master/src/pipeline/predict_pipeline.py) | <code>► INSERT-TEXT-HERE</code> |

</details>

<details closed><summary>src.components</summary>

| File                                                                                                                         | Summary                         |
| ---                                                                                                                          | ---                             |
| [data_ingestion.py](https://github.com/samyak1512/AWS-CI-CD-Projects/blob/master/src/components/data_ingestion.py)           | <code>► INSERT-TEXT-HERE</code> |
| [model_trainer.py](https://github.com/samyak1512/AWS-CI-CD-Projects/blob/master/src/components/model_trainer.py)             | <code>► INSERT-TEXT-HERE</code> |
| [data_transformation.py](https://github.com/samyak1512/AWS-CI-CD-Projects/blob/master/src/components/data_transformation.py) | <code>► INSERT-TEXT-HERE</code> |

</details>

---

##  Getting Started

**System Requirements:**

* **Python**: `version x.y.z`

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
> $ python main.py
> ```

###  Tests

> Run the test suite using the command below:
> ```console
> $ pytest
> ```

---

##  Project Roadmap

- [X] `► INSERT-TASK-1`
- [ ] `► INSERT-TASK-2`
- [ ] `► ...`

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

This project is protected under the [SELECT-A-LICENSE](https://choosealicense.com/licenses) License. For more details, refer to the [LICENSE](https://choosealicense.com/licenses/) file.

---

##  Acknowledgments

- List any resources, contributors, inspiration, etc. here.

[**Return**](#-overview)

---

AWS_ECR_LOGIN_URI = demo>>  566373416292.dkr.ecr.ap-south-1.amazonaws.com

ECR_REPOSITORY_NAME = simple-app
