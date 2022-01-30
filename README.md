# Description
* Our project is about volcano eruptions.
* We studied and observed patterns among past eruptions
* We used machine learning to be able to predict information regarding the next eruption

## Acquisition
* Data collected from https://volcano.si.edu/
* We used beautifulSoup to extract information into a dataframe

## Data Cleaning
* We found many "Unknown" entries in the data , that represent different eruptions , so we divided them into groups (Unknown 1-6)
* We replaced values like '--' to NaN values
* We dropped columns that had >50% missing values
* We filled cells based on the most logical approach (mean,upper neighbor,etc..)

## Visualisation
* We plotted the eruptions on top of the world map
* We showed eruptions occured mainly around the Ring of Fire
* We plotted the data into multiple charts

## Machine Learning
* We predicted the strength of the next eruption
* We predicted volcano types based on their heights
* We predicted S02 emissions.

