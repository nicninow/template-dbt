# Initialise

This workflow is tested and specified against Windows 10, PowerShell, VS Code, Python 3.8.8, dbt 19.0...

The commands below assume you are in the root directory for this repository and have Python location in your `PATH` variable. 

```
python -m venv .venv
python -m pip install -r requirements.txt
dbt init project_name
```

For the virtual Python environent, create a `.env` file and put your environment variables there. 

```
cd > .env
```
