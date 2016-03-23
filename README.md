# Lab-exercise-2
These exercises will help you continue to develop your Python skills and to learn a bit more about reading data files and plotting age data. Feel free to refer back to the first Python tutorial as needed. For each exercise, you will be asked to submit a copy of your Python code, a plot and answers to a few questions via Github.

## Problem 1
For this exercise, you are given a [broken Python script](read_and_plot_data.py) for reading and plotting thermochronometer age data. Your job, with your newly acquired Python skills, is to fix the **6 problems** with the script so that it does what says it should in the comments. The problems are in comments that start with the text `# FIX`. Data for this exercise comes from a [recent paper published on the exhumation of the Himalaya in Bhutan](http://dx.doi.org/10.1002/2013JB010891), in case you're curious. Your modified script should:

1. Read the data file and split the data into separate arrays for each variable.
2. Calculate the goodness of fit between the measured and predicted ages in the data file. The goodness of fit equation you should use is

    ![Reduced chi-squared](Images/reduced-chi-squared.png)
