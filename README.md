# Jam Buddy

## Conda environment

1. Create new conda environment. Alternatively, just use Pycharm interpreter settings to create conda environment (easier)
```
conda env create --name jam-buddy python=3.10
```
2. Add packages to conda
```
conda install -c conda-forge python-sounddevice numpy
```
3. Set up jupyter for conda environment ([sauce](https://stackoverflow.com/questions/39604271/conda-environments-not-showing-up-in-jupyter-notebook))

```
pip install jupyter ipykernel
```
```
python -m ipykernel install --user --name jam-buddy --display-name "jam-buddy"
```