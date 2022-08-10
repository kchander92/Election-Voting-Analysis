# Election-Voting-Analysis

### Table of Contents
1. [Installation](#installation)
2. [Motivation](#motivation)
3. [File Description](#files)
4. [Results](#results)

## Installation <a name="installation"></a>
Python 3.8.12 was used on Jupyter Notebook IDE. The following packages are required and should all be installed directly with Anaconda:
- numpy 1.21.5
- pandas 1.4.1
- scikit-learn 1.0.2

## Motivation <a name="motivation"></a>
We analyze voting precinct data from specific states in the 2016 and 2020 states to compare trends and understand their correlations with precinct-level demographics. Specifically, the following questions are addressed:
- How does the change in Dem/Rep turnout scale with each demographic across all four states?
- What features (state, racial groups, precinct population) tended to be most determinative for how much a precinct's margin shifted between the two elections?
- How many general but distinct groups of precincts can be put together based on state and racial composition?

## File Description <a name="files"></a>
This program utilizes four precinct-level election and demographic data files by state:
- precinct-data-AZ.csv
- precinct-data-GA.csv
- precinct-data-NC.csv
- precinct-data-TX.csv

The code is executed in the Jupyter Notebook file Seattle_AirBnb_analysis.ipynb, which is written fully in Python 3.

## Results <a name="results"></a>
See the results discussed in this Medium post.
