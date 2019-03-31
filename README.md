This repository holds the (early stage) documentation for [DBHub.io](https://dbhub.io).

We're using this to try out [Bookdown](https://bookdown.org), as that should let us
generate documentation in several output formats, including HTML, PDF, and ePub.

To generate the HTML output, open the .Rproj file in the [RStudio IDE](https://www.rstudio.com/products/rstudio/),
then run this command in the RStudio console:

```
bookdown::render_book('index.Rmd', 'bookdown::gitbook')
```
