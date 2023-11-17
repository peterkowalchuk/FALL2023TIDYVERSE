# Shared Commits
## Add the commit to the code you are sharing in this readme file
## After submitting your commit, add a line to this readme file describing the commit, and a link to your markdown file

Initial Description and Link: 
* Demonstrates how to flip ggplot axes
* https://github.com/peterkowalchuk/FALL2023TIDYVERSE/blob/main/ggplot_forcats_fall.rmd


* Demonstrates how to scale axis and move labels (Kelly)
* https://github.com/autistic96/FALL2023TIDYVERSE/blob/main/ggplot_scaling_and_labeling.Rmd


  
Revision/Addition Description and Link:
* Modified ggplot/forcats example to demonstrate sorting, other category
* https://github.com/peterkowalchuk/FALL2023TIDYVERSE/blob/main/ggplot_forcats_fall.rmd


Folorunsho Atanda Addition
* Demonstration of using map() from the purrr package
* Github link: https://github.com/folushoa/Data-Science/tree/Data-607/Tidyverse
=======

# Updates by Haig Bedros (@hbedros)

Vignette and Analysis:  
* Explored a dataset from `FiveThirtyEight` and demonstrated the use of various `tidyverse` functions.  
* https://github.com/acatlin/FALL2023TIDYVERSE/blob/main/hbe.rmd  

Additional Contribution:  
* Introduced a section on **"Exploring Cumulative Distribution with tidyverse"** titled **"Cumulative Followers Distribution"**.  
* https://github.com/acatlin/FALL2023TIDYVERSE/blob/main/ggplot_forcats.rmd

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

## Author
* Matthew Roland
* Document demonstrates a use-case for the TidyR package, specifically, with regards to its pivot functions and searate function

```

## Author
* Matthew Roland
* Date: 2023-06-11
* Link to rmd:
*  https://raw.githubusercontent.com/peterkowalchuk/FALL2023TIDYVERSE/main/Roland%20Tidyverse_CREATE_Assignment.Rmd
* This vignette demonstrates a use-case for the TidyR package, specifically, with regards to using the Pivot and Separate functions to clean and tidy a dataset

# Updates by Jean Jimenez (@sleepysloth12)

Vignette and Analysis:  
* Explored a dataset from `OpenNYC` and demonstrate how to animate geographic data on a map over time
* https://github.com/peterkowalchuk/FALL2023TIDYVERSE/blob/main/jjimenez_tidyverse_queens_carcrash.Rmd

Revision/Addition Description and Link:
* Modified Stroke Data to include NIHSS and added function that calculates NIHSS
* https://github.com/peterkowalchuk/FALL2023TIDYVERSE/blob/main/Roland%20Tidyverse_CREATE_Assignment.Rmd


# Updates by Stephen Phillips (@sphill12)
Added a few useful dplyr functions to help with data analysis

https://github.com/peterkowalchuk/FALL2023TIDYVERSE/blob/main/Tidyverse%20demo%20Stephen%20Phillips.Rmd
