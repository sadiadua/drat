## DMLC drat Repo

This [drat](http://dirk.eddelbuettel.com/code/drat.html) package repository provides R packages from DMLC code repositories.

The packages are updated weekly.

### Usage

```{.r}
# first add the repo
drat::addRepo("dmlc")
# either install just one or more given packages
install.packages("mxnet")     
# or update already installed packages
update.packages()
```

### License

Packages in this repository are available under their respective license.
