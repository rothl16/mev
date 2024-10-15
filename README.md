# mev
Moral effort value (mev) replication and extension (Tissot & Roth)

This project aims to replicate and extend the findings of Celniker et al. (2023, Study 6).


# download Qualtrics
Export -> SPSS -> more options -> corresponding data
this actually gives you a csv file -> read with readr
This way, the data seems to be exported in the most convenient and parsimonious way for further processing

# running script
you actually don't have to run the functions_run_first.R script first anymore, as it is sourced through the .Rmd script

# anonymity
we removed some columns with personal data from the raw data and connected the dataframes
this information is saved locally with the authors