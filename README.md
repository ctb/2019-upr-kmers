# 2019-upr-kmers

Click here: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ctb/2019-upr-kmers/master)

## To run this on your own laptop

If you a Mac or a Linux laptop with conda installed, you can try the following.

Set up bioconda:
```
conda config --add channels defaults
conda config --add channels bioconda
conda config --add channels conda-forge
```

and now create and activate a conda environment with all the tools installed:

```
conda env create --file environment.yml -n smash
conda activate smash
conda install -y jupyter
```

You should now be able to run `jupyter notebook` and see the notebooks
in this directory!

