# org <a href="https://www.csids.no/org/"><img src="man/figures/logo.png" align="right" width="120" /></a>


## Overview 

[org](https://www.csids.no/org/) is framework to help you organize projects.

Most analyses have three (or more) main sections: code, results, and data, each with different requirements (version control/sharing/encryption). You provide folder locations and 'org' helps you take care of the details.

Read the introduction vignette [here](https://www.csids.no/org/articles/org.html) or run `help(package="org")`.

## csverse

The [csverse](https://www.csids.no/packages.html) is a set of R packages developed to help solve problems that frequently occur when performing disease surveillance.

If you want to install the dev versions (or access packages that haven't been released on CRAN), run `usethis::edit_r_profile()` to edit your `.Rprofile`. 

Then write in:

```
options(
  repos = structure(c(
    CSVERSE = "https://www.csids.no/drat/",
    CRAN    = "https://cran.rstudio.com"
  ))
)
```

Save the file and restart R.

You can now install [csverse](https://www.csids.no/packages.html) packages from our [drat repository](https://www.csids.no/drat/).

```
install.packages("org")
```

