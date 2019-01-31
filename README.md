# d18oc_sst

This is a companion to Malevich, Steven B, Lael Vetter, and Jessica E. Tierney, (2019). "Global core top calibration of d18O in planktic foraminifera to sea-surface temperature". Submitted to "Paleoceanography and Paleoclimatology".

This repository contains code walking through the four Bayesian regression coretop calibration models. This is in the notebook in [./notebooks/bayesian_calibration_examples.ipynb](https://github.com/brews/d18oc_sst/blob/master/notebooks/bayesian_calibration_examples.ipynb). You should be able to view this notebook online.

## Data

Data used for the examples is in [./data/parsed/](https://github.com/brews/d18oc_sst/blob/master/data/parsed/). These are simple CSV files. This data is also in the Supplemental Information of Malevich et al. 2019.

## Running the notebook locally

If you would like to run the examples, I've included [environment.yml](https://github.com/brews/d18oc_sst/blob/master/environment.yml). This lists the package requirements to create a virtual environment in [Anaconda](https://www.anaconda.com/)/[conda](https://docs.conda.io/projects/conda/en/latest/).

Assuming you have `conda` installed and configured, you can create the environment with:

```bash
conda env create -f environment.yml
```

and follow the prompts. With the environment created, activate the new environment. You can now start a Jupyter notebook server for your Desktop computer with:

```bash
jupyter notebook
```

This should launch a web browser allowing you to navigate to Jupyter notebook in ./notebooks/.

Thank you very much for your interest!
