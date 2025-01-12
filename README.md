# local-chatgpt-python

Local ChatGPT LLM using python and openAPI

# Prerequisites

## Install Ollama

https://ollama.com/

### Test ollama

```bash
$ ollama run llama3.2
>>> Teach me how to run a small business
...
Use Ctrl + d or /bye to exit.
>>> /bye
```

# Required setup

## Option 1 : Conda Approach

#### Install Conda

https://docs.conda.io/projects/conda/en/stable/user-guide/install/index.html

#### Create a Conda env

```bash
$ conda env create -f environment.yml
```

#### Activate the Conda environment

```bash
$ conda activate llms
```

## Option 2 : Virtual environment with python

#### Create a virtual environment

```bash
$ python -m venv .venv
$ source .venv/bin/activate
$ pip install -r requirements.txt
```

# Run a data science environment with jupyter lab

```bash
$ jupyter lab
```
