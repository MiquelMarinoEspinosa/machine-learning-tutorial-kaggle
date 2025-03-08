# machine-learning-tutorial-kaggle
Kaggle tutorial with jupyter environment

Based on

* [Kaggle tutorials](https://www.kaggle.com/learn)
* [Data science with JupyterLab](https://docs.docker.com/guides/jupyter/)

Access to the jupyter via http://localhost:8889/lab?token=my-token

Related [jupyter docker hub image](https://hub.docker.com/repository/docker/miquelmarinoespinosa/jupyter-python-machine-learning/general)

Add datasets at the `input` folder to be able to execute the notebook according to the define path at the different notebook. The datasets can be found at [kaggle datasets](https://www.kaggle.com/datasets)

Example of path definition

```
data = pd.read_csv('../../input/melbourne_housing_snapshot/melb_data.csv')
```
