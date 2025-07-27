# SGtraits: a living trait database for the Singapore flora

Welcome! `SGtraits` is a work-in-progress R package to interface with the 
functional trait database of the Singapore flora.

# Installation

`SGtraits` is still under development. To install the current version from 
GitHub:

```
# install.packages("remotes")
remotes::install_github("hrlai/SGtraits", dependencies = TRUE, upgrade = "ask")

# Load the package
library(SGtraits)
```

# Quick start

Currently, it is a wrapper around the `austraits` package, so you can find most
of the documentation and help from their 
[website](https://traitecoevo.github.io/austraits/).

The only function in `SGtraits` that differ from `austraits` is `load_database`,
which loads our database:

```
SGtraits <- load_database(version = "0.0.2", path = "data/SGtraits")
```

Once you have loaded our trait database, simply 
[follow the rest of the tutorial](https://traitecoevo.github.io/austraits/articles/austraits.html#descriptive-summaries-of-traits-and-taxa)
in `austraits` to explore the database.
