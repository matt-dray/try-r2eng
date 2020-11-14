
# try-r2eng

<!-- badges: start -->
[![Launch Rstudio Binder](http://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/matt-dray/try-r2eng/master?urlpath=rstudio)
[![rostrum.blog post](https://img.shields.io/badge/rostrum.blog-post-008900?style=flat&labelColor=black&logo=data:image/gif;base64,R0lGODlhEAAQAPEAAAAAABWCBAAAAAAAACH5BAlkAAIAIf8LTkVUU0NBUEUyLjADAQAAACwAAAAAEAAQAAAC55QkISIiEoQQQgghRBBCiCAIgiAIgiAIQiAIgSAIgiAIQiAIgRAEQiAQBAQCgUAQEAQEgYAgIAgIBAKBQBAQCAKBQEAgCAgEAoFAIAgEBAKBIBAQCAQCgUAgEAgCgUBAICAgICAgIBAgEBAgEBAgEBAgECAgICAgECAQIBAQIBAgECAgICAgICAgECAQECAQICAgICAgICAgEBAgEBAgEBAgICAgICAgECAQIBAQIBAgECAgICAgIBAgECAQECAQIBAgICAgIBAgIBAgEBAgECAgECAgICAgICAgECAgECAgQIAAAQIKAAAh+QQJZAACACwAAAAAEAAQAAAC55QkIiESIoQQQgghhAhCBCEIgiAIgiAIQiAIgSAIgiAIQiAIgRAEQiAQBAQCgUAQEAQEgYAgIAgIBAKBQBAQCAKBQEAgCAgEAoFAIAgEBAKBIBAQCAQCgUAgEAgCgUBAICAgICAgIBAgEBAgEBAgEBAgECAgICAgECAQIBAQIBAgECAgICAgICAgECAQECAQICAgICAgICAgEBAgEBAgEBAgICAgICAgECAQIBAQIBAgECAgICAgIBAgECAQECAQIBAgICAgIBAgIBAgEBAgECAgECAgICAgICAgECAgECAgQIAAAQIKAAA7)](https://www.rostrum.blog/2020/11/14/hello-r2eng/)
<!-- badges: end -->

The {r2eng} package for R is an in-development R package that takes an R expression and returns an English translation. To learn more, visit the [package site](https://matt-dray.github.io/r2eng/) or [source](https://github.com/matt-dray/r2eng) and [read the blogpost]().

Click the 'launch binder' badge to launch RStudio in your browser with {r2eng} and the tidyverse installed, thanks to [the Binder project](https://mybinder.org/).

You can then run commands like:

``` r
library(r2eng)
translate(x <- 1, speak = FALSE)
```

Note that you should set the 'speak' argument to `FALSE` because the Binder instance can't run the system call that's required to vocalise the expression.

Feel free to [provide your thoughts or bug reports](https://github.com/matt-dray/r2eng/issues) about the package.
