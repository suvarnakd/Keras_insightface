


Steps

1. Installations 

```
pyenv install 3.8.5
pyenv virtualenv 3.8.5 insightface_env
pyenv activate insightface_env
```

2. Install packages

```
pip install --upgrade pip
pip install pip-tools tf-nightly tfa-nightly
pip install tensorflow  glob2 pandas tqdm scikit-image scikit-learn ipython
```