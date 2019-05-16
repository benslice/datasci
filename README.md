# Data Science Project Template
This repo holds a template data science project

## Installation Instructions

```bash

# 1. Clone this repository
    git clone git@github.com:<USERNAME>/datasci <NEWPROJ>
    # or clone with -b <BRANCH> if you have more then one template

# 2. We will have a new "origin", rename this to "upstream" 
    # so we can still pull updates to the template, disable push
    git remote rename origin upstream
    git remote set-url --push upstream no_push

# 3. Create a <NEWPROJ> repository on GitHub 

# 4. Set <NEWPROJ> as the origin and push the code
    git remote add origin git@github.com:<USERNAME>/<NEWPROJ>.git
    git push -u origin master
    

```

  
## Template Directory Structure

├── LICENSE  
├── Makefile           <- Makefile with commands like `make data` or `make train`  
├── README.md          <- The top-level README for developers using this project.  
├── data  
│   ├── external       <- Data from third party sources.  
│   ├── interim        <- Intermediate data that has been transformed.  
│   ├── processed      <- The final, canonical data sets for modeling.  
│   ├── refdata        <- Data dictionaries  
│   └── raw            <- The original, immutable data dump.  
│  
├── docs               <- A default Sphinx project; see sphinx-doc.org for details  
│  
├── models             <- Trained and serialized models, model predictions, or model summaries  
│  
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),  
│                         the creator's initials, and a short `-` delimited description, e.g.  
│                         `1.0-jqp-initial-data-exploration`.  
│  
├── references         <- Articles, manuals, and all other explanatory materials.  
│  
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.  
│   └── figures        <- Generated graphics and figures to be used in reporting  
│  
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.  
│                         generated with `pip freeze > requirements.txt`  
│  
├── setup.py           <- Make this project pip installable with `pip install -e`  
├── src                <- Source code for use in this project.  
│   ├── __init__.py    <- Makes src a Python module  
│   │  
│   ├── data           <- Scripts to download or generate data  
│   │   └── make_dataset.py  
│   │  
│   ├── features       <- Scripts to turn raw data into features for modeling  
│   │   └── build_features.py  
│   │  
│   ├── models         <- Scripts to train models and then use trained models to make  
│   │   │                 predictions  
│   │   ├── predict_model.py  
│   │   └── train_model.py  
│   │  
│   └── visualization  <- Scripts to create exploratory and results oriented visualizations  
│       └── visualize.py  
│  
└── venv               <- directory to hold the virtualenv  


## Sources
https://www.kdnuggets.com/2018/07/cookiecutter-data-science-organize-data-project.html
https://medium.com/@smrgrace/having-a-git-repo-that-is-a-template-for-new-projects-148079b7f178
