# HarryPotterSortingHat
## Introduction
On no! Since its creation, the famous school of wizards, Hogwarts, had never known such
an offense. The forces of evil have bewitched the Sorting Hat. It no longer responds, and
is unable to fulfill his role of sorting the students to the houses.
The new academic year is approaching. Gladly, the Professor McGonagall was able
to take action in such a stressful situation, since it is impossible for Hogwarts not to
welcome new students. . . She decided to call on you, a muggle "datascientist" who is able
to create miracles with the tool which all muggles know how to use: a "computer".
Despite the intrinsic reluctance of many wizards, the director of the school welcomes
you to his office to explain the situation. You are here because his informant discovered
that you are able to recreate a magic Sorting Hat using your muggle tools. You explain
to him that in order for your "muggle" tools to work, you need students data. Hesitantly,
Professor McGonagall gives you a dusty spellbook. Fortunately for you, a simple "Digitalis!"
and the book turned into a USB stick.

## Objectives
In this project DataScience x Logistic Regression, you will continue your exploration of
Machine Learning by discovering different tools.
The use of the term DataScience in the title will be clearly considered by some to be
abusive. That is true. We do not pretend to give you all the basics of DataScience in this
topic. The subject is vast. We will only see here some bases which seemed to us useful
for data exploration before sending it to the machine learning algorithm .
You will implement a linear classification model, as a continuation of the subject linear
regression : a logistic regression. We also encourage you a lot to create a machine
learning toolkit while you will move along the branch.
Summarizing :
• You will learn how to read a data set, to visualize it in different ways, to select and
clean unnecessary information from your data.
• You will train a logistic regression that will solve classification problem.

## General instructions
You can use whatever language you want. However, we recommend that you choose a
language with a library that facilitates plotting and calculation of statistical properties
of a dataset.
Any functions that would do all the heavy-lifting for you (for example, using the
describe function of the Pandas) library will be considered cheating.

### V.1 Data Analysis
First of all, take a look at the available data. look in what format it is presented, if
there are various types of data, the different ranges, and so on. It is important to make
an idea of your raw material before starting. The more you work on data - the more you
develop an intuition about how you will be able to use it.
In this part, Professor McGonagall asks you to produce a program called describe.[extension].
This program will take a dataset as a parameter. All it has to do is to display information
for all numerical features like in the example:

### V.2 Data Visualization
Data visualization is a powerful tool for a data scientist. It allows you to make insights
and develop an intuition of what your data looks like. Visualizing your data also allows
you to detect defects or anomalies.
In this section, you are asked to create a set of scripts, each using a particular visualization
method to answer a question. There is not necessarily a single answer to the
question.

#### V.2.1 Histogram
Make a script called histogram.[extension] which displays a histogram answering the
next question :
Which Hogwarts course has a homogeneous score distribution between all four houses?

#### V.2.2 Scatter plot
Make a script called scatter_plot.[extension] which displays a scatter plot answering
the next question :
What are the two features that are similar ?

#### V.2.3 Pair plot
Make a script called pair_plot.[extension] which displays a pair plot or scatter plot
matrix (according to the library that you are using).
From this visualization, what features are you going to use for your logistic regression?

#### V.3 Logistic Regression
You arrive at the last part: code your Magic Hat. To do this, you have to perform a
multi-classifier using a logistic regression one-vs-all.
You will have to make two programs :
• First one will train your models, it’s called logreg_train.[extension]. It takes
as a parameter dataset_train.csv. For the mandatory part, you must use the
technique of gradient descent to minimize the error. The program generates a file
containing the weights that will be used for the prediction.
• A second has to be named logreg_predict.[extension]. It takes as a parameter
dataset_test.csv and a file containing the weights trained by previous program.
In order to evaluate the performance of your classifier this second program will have
to generate a prediction file houses.csv formatted exactly as follows:
