# pytorch_notebook
Private notebook for pytorch tips

[Notebok Viewer][https://nbviewer.jupyter.org/github/ugo-nama-kun/pytorch_notebook/tree/master/]

## Settings

### pyenv-pipenv
https://qiita.com/y-tsutsu/items/54c10e0b2c6b565c887a

pipenv manages python packages. The installation is executed by script below
```bash
pip install pipenv
```

The script below opens the jupyter notebook.
```bash
pipenv run start
```

We can add new script in [scripts] of Pipfile.

### Installing pytorch
https://pytorch.org/

```bash
pipenv install torch torchvision
```

### Running pipenv environment in jupyter notebook
https://qiita.com/mzn/items/99d769d0ad9d03a5d73e
1. Install ipykernel and jupyter
2. Run scripts below
```bash
$ pipenv shell
$ python -m ipykernel install --user --name=<name you like>
```
