
# try-r2eng

<!-- badges: start -->
[![Launch Rstudio Binder](http://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/matt-dray/try-r2eng/master?urlpath=rstudio)
<!-- badges: end -->

{r2eng} ([site](https://matt-dray.github.io/r2eng/), [source](https://github.com/matt-dray/r2eng)) is an in-development R package that takes an R package and returns an English translation.

Click the 'launch binder' badge to launch RStudio in your browser with {r2eng} installed, thanks to [the Binder project](https://mybinder.org/).

You can then run commands like:

``` r
r2eng::translate(x <- 1)
```

(Note that at time of writing there is a known bug in {r2eng} related to the 'say' system command.)

Feel free to [provide your thoughts or bug reports](https://github.com/matt-dray/r2eng/issues) as GitHub issues.
