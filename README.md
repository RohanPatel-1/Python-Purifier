# Json Language Server

## Install Server Dependencies

1. `python -m venv env`
1. `python -m pip install -e .` from root directory
1. Create `.vscode/settings.json` file and set `python.pythonPath` to point to your python environment where `pygls` is installed

## Activate Virtual Enviroment

1. `.env/Scripts/activate` for Windows

## Install Server Dependencies

1. `pip install pygls`
1. `pip install git+https://github.com/James-Ansley/qchecker@dev-0.0.0a4`

## Install Client Dependencies

Open terminal and execute following commands:

1. `npm install`
1. `cd client/ && npm install`

## Run Example

1. Open this directory in VS Code
1. Open debug view (`ctrl + shift + D`)
1. Select `Server + Client` and press `F5`
