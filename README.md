Kiva Loan Analysis
=================================

These files present analysis and predictive modeling of loan repayment rates for the [Kiva loan data set](http://build.kiva.org/docs/data/snapshots), based on a snapshot taken at 2015-07-10 20:10:00 UTC. The initial parts are concerned with preprocessing and simple profiling, so readers with limited time may wish to skip ahead.

Running
-------

Each part of the analysis can be viewed online, thanks to RawGit.

* Summary and Highlights (coming soon)
* 07: The Single-Borrower Class (coming soon)
* 06: Tree and Forest Models (coming soon)
* 05: Repayment Rate: Linear Models
* 04: Goal Setting and Subsetting
* 03: Analysis in Two Variables
* 02: Analysis in One Variable
* 01: Loan Preprocessing

The `html` files can also be downloaded and viewed locally with any browser.

The `Rmd` (R markdown) files, where the analyses were done, can be accessed with RStudio or the R IDE of your choice. Please make sure that the packages loaded at the top of the file are installed, using `install.packages("<package name>")`.

Note that the loan data are not included in this repo, since they are rather large, but the initial snapshot can be downloaded from the Kiva site. All intermediate data files can be generated via the functions in the various `Rmd` files.