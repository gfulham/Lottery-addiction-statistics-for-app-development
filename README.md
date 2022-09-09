# Lottery addiction statistics for app development

Development of a mobile app that is meant to help lottery addicts better estimate their chances of winning.

Questions to answer:

- What is the probability of winning the big prize with a single ticket?
- What is the probability of winning the big prize if we play 40 different tickets (or any other number)?
- What is the probability of having at least five (or four, or three, or two) winning numbers on a single ticket?

[The data set](https://www.kaggle.com/datascienceai/lottery-dataset) has data for 3,665 drawings, dating from 1982 to 2018.

The 6/49 lottery 6 numbers are drawn from a set of 49 numbers without replacement. We will need two main functions:
- a function that calculates factorials
- a function that calculates combinations