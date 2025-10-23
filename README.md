# Data Acquisition and Version Control Assignment

## Project Overview

This repository contains a Google Colab notebook and related files for the "Data Acquisition and Version Control with Git" homework assignment. The project focuses on acquiring and exploring a dataset, analyzing it with Python, and managing the workflow using Git and GitHub. The chosen dataset is the **Iris dataset** from the UCI Machine Learning Repository, a classic dataset used for educational purposes in data science.

## Dataset Description

- **Source**: UCI Machine Learning Repository [](https://archive.ics.uci.edu/ml/datasets/iris)
- **Description**: Contains 150 samples of iris flowers with measurements of sepal length, sepal width, petal length, petal width, and species (Setosa, Versicolor, Virginica).
- **Collection Method**: Manually measured by R.A. Fisher in 1936.
- **Reliability**: Peer-reviewed and widely used in machine learning research.
- **Limitations/Biases**: Small sample size (150 records) and data from one location (Quebec, Canada), which may not represent global iris variations.

## Tasks Completed

### Part 1: Data Acquisition & Exploration

1. **Dataset Selection**: Selected the Iris dataset and documented its collection method, reliability, and limitations.
2. **Data Import**: Loaded the dataset into a Google Colab notebook using pandas.
3. **Data Exploration**: Analyzed dataset shape, columns, data types, summary statistics, and missing values. Created two visualizations (histogram and scatter plot) and interpreted an insight about species classification.
4. **Ethical & Legal Reflection**: Evaluated the dataset's public domain license, privacy implications (none, as no personal data), GDPR irrelevance, and potential biases (geographic limitation).
5. **Notebook Presentation**: Organized the Colab notebook with clear Markdown headings and code comments.

### Part 2: Version Control with Git

1. **Repository Setup**: Created this GitHub repository with a `.gitignore` file.
2. **Local Project Initialization**: Initialized a local Git repository, added the notebook and dataset.
3. **Commit and Push**: Made multiple commits with descriptive messages and pushed to GitHub.
4. **Branching and Merging**: Created a feature branch for ethical reflection, merged it into main, and pushed changes.
5. **Collaboration**: Invited a collaborator to review the repository.

## Ethical Reflection

The Iris dataset is public domain, allowing unrestricted use. It contains no personal data, posing no privacy concerns or GDPR applicability. However, its geographic limitation (Canada) may bias models if applied globally. Ethically, users should validate models on diverse datasets to ensure fairness and avoid overgeneralization.

## Deliverables

- **Colab Notebook**: [https://colab.research.google.com/drive/1NMjFwKEmMj9BG_9QuAJhX8hJ74sIqgVc?usp=sharing]
- **GitHub Repository**: [https://github.com/paruyr-gevorgyan/data_acquisition_git]
- **Screenshots**: Available in the repository (see `screenshots` folder for Git log and merge confirmation).

## How to Run

1. Open the Colab notebook via the provided link.
2. Ensure `pandas`, `matplotlib`, and `seaborn` are installed (`!pip install seaborn` if needed).
3. Run all cells to reproduce the analysis.
4. Clone this repository locally\` `git clone https://github.com/paruyr-gevorgyan/data_acquisition_git.git` to view version history.

## Contact

For questions or feedback, contact `paruyr-gevorgyan` via GitHub or <gevorgyan.paruyr.2002@gmail.com>.
