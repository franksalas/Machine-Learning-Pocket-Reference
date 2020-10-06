# Machine Learning Pocket Reference

[![book image](https://images-na.ssl-images-amazon.com/images/I/418be-msEJL._SX302_BO1,204,203,200_.jpg)](https://amzn.to/3jC9HCz)


## Description
Book overview of each chapter with code.

## Setup environment
Create enviroment from file
```bash
conda env create -f environments/base_environment.yml
```
## Activate environment

```bash
conda activate ml-pr
```

## Update environment

```bash
$ conda env update --prefix ./env --file environment.yml  --prune

pip freeze > requirements.txt
```
## Folder Structure
```
.
├── data
│   ├── final
│   ├── interim
│   └── raw
├── environments
│   ├── base_environment.yml
│   └── README.md
├── notebooks
│   └── EXAMPLES.ipynb
├── notes
├── README.md
├── report
│   └── graphs
└── src
    └── start.py

```