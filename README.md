# Sample Python Dependabot

This repository is a minimal Python project created to test and demonstrate GitHub Actions and Dependabot.  
It's designed for experimenting with automated dependency updates, workflow triggers, and continuous integration setups.


## Overview

The project contains a simple Python script (`main.py`) that prints a message to verify the setup.  
It includes standard configuration files for Git, dependencies, and GitHub automation.


## Features

- Demonstrates Dependabot dependency updates  
- Example of GitHub Actions workflow structure  
- Includes Python-specific `.gitignore` and `.gitattributes`  
- Simple runnable Python script (`main.py`)  
- Ready-to-use dependency list in `requirements.txt`


## Project Structure

```

sample-python-dependabot/
│
├── .github/               # GitHub workflows and issue templates
├── .gitattributes         # Line ending and linguist configuration
├── .gitignore             # Python and editor ignores
├── main.py                # Entry-point Python script
└── requirements.txt       # Project dependencies

````


## Installation

### 1. Clone the repository
```bash
git clone https://github.com/lukas-hempel-bp/sample-python-dependabot.git
cd sample-python-dependabot
````

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the script

```bash
python main.py
```

Expected output:

```
Hello, this is an enourmous test of Dependabot and GitHub Actions
```


## How It Works

* **Dependabot** checks `requirements.txt` for outdated dependencies and automatically opens pull requests with updates.
* **GitHub Actions** can be configured to run tests, lint checks, or deployment workflows on every push or pull request.
* The `.github` directory includes templates for issues and workflows to support CI/CD automation.


## Requirements

* Python 3.8 or later
* pip (Python package manager)
