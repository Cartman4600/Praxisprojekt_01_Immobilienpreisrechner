python -m venv repc_env

.\repc_env\Scripts\Activate.ps1

python -m pip install -r requirements.txt

py -m run_repc.py

py -m pyinstaller run_repc.spec