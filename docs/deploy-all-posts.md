# Deploy all posts

### Create a virtual environment

    python3 -m venv nikola-env
    cd nikola-env

### Install nikola

    bin/python -m pip install -U pip setuptools wheel
    bin/python -m pip install -U "Nikola[extras]"

### Activate virtual environment

    source bin/activate

### Use nikola

    nikola
