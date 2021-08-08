# configr
Contains 2 config files for R initialization at start. For files to take effect they should be placed in folder *etc* in R installation path.
## Renviron.site
Contains:
* R_LIBS_USER variable which specifies default path for R packages folder.
* PATH env variable modification to include default Rtools installation path.
## Rprofile.site
* Contains code for automatic packages and R upgrade to new version when the newer ones available.