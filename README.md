
# Social Media Bot Detection Project - ML1

This repository contains all the materials related to the Social Media Bot Detection project developed as part of the Machine Learning I course at Universidad Panamericana by team members David Arturo Hernández Gómez and Adriana Leticia Martínez Estrada.

## Project Structure

- `ML1_Project/`
  - `datasets/` - Contains the datasets used in the project.
    - `botwiki-2019/` - Data related to bot accounts from 2019.
      - `botwiki-2019.tsv` - Bot account identifiers.
      - `botwiki-2019_tweets.json` - Additional bot account information.
    - `verified-2019/` - Data related to human-verified accounts from 2019.
      - `verified-2019.tsv` - Human account identifiers.
      - `verified-2019_tweets.json` - Additional human account information.
    - `datasets_desc` - Descriptions of the datasets used.
  - `DecisionTreeClassifier_gridsearch.sav` - The saved model from GridSearch.
  - `requirements.txt` - Required libraries and their versions.
- `report/` - Contains the LaTeX report files.
  - `Final_project_am1_ADHG - ALME.zip` - LaTeX source files.
  - `Final_project_am1_ADHG___ALME.pdf` - Compiled PDF report.
- `App.ipynb` - Jupyter notebook for the graphical interface application.
- `ML1_Final_project.ipynb` - Main project notebook with data processing, model training, evaluation, and results.

## Getting Started

To run the notebooks and scripts in this repository, you will need to install the required Python libraries listed in `requirements.txt`. This can be done by running the Google Colab notebooks or using the following command:

```sh
pip install -r requirements.txt
```

## Models
We've saved the Decision Tree classifier with GridSearch (DecisionTreeClassifier_gridsearch.sav) which proved to be the most effective model during our experiments.

## Interface
The App.ipynb notebook provides a Gradio-based graphical interface that allows for easy interaction with the predictive model. Users can input raw data, and the app will return a prediction of whether the account is a bot or not.

## Reports
For an in-depth understanding of the project, methodology, and results, please refer to the report/ folder, where you can find the LaTeX report source files as well as the compiled PDF document.

## Contributions
Contributions, issues, and feature requests are welcome. Feel free to check  [issues page](https://github.com/adrianaleticiamartinez/MCD/issues). if you want to contribute.

## Authors
- David Arturo Hernández Gómez
- Adriana Leticia Martínez Estrada

