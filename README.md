# beem_data
Data sets for "Bayesian Methods for Ecological and Environmental Modelling" course

[Web site](https://nerc-ceh.github.io/beem/)

https://nerc-ceh.github.io/beem/

### Reading the data in R

Use the form below to read the files.

```
df <- read.csv(url("https://raw.githubusercontent.com/NERC-CEH/beem_data/main/trees.csv"))
```

Note that we need the `url` function, and we need to reference the raw content of the files (hence `raw.githubusercontent.com`), not the version displayed on the GitHub website.