# Project-template

This template is a system of files and folders to use for data science projects for consistency and ease of use! Project repository structure informed and inspired by [towards data science](https://towardsdatascience.com/manage-your-data-science-project-structure-in-early-stage-95f91d4d0600), [cookiecutter](https://drivendata.github.io/cookiecutter-data-science/#directory-structure), [Noble](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1000424), and [outlierbio](https://github.com/outlierbio/ob-project-template)

This repository template has logical thematic organization at top levels, with the idea that lower levels have a date or version based organization for files. Ideally dated files would have a short explanation of contents as well as date.

### Directories and files:

* notebook.Rmd - main notebook for project containing reproducible analyses and figure output
* raw - untouched raw data 
* data - processed/cleaned data to be used for analysis
* results - output from analyses
* src - source code (project-wide code you use again and again)
* test - store sample data sets or scripts for testing
* notebooks - supplementary notebooks or work in progress notebooks containing immature code
  + exploration - data exploration/exploratory analysis
  + analysis
  + model - notebooks for creating, testing, evaluating models
* reports - polished PDF notebooks, manuscripts
  + figures - figures for presentations and publication
* references - explanatory materials like literature articles, pdfs, slides, data dictionaries, anything that gives background and context
* requirements.txt - The requirements file for reproducing the analysis environment, e.g. generated with "pip freeze > requirements.txt"



### Clone this repository to start a new project!
