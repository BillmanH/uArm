# Using the ARM in Notebooks
I prefer to use Anaconda for managing my python libraries. 

## Setting up the environment
Replicate the environment with the yaml file:
```
conda env create -f env.yaml
```

Once you have the uarm environment, open the notebooks with:
```
python -m ipykernel install --name uarm --display-name "Python (uArm)"
conda activate uarm
jupyter lab
```
