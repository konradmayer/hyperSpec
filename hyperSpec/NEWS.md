# hyperSpec 1.0.0 2020-xx-xx

## Acknowledgements

* The `hyperSpec` team gratefully acknowledges support from the Google Summer of Code program, which sponsored student Erick Oduniyi during summer 2020. Erick and the team carried out a significant overhaul of `hyperSpec` which led to this major release.


## User-Facing Changes from 0.99 Series

* `NEWS.md` (this file) added so that users can readily see changes that may affect the use of the package.
* Documentation now available in `pkgdown` sites (https://r-hyperspec.github.io/).
* Introductory vignette reorganized and enhanced, thanks to Bryan Hanson.
* Portions of `hyperSpec` were spun out into their own packages for ease of maintenance.  ELABORATE
* Dataset `faux_cell` and function `generate_faux_cell` replace `chondro` dataset (#125, #156, #180, #229).
* Dataset `chondro` was moved to package **hySpc.chondro** (https://r-hyperspec.github.io/hySpc.chondro/).
* Function `spc.NA.linapprox()`, which was deprecated for long time, is now completely removed (#239).
* Column names in spectra matrix (`$spc` column of `hyperSpec` object) are now returned correctly by functions `spc.bin()` (#237), and `spc.loess()` (#245).
* Functions `show()`, `print()`, `summary()` gives different default output now (@GegznaV, #211).


## Non-User-Facing Changes from 0.99 Series

* Note: this listing is for the benefit of developers, and should summarize significant infrastructure changes.
* Vignettes converted to `.Rmd` and formatted consistently, thanks to Vilmantas Gegzna.