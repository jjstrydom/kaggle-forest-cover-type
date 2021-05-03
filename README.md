# README

## Python
Make sure your python version is 3.8.x 

## Package management
Uses pipenv.
1. Intall pipenv using pip install pipenv.
2. cd to the project directory.
3. run pipenv shell to create the virtual environment. 
See pipfile fore mode details on packages installed.

## Development in Jupyter
Uses jupyter notebooks for the Data Science process.
1. pipenv shell should have already installed the jupyter package.
2. Run jupyter with `jupyter notebook` within the pipenv shell.

## Dataset
From [kaggle Forest Cover Type Prediction](https://www.kaggle.com/c/forest-cover-type-prediction) competition.
- Use the `download_competition_files` notebook to download the files using the kaggle API.
- Make sure your kaggle API access has been setup.
- Browse to `https://www.kaggle.com/<your_username>/account` and click on `Create new API token`.
- Make sure you store the token in the correct place. 
- Running the `kaggle` command in the pipenv shell will tell you where the `kaggle.json` file is expected.
