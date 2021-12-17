# Home-Credit-Default-Risk

Course project for Math 8670. Data from kaggle. 

## DATA

Folder used to store various datasets used in the project.

## Data Engineering

### build_month_default_count.ipynb

Consumes bureau_balance and bureau csvs and productes applicant_default_count.csv, which contains the total default count for applicants with a history in the bureau data.

### data_pipeline.ipynb

Consumes application_train.csv and applicant_default_count.csv and produces final_dataset.csv. This has code that removes unnecessary columns, creates new features, and imputes missing data.

## Data Exploration

### research.ipynb

Initial look at data. Produces sweetwiz report (report.html).

### clean_data_report.html

Sweetviz report for clean data. Created in data_pipeline.ipynb.

### mito_notebook.ipynb

Uses python mito library to generate a variety of visualizations.

### continuous_vs_target.ipynb

Contains various visualization describing relationship of continuous variables and default rate.

## Modeling

### weighted_random_forest.ipynb

Implementation of weighted random forest model.

### balanced_random_forest.ipynb

Implementation of balanced random forest model. Also contains model explanations.

### interpret_ml_model.ipynb

Implementation of explainable boosting machine. Also contains model explanations.

## Presentation

### project_presentation.ipynb

Notebook that was converted to the slides (project_presentation.slides.html) used in class presentation.

### project_report.ipynb

Notebook that was converted into the final report (project_report.html).