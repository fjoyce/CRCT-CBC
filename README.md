# Coto Brus, Costa Rica Christmas Bird Count Shiny app

[Shiny app](https://fhjoyce.shinyapps.io/CRCT-CBC/) for Coto Brus Christmas Bird Count. 

Adapted from [Sharleen W's Shiny app for Hamilton, Ontario](https://sharleenw.shinyapps.io/hamilton_cbc_shiny/), as described on [this blog]( https://sharleenw.rbind.io/2019/03/24/hamilton-cbc-part-3/)

# data

"HistoricalResultsByCount [CRCT-2022-2022].csv" is the raw csv download (taxonomic sort) from https://netapp.audubon.org/cbcobservation/historical/resultsbycount.aspx# for count code CRCT.

Start year: 122 (2021).

I did do a bit of manual cleanup as described in the Rmd.

cleaning.Rmd takes CRCT-2021_pre-cleaned.csv and outputs CRCT-CBC-2021-cleaned.csv

# root
CRCT-2021-cleaned.csv is the data file used by the app.

app.R is the code for the Shiny app.
