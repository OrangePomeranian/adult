# Credit project - guidelines 

## Data
The data comes from the website (http://archive.ics.uci.edu/ml/datasets/Adult); this is a publicly available dataset used in machine-learning projects.
## Purpose
To develop a model (logistic regression) that predicts a person's income (under 50k per year or over 50k per year) from the data

## Tasks:
  In the type_employer column:

  Replace the entries "Federal-gov" and "Local-gov" with "SL-gov"

  Replace the entries "Self-emp-inc" and "Self-emp-not-inc" with "self-emp"

  Reduce the number of entries in the "marital" column to three (Married;Not-Married;Never-Married)

  Reduce the number of entries in the country column (e.g. grouping by continents? another approach?)

  Replace "?" entries with NA values

  Delete rows containing NA entries

  Divide data into test and learning set

  Build model using functions (glm)

  Refine the model using step functions

  Test model on test data (confusion table)

  Calculate the F1-score for the developed model
