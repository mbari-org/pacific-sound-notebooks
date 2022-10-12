Notebooks can be run on your computer locally. [**Python>=3.6.0**](https://www.python.org/)
### Install locally on your computer

### Requirements
[**Python>=3.6.0**](https://www.python.org/) is required with an [Anaconda](https://www.anaconda.com/) environment.

### Checkout the code 

```bash
git clone https://github.com/mbari-org/pacific-sound-notebooks
cd pacific-sound-notebooks
```

### Install the dependencies

If using a Mac 
```
brew install sox
```

If using Linux
```
apt-get install libsox-fmt-all libsox-dev
```

### Create the Anaconda environment

This will create an environment called pacific-sound-notebooks and make that available in your local jupyter notebook as the kernel named *pacific-sound-notebooks*
```
conda env create 
conda activate pacific-sound-notebooks
pip install ipykernel
python -m ipykernel install --user --name=pacific-sound-notebooks
```

### Launch the jupyter notebook

```
jupyter notebook
```