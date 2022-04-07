# Steps to set up

py -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
ipython kernel install --name "local-venv" --user
jupyter notebook