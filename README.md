# COVID_2.15.23

CREATING A PROJECT
# Starting an R Data Analysis Project ####

Here is the recording -- https://doimspp-my.sharepoint.com/:v:/g/personal/msaid_nps_gov/Eb30Ljh44-hFgJJR5cUOM_MBLia3huywwq24faMGJ4DXtQ

# Open R Studio
# Clear the three screens


library(devtools)
devtools::install_github("dgrisafe/freshproject")
library(freshproject)
freshproject::create_fresh_project("Example NPS", proj_dir = "C:/Users/msaid/OneDrive - DOI/R")

# Now I am going to start another one for COVID specifically
freshproject::create_fresh_project("COVID Example", proj_dir = "C:/Users/msaid/OneDrive - DOI/R")

# Open an R project
# You need to create a new folder with a  name you want

# Create Local Git
library(usethis)
use_git()

# Connecting to Github
library(usethis)
use_github()![image](https://user-images.githubusercontent.com/124802247/219148324-68fd7206-4cb4-4a15-848f-9ae80665a75b.png)
