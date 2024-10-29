It seems that both my raw and cleaned datasets are too large to upload directly to GitHub, even using GitHub LFS (at least without paying) as they exceed 100MB. 

This repository includes the R script containing the functions used to clean (clean.Rmd), and links to Google Drive folders containing the raw and cleaned data are included below:

raw_data: https://drive.google.com/drive/folders/1OMIjs58oo7F8HGovNjniooM-5W9fy5z6?usp=drive_link

clean_data: https://drive.google.com/drive/folders/1nb8fkVN-VuvIf45G69UffZGDrVdTvFcM?usp=drive_link

For context, the datasets I cleaned represent voltage readings (potential difference in mV) from pairs of electrodes (1 and 2, 3 and 4, 5 and 6, etc.) embedded in various regions of fungi. Measurements were collected every 1 ms. Four species of fungi were measured over the course of ~5-6 hours: cordyceps, enoki, ghost fungi, and splitgill mushroom.

Note that not all four species studied had the same number of electrodes embedded, nor the total time measured, which is why the data from each species are all in separate files.

Also note that both raw and clean datasets are too large to open in Excel without truncating columns.
