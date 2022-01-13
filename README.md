# org <img src="man/figures/logo.png" align="right" width="120" />

[org](https://docs.sykdomspulsen.no/org) is a system to help you organize projects. Most analyses have three (or more) main sections: code, results, and data, each with different requirements (version control/sharing/encryption). You provide folder locations and 'org' helps you take care of the details.

Read the introduction vignette [here](http://docs.sykdomspulsen.no/org/articles/intro.html) or run `help(package="org")`.

## splverse

<a href="https://docs.sykdomspulsen.no/packages"><img src="https://docs.sykdomspulsen.no/packages/splverse.png" style="width:200px;"></a>

The [splverse](https://docs.sykdomspulsen.no/packages) is a set of R packages developed to help solve problems that frequently occur when performing infectious disease surveillance.

If you want to install the dev versions (or access packages that haven't been released on CRAN), run `usethis::edit_r_profile()` to edit your `.Rprofile`. Then write in:

```
options(
  repos = structure(c(
    FHI  = "https://folkehelseinstituttet.github.io/drat/",
    CRAN = "https://cran.rstudio.com"
  ))
)
```

Save the file and restart R. This will allow you to install splverse packages from the FHI registry.
