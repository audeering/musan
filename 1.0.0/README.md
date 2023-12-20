# Version 1.0.0

## Preparation

Create virtual environment and install dependencies:

```bash
$ virtualenv -p python3.10 venv
$ source venv/bin/activate
$ pip install -r requirements.txt.lock
```

If you have a different Python version,
you can try to install from `requirements.txt`.

## Publication

To publish the data run:

```bash
$ python download.py
$ python convert.py
$ python publish.py
```
