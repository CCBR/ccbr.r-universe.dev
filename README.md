# CCBR R Universe

[![name status badge](https://ccbr.r-universe.dev/badges/:name)](https://ccbr.r-universe.dev/)
[![registry status badge](https://ccbr.r-universe.dev/badges/:registry)](https://ccbr.r-universe.dev/)
[![packages status badge](https://ccbr.r-universe.dev/badges/:packages)](https://ccbr.r-universe.dev/packages)

<https://ccbr.r-universe.dev>


```r
# Enable this universe
options(repos = c(
    CCBR = 'https://ccbr.r-universe.dev',
    CRAN = 'https://cloud.r-project.org',
    BIOC = 'https://bioc.r-universe.dev/'))

# Install packages
install.packages('MOSuite')
```