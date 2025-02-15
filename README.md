# startmrca
This package implements a hidden Markov model to estimate the time at which a beneficial
allele begins increasing in frequency. More specifically, we assume a "star" genealogy 
among carriers of the benefical allele to estimate time to the most recent common ancestor
(TMRCA). See [Smith et al. (2018)](https://doi.org/10.1093/molbev/msy006) 
for details of the model.

## Setup
In R, install the latest version of the package using these commands:
    
   ```R
   library(devtools)
   install_github("jhavsmith/startmrca")
   library(startmrca)
   ```

## Usage
After installing the package, usage options and an example are available 
by typing:

   ```R
   help(run.startmrca)
   ```

