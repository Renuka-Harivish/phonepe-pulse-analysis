# Python environment for pulse-master

This project uses a virtual environment named `.venv`.

Windows (PowerShell) - create and activate:

```powershell
python -m venv .venv
.venv\Scripts\Activate.ps1
```

Install dependencies:

```powershell
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
```

Register notebook kernel (optional):

```powershell
python -m ipykernel install --user --name pulse-env --display-name "Python (pulse-env)"
```

After activation, open `project1.ipynb` with Jupyter or VS Code and select the `Python (pulse-env)` kernel.
