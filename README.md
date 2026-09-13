# Electronic Notebook: Statistical Modelling of Extreme Values, Lab Assignment

This GitHub repository was created to practice reproducible workflows and the FAIR principles. The R workflow demonstrates extreme value analysis using the `extRemes` package. 

## What this does

It fits Generalized Extreme Value (GEV) models to winter maximum temperature data (Port Jervis, NY, 1927-1995), with and without a climate covariate (the Arctic Oscillation index) in the location and scale parameters. It compares nested models with likelihood-ratio tests and computes the covariate-dependent return levels. Next, a threshold is selected for peaks-over-threshold analysis of US hurricane damages (1926-1995) using threshold-stability and mean-residual-life diagnostics. Finally, a Generalized Pareto (GP) distribution to the exceedances is fitted. 

Both datasets (`PORTw` and `damage`) are bundled with the `extRemes` package itself, so no external data download is required.

## Requirements

- R runtime. 
- `extRemes` (pinned to version 2.2-1).
- `remotes` (used to install the pinned version of `extRemes`).

## How to run

### Option A: Google Colab (recommended, no local setup)

1. Click the "Open in Colab". 
2. Set `Runtime > Change runtime type > R`.
3. `Runtime > Run all`.

### Option B: Local Jupyter with an R kernel

``` bash
install.packages("remotes")
remotes::install_version("extRemes", version = "2.2-1")
install.packages("IRkernel")
IRkernel::installspec()
```

Then open `BERN02_Ex3.ipynb` in Jupyter and run all cells.

## Repository contents

- `BERN02_Ex3.ipynb`: The analysis notebook (R code, figures, FAIR discussion).
- `LICENSE`: Project license.
- `README.md`: This is the file you're viewing right now.

## FAIR data principles

A full discussion of how this workflow relates to the FAIR (Findable, Accessible, Interoperable, Reusable) principles is included as the final section of the notebook itself. 

## Authors

Sek Huen Leung, Kadri Kalamäe
- The code was written by Kadri Kalamäe.
- The repository and the discussion of the FAIR principles were developed collaboratively by Kadri Kalamäe and Sek Huen Leung.



