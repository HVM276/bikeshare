# US Bikeshare Data Analysis Project

## 13/05/2020

## Overview:
In this project, _Python_ is used to explore data related to bike share systems for three major cities in the United States — _Chicago, New York City,_ and _Washington_. 
- The source code takes in raw input from the user to create an interactive experience. 
- According to the input the code will import the data and will provide information by computing descriptive statistics.

## Files used:
* bikeshare.py

## Softwares needed:
* _Python 3, NumPy,_ and _Pandas_ installed using _Anaconda_
* A text editor, like _VS Code_ or _Atom_.
* A terminal application (_Terminal_ on _Mac_ and _Linux_ or _Cygwin_ on _Windows_).

## Code explained in Detail:
### How the program works:
The code developed takes in raw input to create an interactive experience in the terminal that answers questions about the dataset. The experience is interactive because depending on a user's input, the answers to the questions will change! There are four questions that will change the answers:

* Would you like to see data for _Chicago_, _New York_, or _Washington_?
* Would you like to filter the data by month, day, or not at all?
* (If they chose month) Which month - _January_, _February_, _March_, _April_, _May_, or _June_?
* (If they chose day) Which day - _Monday_, _Tuesday_, _Wednesday_, _Thursday_, _Friday_, _Saturday_, or _Sunday_?

The answers to the questions above will determine the city and timeframe on which you'll do data analysis. After filtering the dataset, users will see the statistical result of the data, and choose to start again or exit.

### The Datasets:
Randomly selected data for the first six months of 2017 are provided for all three cities. All three of the data files contain the same core six (6) columns:

* Start Time (e.g., 2017-01-01 00:07:57)
* End Time (e.g., 2017-01-01 00:20:53)
* Trip Duration (in seconds - e.g., 776)
* Start Station (e.g., Broadway & Barry Ave)
* End Station (e.g., Sedgwick St & North Ave)
* User Type (Subscriber or Customer)