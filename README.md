# Coding and Collaboration using Git, GitHub and Pull Requests
Demonstration repository for the DATA2050: Coding + Collaboration using Git, GitHub and Pull Requests workshop.

## 🎯 Aim for the Workshop

We're going to collectively update files within this directory, which follows the [Cookiecutter Data Science](https://cookiecutter-data-science.drivendata.org) template, a standarized structure for collaborative
data science projects.

* The steps for the workshop are listed on [the workshop's web page](https://brownccv.notion.site/Collaboration-using-Git-GitHub-and-Pull-Requests-afdc0e8c48a449f2864f0e3e8b5b4a59).

* [Project Structure](https://docs.google.com/presentation/d/1VUG0ursutuPETHqoLLIaIq1CuxLEENHGYqSbnUJ6Npw/edit?usp=sharing): Slides on project structure best practices. 

### 🗂️ Cookiecutter Data Science Project Structure
```
├── LICENSE            <- Open-source license if one is chosen
├── Makefile           <- Makefile with convenience commands like `make data` or `make train`
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- A default mkdocs project; see www.mkdocs.org for details
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── pyproject.toml     <- Project configuration file with package metadata for 
│                         data2050 and configuration for tools like black
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
├── setup.cfg          <- Configuration file for flake8
│
└── data2050   <- Source code for use in this project.
    │
    ├── __init__.py             <- Makes data2050 a Python module
    │
    ├── config.py               <- Store useful variables and configuration
    │
    ├── dataset.py              <- Scripts to download or generate data
    │
    ├── features.py             <- Code to create features for modeling
    │
    ├── modeling                
    │   ├── __init__.py 
    │   ├── predict.py          <- Code to run model inference with trained models          
    │   └── train.py            <- Code to train models
    │
    └── plots.py                <- Code to create visualizations
```

--------
