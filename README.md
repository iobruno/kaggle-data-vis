# Kaggle Data Visualization

![Python](https://img.shields.io/badge/Python-3.12_|_3.11_|_3.10-4B8BBE.svg?style=flat&logo=python&logoColor=FFD43B&labelColor=306998)
![Pandas](https://img.shields.io/badge/pandas-2.x-E70288?style=flat&logo=pandas&logoColor=white&labelColor=130753)
![Jupyter](https://img.shields.io/badge/Jupyter-31393F.svg?style=flat&logo=jupyter&logoColor=F37726&labelColor=31393F)

![License](https://img.shields.io/badge/license-CC--BY--SA--4.0-31393F?style=flat&logo=creativecommons&logoColor=black&labelColor=white)

Kaggle - Learn Data Visualization

## Tech Stack
- [pandas](https://pandas.pydata.org/docs/user_guide/)
- [plotly](https://plotly.com/python/)
- [seaborn](https://seaborn.pydata.org/)
- [PDM](https://pdm-project.org/latest/usage/dependency/)
- [Ruff](https://docs.astral.sh/ruff/configuration/)


## Up & Running

**1.** Create and activate a virtualenv with conda:
```shell
conda create -n datavis python=3.12
conda activate datavis
```

**2.** Install the dependencies on `pyproject.toml`:
```shell
pdm sync
```

**3.** Spin up jupyter for EDA and Data vis:
```shell
jupyter lab
```

## TODO

- [x] PEP-517: Packaging and dependency management with PDM
- [x] Implement basic visualizations with seaborn in Jupyter
- [ ] Implement the visualizations done with seaborn using Plotly
- [ ] Optimize COVID19 EDA Visualizations
- [ ] Implement visualization with Streamlit and Plotly