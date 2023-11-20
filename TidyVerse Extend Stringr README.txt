# TidyVerse Extend - Readme

## Introduction

This extension to the existing TidyVerse example focuses on extracting the release day from the "Release Date (US)" column using the `str_extract` function. The goal is to enhance the dataset by adding a new variable, "release_day," which captures the day component of the release date.

## Code Explanation

The provided code snippet performs the following actions:

1. **Extracting Release Day:**
   ```{r}
   movies_extended <- movies %>%
     mutate(release_day = str_extract(`Release Date (US)`, "[0-9]+"))
   ```

   This code utilizes the `str_extract` function to extract numerical values from the "Release Date (US)" column, specifically capturing the day. The results are stored in a new column named "release_day."

2. **Displaying the Updated Dataset:**
   ```{r}
   # Display the dataset with the new release_day column
   head(movies_extended)
   ```

   The code then displays the updated dataset, showcasing the addition of the "release_day" column to provide a quick overview of the changes.

## Implementation

To implement this extension, simply incorporate the provided code into the existing analysis script after loading the original dataset and exploring the initial string manipulations. This extension contributes to a more comprehensive understanding of the dataset by introducing a new variable related to the release day of the movies.).
