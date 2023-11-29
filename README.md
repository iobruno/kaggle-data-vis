# Kaggle Data Visualization

![Python](https://img.shields.io/badge/Python-3.10_|_3.11-4B8BBE.svg?style=flat&logo=python&logoColor=FFD43B&labelColor=306998)
![Pandas](https://img.shields.io/badge/pandas-2.x-E70288?style=flat&logo=pandas&logoColor=white&labelColor=130753)
![Jupyter](https://img.shields.io/badge/Jupyter-31393F.svg?style=flat&logo=jupyter&logoColor=F37726&labelColor=31393F)
[![Ruff](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/astral-sh/ruff/main/assets/badge/v2.json)](https://github.com/astral-sh/ruff)

![License](https://img.shields.io/badge/license-CC--BY--SA--4.0-31393F?style=flat&logo=creativecommons&logoColor=black&labelColor=white)

Kaggle - Learn Data Visualization

## Tech Stack
- [pandas](https://pandas.pydata.org/docs/user_guide/)
- [plotly](https://plotly.com/python/)
- [seaborn](https://seaborn.pydata.org/)
- [PDM](https://pdm-project.org/latest/usage/dependency/)
- [Ruff](https://docs.astral.sh/ruff/configuration/)


## Up & Running

**Create a virtualenv for Python 3.10 / 3.11**
```shell
conda create -n datavis python=3.11
conda activate datavis
```

**Install project dependencies**
```shell
pdm sync
```

## TODO

- [x] PEP-517: Packaging and dependency management with PDM
- [x] Implement basic visualizations with seaborn in Jupyter
- [ ] Implement the visualizations done with seaborn using Plotly
- [ ] Optimize COVID19 EDA Visualizations
- [ ] Implement visualization with Streamlit and Plotly