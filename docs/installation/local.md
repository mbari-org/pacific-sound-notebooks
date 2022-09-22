Notebooks can be run on your computer locally. [**Python>=3.6.0**](https://www.python.org/)
### Install in your computer

[**Python>=3.6.0**](https://www.python.org/) is required with the 
[requirements.txt](https://github.com/mbari-org/pacific-sound-notebooks/blob/master/requirements.txt).
 
The recommended way to run the notebooks is using the [Anaconda](https://www.anaconda.com/) environment

```bash
git clone https://github.com/mbari-org/pacific-sound-notebooks
cd pacific-sound-notebooks
```

If using a Mac 
```
brew install sox
```

If using Linux
```
apt-get install libsox-fmt-all libsox-dev
```

```
conda env create 
conda activate pacific-sound-notebooks
pip install ipykernel
python -m ipykernel install --user --name=pacific-sound-notebooks
jupyter notebook
```