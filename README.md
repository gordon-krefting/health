# Health

Some utils to help monitor my own health.

## First time python setup
Assuming python and virtualenv are already installed
```bash
virtualenv venv
source venv/bin/activate
python3 -m pip install -U jupyter matplotlib numpy pandas scipy scikit-learn xlrd
```
To check installation, run this (should be silent):
```bash
python3 -c "import jupyter, matplotlib, numpy, pandas, scipy, sklearn
```

## To run the jupyter notebooks
```bash
source venv/bin/activate
jupyter notebook
```
