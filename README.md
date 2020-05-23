# Introduction

In the predictive analysis discipline we aim to develop statistical models, based on data, for a particular outcome of interest. From this model, we make sure that behavioral learning and past experiences have a model with good generalization.

In this project, we developed a set of tasks to go further in Predictive Analytics by exploring some Deep Learning techniques.

This website intends to present the work analysis for the *"Análise Preditiva Avançada"* class assignment.

```
Trabalho em grupo de 3 a 4 alunos envolvendo técnicas de aprendizado supervisionado 
de máquina com Deep learning.

Possíveis trabalhos:

- Classificação ou Previsão, Dados Numéricos ou Categóricos, Estilo de problema 
similar às Regressões Logística ou Linear;
- Principalmente no caso de processamento de texto em linguagem natural;
- Classificação de imagens com Redes Convolutivas;
- Previsão de Texto com Redes Sequenciais;
- Geração de conteúdo (música por exemplo) com redes Auto-Generativas;
-  Mix de estilos artísticos com Redes Convolutivas / Auto-Generativas.

Material a ser entregue:

Se fizer em Python (recomendado): Jupyter Notebook com base e resultados (no caso de 
dados não submetidos à confidencialidade) ou apenas o Jupyter Notebook (com algumas 
referências de dados que possam "validar" o modelo de rede neural entregue).

Se fizer em R: Entregar a base de dados e o Rmarkdown. As bibliotecas de machine 
learning mais utilizadas (scikit-learn, tensorflow e keras) estão disponíveis também 
no R, porém com um print-end. É necessário instalar o Python para executalas.
```
:link: See the final website report in Rodrigo Gonçalves' Kaggle profile at: [https://www.kaggle.com/rodrigonca/advanced-predictive-analysis-cnn-implementation](https://www.kaggle.com/rodrigonca/advanced-predictive-analysis-cnn-implementation).

:octocat: Alternatively, run a binder container: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ldaniel/Advanced-Predictive-Analytics/master?filepath=notebooks%2Ffgv_assignment%2Fadvanced-predictive-analysis-cnn-implementation.ipynb)

## Professor
- Gustavo Mirapalheta

## Authors / Students
|Profile|Name|E-mail|
|---|---|---|
|<a href="https://github.com/DanielFCampos"><img src="https://avatars2.githubusercontent.com/u/31582602?s=460&v=4" title="DanielFCampos" width="80" height="80"></a>|Daniel Campos|[(daniel.ferraz.campos@gmail.com)](daniel.ferraz.campos@gmail.com)|
|<a href="https://github.com/ldaniel"><img src="https://avatars2.githubusercontent.com/u/205534?s=460&v=4" title="ldaniel" width="80" height="80"></a>|Leandro Daniel|[(contato@leandrodaniel.com)](contato@leandrodaniel.com)|
|<a href="https://github.com/RodriGonca"><img src="https://avatars2.githubusercontent.com/u/50252438?s=460&v=4" title="RodriGonca" width="80" height="80"></a>|Rodrigo Goncalves|[(rodrigo.goncalves@me.com)](rodrigo.goncalves@me.com)|
|<a href="https://github.com/ygorlima1"><img src="https://avatars2.githubusercontent.com/u/52429828?s=460&v=4" title="ygorlima1" width="80" height="80"></a>|Ygor Lima|[(ygor_redesocial@hotmail.com)](ygor_redesocial@hotmail.com)|

# Project Organization
------------

    ├── LICENSE
    ├── Makefile              <- Makefile with commands like `make data` or `make train`
    ├── README.md             <- The top-level README for developers using this project.
    ├── data
    │   ├── external          <- Data from third party sources.
    │   ├── interim           <- Intermediate data that has been transformed.
    │   ├── processed         <- The final, canonical data sets for modeling.
    │   └── raw               <- The original, immutable data dump.
    │
    ├── docs                  <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models                <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks             <- Jupyter notebooks. 
    │   └── external_examples <- Other interesting notebooks
    │   │
    │   └── fgv_assignment    <- The final class assignment given by Professor Mirapalheta
    │   │
    │   └── fgv_classes       <- All notebooks given by Professor Mirapalheta and Professor Hithoshi
    │                            in theirs respective classes
    │                            
    ├── references            <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports               <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures           <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt      <- The requirements file for reproducing the analysis environment, e.g.
    │                            generated with `pip freeze > requirements.txt`
    │
    ├── setup.py              <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                   <- Source code for use in this project.
    │   ├── __init__.py       <- Makes src a Python module
    │   │
    │   ├── data              <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── exercises         <- Scripts for FGV's class assignments
    │   │   └── __init__.py    
    │   │   └── playground.py
    │   │
    │   ├── features          <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models            <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization     <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini               <- tox file with settings for running tox; see tox.testrun.org


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
