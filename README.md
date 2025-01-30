# crypto-price-tracker
These notes contain a concise list of the terminal commands used while creating a data science app 
## Create project folder
```bash
mkdir folder_name
```

## Change current working directory
```bash
cd folder_name
```

## Run Streamlit App
```bash
streamlit run appname.py --server.port 8888 --browser.serverAddress [server address]
```

## Virtual Environment

### Create virtual environment in working directory using python3
```bash
pipenv --python 3
```

### Activate virtual environment
```bash
pipenv shell
```

### Deactivate virtual environment
```bash
deactivate
```

### To see list of installed packages in virtual environment
```bash
pipenv run pip freeze
```

### To see the version of an installed package in virtual environment
```bash
pipenv run pip freeze | grep package_name
```

### To see path of virtual environment
```bash
pipenv --venv
```

