# Data

- https://download.inep.gov.br/microdados/microdados_enade_2019_LGPD.zip

# Settings

- Ubuntu 22.04 LTs

- Python 3.10.4

- virtualenv 20.13.0+ds from /usr/lib/python3/dist-packages/virtualenv/__init__.py

- pip 22.0.2 from /usr/lib/python3/dist-packages/pip (python 3.10)

# Setup

```zsh
git clone git@github.com:alex-repo-alves/Microdados-Enade.git

git checkout data_analysis

virtualenv -p python3 venv

source venv/bin/activate

pip install -r requirements

jupyter-lab
```

- After popup the jupyter-lab, open up the <code>data_analysis.ipynb</code> file

- After open up the file, execute each cell in the order they appear