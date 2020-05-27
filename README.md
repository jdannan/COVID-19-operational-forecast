# COVID-19-operational-forecast

27/5/2020

operational.tar is a bundle with two Rmd files (Rmarkdown) that generate analyses and figures for the revised version of manuscript. Will add URL when manuscript available.


15/4/2020 
Manuscript as submitted to medrxiv with turnkey code for all analyses and figures is in paper_github.zip
(actually it has v minor edits in text compared to the medrxiv version, code is unchanged).

This is an updated and improved analysis method and the earlier files described below are deprecated.

----------
covid-19_mcmc_prediction_public.Rmd

simple MCMC parameter estimation for forecasting COVID deaths (etc)

Should run out of the box (once you've put the data file in the right place) to generate the forecast I
published on morning of 11 April based on data to 10 April. It's an Rmarkdown document that runs in
RStudio but I'm sure you can work out how to execute the code via your workflow of choice.

UK.worldometer.txt needs to go in a data subdirectory (or just change the path in the code of course).
It's basically cut and paste from the html on the UK worldometer page to create a trivial csv file.
Other data sources are available.
