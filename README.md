# MBio (Year 3) Computer skills practical: Bayesian phylogenetics and epidemiology
Presented by Bernardo Gutierrez and Rhys Inward

## Repository structure and usage
The structure of this repository is shown below. To go over the contents of the R Markdown file, just clone the repository in a local directory and run it in RStudio - paths to required files should work with no editing as long as the working directory is set to the cloned directory.

```
Y3_Computer_skills_Bayesian_phylogenetics/
├── MCC_trees
│   ├── MCC_CHIKV_IndianOcean.tree
│   └── MCC_CHIKV_IndianOcean_updated.tree
├── MCMC_log_files
│   ├── CHIKV_IndianOcean_BEAST_output_log.csv
│   └── CHIKV_IndianOcean_updated_BEAST_output_log.csv
├── Raw_files
│   ├── CHIKV_IndianOcean_metadata.csv
│   └── CHIKV_IndianOcean_updated_metadata.csv
└── CHIKV_BEAST_output_processing.Rmd
```

## Script for running this repository
Clone this repository to your local machine by accessing the console/terminal and typing the following (make sure you have git installed)

```
git clone git@github.com:BernardoGG/Y3_Computer_skills_Bayesian_phylogenetics.git
```
install.packages("remotes")
remotes::install_github("YuLab-SMU/ggtree")
