# Shared Commits
## Add the commit to the code you are sharing in this readme file
## After submitting your commit, add a line to this readme file describing the commit, and a link to your markdown file

Initial Description and Link: 
* Demonstrates how to flip ggplot axes
* https://github.com/peterkowalchuk/FALL2023TIDYVERSE/blob/main/ggplot_forcats_fall.rmd

* Demonstrates how to scale axis and move labels (Kelly)
* https://github.com/autistic96/FALL2023TIDYVERSE/blob/main/ggplot_scaling_and_labeling.Rmd

* Demonstrates how to animate geographic data on a map over time (Jean)
* https://github.com/sleepysloth12/data607_tidyverse_queens_crash/blob/30c9e4dc2d900ed2bdb901c3390d212d13cd451e/jjimenez_tidyverse_queens_carcrash.Rmd

Revision/Addition Description and Link:
* Modified ggplot/forcats example to demonstrate sorting, other category
* https://github.com/peterkowalchuk/FALL2023TIDYVERSE/blob/main/ggplot_forcats_fall.rmd
# TidyVerse Create Repository README

## Author
- **Name:** Mikhail Broomes
- **Date:** 2023-11-05

## Link to code 
- https://github.com/MAB592/FALL2023TIDYVERSE/blob/main/TidyVerse%20CREATE%20assignment.Rmd

## Libraries
- To run the code in this repository, make sure you have the following R libraries installed:

 The core R packages used are.
    - dplyr 1.1.2
    - readr 2.1.4
  

## Joins in R
In this repository, you will find information on how to perform a full join using the dplyr package in R. The focus is on merging two datasets containing movie ratings for the years 2021 and 2022. The goal is to combine these datasets and create a comprehensive list of movie ratings, ensuring that all movies from both years are included and missing values are filled with NA where necessary.

## Dataset Description

The repository includes two datasets:

1. `movieratings_2021`: Contains movie ratings for the year 2021.
2. `movieratings_2022`: Contains movie ratings for the year 2022.

The merging process is based on a unique identifier for each movie.

## Example Usage
To load the datasets and perform a full join, you can use the following code:

```R
# Load the datasets
movieratings_2021 <- read_csv("URL_TO_MOVIERATINGS_2021_CSV_FILE")
movieratings_2022 <- read_csv("URL_TO_MOVIERATINGS_2022_CSV_FILE")

# Perform a full join
full_movie_ratings <- full_join(movieratings_2021, movieratings_2022, by = "Film")
