# Introduction to R Markdown
## NISRA Coffee and Coding - R Markdown Introduction

### Setup 
- Download the .zip folder of this repo (green code button dropdown to top right, then select "Download ZIP").

- Unzip this folder to a location on your machine e.g. Desktop

- Open the folder and open the _"CC-intro-rmarkdown.Rproj"_ file. This should open an instance of RStudio

- Next open the `renv_setup.R` script and follow the steps within titled `renv::restore()` and `renv::status()`. If successful, renv should now be activated and all required packages should be available.

- When setting up renv within this project, you may see error lines printed to console similar to: 
```
renv was unable to query available packages from the following repositories: 
- # file:////pr-clus-vfpdfp/DOF_NISRA_R_Packages/production/src/contrib --------
```
- These do not affect the setup of the project and can be ignored

- If the install flags up errors and stops:
  - You may not have access to the package repository needed to install packages within this project. Contact techlab@nisra.gov.uk for more info on this

Open _"code/demo/demo_report.rmd"_ and follow along through the code
