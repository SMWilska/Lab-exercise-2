# Lab-exercise-2
These exercises will help you continue to develop your Python skills and to learn a bit more about reading data files and plotting age data. Feel free to refer back to the first Python tutorial as needed. For each exercise, you will be asked to submit a copy of your Python code, a plot and answers to a few questions via Github.

## Problem 1
For this exercise, you are given a [broken Python script](read-and-plot-data.py) for reading and plotting thermochronometer age data. Your job, with your newly acquired Python skills, is to fix the **6 issues** with the script so that it does what says it should in the comments. The issues are in comments that start with the text `# FIX`. Data for this exercise comes from a [recent paper published on the exhumation of the Himalaya in Bhutan](http://dx.doi.org/10.1002/2013JB010891), in case you're curious. Your modified script should

1. Read the data file and split the data into separate arrays for each variable.
2. Calculate the goodness of fit between the measured and predicted ages in the data file. The goodness of fit equation you should use is

    ![Reduced chi-squared](Images/reduced-chi-squared.png)

where *n* is the number of ages, *O* is the measured age, *E* is the predicted age and *σ* is the standard deviation.

3. Produce a plot of the measured ages with their error bars and the predicted ages, both as a function of latitude. Be sure to include axis labels and a title.

In addition to modifying the script, you should submit answers to the following questions:

1. Looking at your plot and without looking at the goodness of fit value, how well would you say the predicted ages fit the measured ages in this example? Is this difficult to do? Why or why not?
2. How well would you say the predicted ages fit the measurements using the calculated goodness of fit? Is your calculated goodness of fit intuitive to use? Why or why not?

**For this problem, save a modified copy of the code in your Github repository and edit the `README.md` document to display a copy of your plot and answers to the questions above.**

## Problem 2 - This one is iffy
For this exercise, you will add a conditional statement to your modified code from Problem 1 that changes the formatting of the plot as a function of one of the plotted values. You are free to choose how you modify the plot, but be sure to explain what you did. You might consider changing the line color, symbol type or some other aspect of the plot. For this exercise, you should

1. Start by making a copy of your `read-and-plot-data.py` file from Problem 1 and saving it as `read-and-plot-data-part2.py`.
2. Provide a brief description of the change you made to the code and what it does.
3. Display a plot in this document demonstrating the modified plotting. Be sure it is clear that something has changed!
4. Write a caption for your plot describing it as if it were in a scientific journal. You should clearly mention what is plotted, the symbol types/colors and any other particular items in the plot such as changes related to your conditional statement.

**For this problem, save a modified copy of the code in your Github repository, and edit the `README.md` document to display a copy of your plot with the requested figure caption clearly describing what was modified in the plot.**

# Answers
## Problem 1

**TOO HARD**

This is some text. You can use *italics* or **bold** text easily. You may want to read a bit more about [formatting text in Github-flavored Markdown](https://help.github.com/articles/basic-writing-and-formatting-syntax/). You can see an example of how to display an image below.

![Text shown if image does not load](Images/sine.png)

Here is a bit more text beneath the image. Have fun!
