## Resubmission

This is a resubmission of a package that was archived on CRAN on 2024-06-16.

In this version I have:

* Removed the dependency on the 'DataCombine' package, which has since been
  archived on CRAN. The single function used from it (`slide()`) is now
  implemented internally in base R, so the package no longer imports any
  archived packages.
* Fixed the over-width example line in the `ema.powercurve()` documentation
  (which also referenced a non-existent `COL.3` argument).
* Repaired internal bugs in `eventmerge()`.

## Test environments

* local macOS install, R 4.x
* win-builder (devel and release)

## R CMD check results

There were no ERRORs or WARNINGs.

There were no NOTEs other than the standard "New submission / Package was
archived on CRAN" note for a resubmission.
