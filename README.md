# Electronic Notebook: Statistical modelling of extreme values Lab Assignment

This GitHub repository was created to practice reproducible workflows and the FAIR principles.

The code was written by Kadri Kalamäe.

The repository and the discussion of the FAIR principles were developed collaboratively by Kadri Kalamäe and Sek Huen Leung.
## Layout

Description of the directory layout.

- `README.md` This is the file you're viewing right now.
- `environment.yml` Defines the required Python packages using conda. Try to pin to specific major versions of your
  dependencies as their behavior may change in the future.
  The environment is currently called `my_environment` and you'll likely want to rename it to something less generic.

## Requirements

To run the Notebooks online, click on the _Launch Binder_ badge above. Alternatively, to run on your own computer,
install Python using _e.g._ [Miniforge](https://github.com/conda-forge/miniforge) or [Anaconda](https://docs.conda.io)
and make sure all required packages are loaded by issuing the following terminal commands

``` bash
conda env create -f environment.yml
source activate my_environment
jupyter-lab
```
