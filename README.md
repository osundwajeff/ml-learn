# ml-learn
Overview of Machine Learning.

## Environment set up

Install miniconda/conda.

Create new conda env:

```bash
conda create -n ml-learn python
```

Activate env:

```bash
conda activate ml-learn
```

Install necessary packages:

```bash
conda install numpy pandas scikit-learn seaborn jupyter
```

Or use:

```bash
pip install -r requirements.txt
```

System link env to project root (Good for Zed IDE):

```bash
ln -s ~/.conda/envs/ml-learn .venv
```

For updating `requirements.txt`:

```bash
pip list --format=freeze > requirements.txt
```
