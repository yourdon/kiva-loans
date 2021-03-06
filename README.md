Kiva Loan Analysis
=================================

These files present analysis and predictive modeling of loan repayment rates for the [Kiva loan data set](http://build.kiva.org/docs/data/snapshots), based on a snapshot taken at 2015-07-10 20:10:00 UTC. The initial parts are concerned with preprocessing and simple profiling, so readers with limited time may wish to ready [the summary](https://cdn.rawgit.com/yourdon/kiva-loans/c92cc58fa86c00be2a9933eb0618a1517527d497/Running_Summary_and_Highlights.html) or skip the earlier parts. 

Running
-------

Each part of the analysis can be viewed online, thanks to RawGit.

* [Running Summary and Highlights](https://cdn.rawgit.com/yourdon/kiva-loans/c92cc58fa86c00be2a9933eb0618a1517527d497/Running_Summary_and_Highlights.html)
* [06: Tree and Forest Models](https://cdn.rawgit.com/yourdon/kiva-loans/c92cc58fa86c00be2a9933eb0618a1517527d497/06-Tree_and_Forest_Models.html)
* [05: Repayment Rate: Linear Models](https://cdn.rawgit.com/yourdon/kiva-loans/c92cc58fa86c00be2a9933eb0618a1517527d497/05-Repayment_Rate_Linear_Models.html)
* [04: Goal Setting and Subsetting](https://cdn.rawgit.com/yourdon/kiva-loans/c92cc58fa86c00be2a9933eb0618a1517527d497/04-Goal_Setting_and_Subsetting.html)
* [03: Analysis in Two Variables](https://cdn.rawgit.com/yourdon/kiva-loans/3afb39154ed81c94f782147cd6c0d3e18cb96ff8/03-Analysis_in_Two_Variables.html)
* [02: Analysis in One Variable](https://cdn.rawgit.com/yourdon/kiva-loans/3afb39154ed81c94f782147cd6c0d3e18cb96ff8/02-Analysis_in_One_Variable.html)
* [01: Loan Preprocessing](https://cdn.rawgit.com/yourdon/kiva-loans/c92cc58fa86c00be2a9933eb0618a1517527d497/01-Loan_Preprocessing.html)

The `html` files can also be downloaded and viewed locally with any browser.

The `Rmd` (R markdown) files, where the analyses were done, can be accessed with RStudio or the R IDE of your choice. Please make sure that the packages loaded at the top of the file are installed, using `install.packages("<package name>")`.

Note that the loan data are not included in this repo, since they are rather large, but the initial snapshot can be downloaded from the Kiva site. All intermediate data files can be generated via the functions in the various `Rmd` files.