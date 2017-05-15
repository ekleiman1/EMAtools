## Test environments
* local OS X install, R 3.3.2 ("Sincere Pumpkin Patch")
* local OS X install, R 3.4.0 ("You Stupid Darkness")
* win-builder (devel and release)

## R CMD check results
There were no ERRORs or WARNINGs.

There was 1 NOTE:

* checking R code for possible problems ... NOTE
eventmerge: no visible binding for global variable ‘respondent_id’
eventmerge: no visible binding for global variable ‘survey_id’
eventmerge: no visible binding for global variable ‘timezone_offset’
eventmerge: no visible binding for global variable ‘timestamp_event’
Undefined global functions or variables:
  respondent_id survey_id timestamp_event timezone_offset

These are all default column labels that will be in the dataframe that users export from the MobileEMA (mEMA) backend.

EMA and ESM are spelled correctly (they're acroynms)
