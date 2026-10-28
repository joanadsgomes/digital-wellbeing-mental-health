# Digital Wellbeing and Mental Health Analysis

Academic Python project developed by two students. The project explores associations between digital device use, digital dependence and indicators of psychological wellbeing, and applies logistic regression to classify a high-risk indicator in the dataset.

## Project objectives
- Describe the dataset and explore numerical variables.
- Analyze outliers and correlations between digital use and wellbeing indicators.
- Visualize device use patterns across groups.
- Explore associations with stress, daily role, phone unlocks and notifications.
- Train and evaluate a logistic regression classifier for `high_risk_flag`.

## Notebooks — read in this order
1. [`01_introducao_exploracao.ipynb`](01_introducao_exploracao.ipynb) — Introduction, dataset description, descriptive statistics, outlier boxplots and correlation clustermap.
2. [`02_padroes_uso_digital.ipynb`](02_padroes_uso_digital.ipynb) — Screen-time density, digital dependence by region and gender, and screen time by device type.
3. [`03_habitos_e_bem_estar.ipynb`](03_habitos_e_bem_estar.ipynb) — Screen time versus stress, daily role distributions, and phone unlocks versus notifications.
4. [`04_regressao_logistica_conclusoes.ipynb`](04_regressao_logistica_conclusoes.ipynb) — Logistic regression, model evaluation, confusion matrix, predicted probabilities and conclusions.

The original analysis and its written interpretations were preserved across the four notebooks. The logistic-regression section was reordered so the model runs before its confusion matrix is calculated.

## Technologies
Python, Jupyter Notebook, pandas, Matplotlib, Seaborn, scikit-learn.

## Data
The notebooks read `data/dataset_prog.csv`, a semicolon-delimited CSV file containing 3,500 records and 24 variables. The dataset is included for local preparation, but **confirm that its licence permits public redistribution before uploading it to a public GitHub repository**. Add the original dataset source, licence and attribution here. If redistribution is not permitted, omit the CSV from the public repository and provide instructions for obtaining it from its official source.

## Run locally
1. Download or clone this repository.
2. Ensure the authorized dataset is saved as `data/dataset_prog.csv` (semicolon-separated).
3. Install dependencies with `pip install -r requirements.txt`.
4. Launch Jupyter from the repository's root folder and open the notebooks in numbered order. Each notebook can run independently from this folder.

## Interpretation and limitations
The visualizations describe associations, not causal relationships. The classifier predicts a dataset-defined flag and must not be interpreted as a clinical diagnosis. Accuracy alone is insufficient to evaluate the detection of high-risk cases; review precision, recall and the confusion matrix. Performance estimates can vary when the data or modeling choices change.

## Authors
- [Student 1 — add name and GitHub profile]
- [Student 2 — add name and GitHub profile]

*Academic project. Confirm dataset redistribution permission and add the source and attribution before publishing.*
