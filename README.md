# Introduction

This repository is to store and share generic templates and workflows for bioinformatics analysis in the Singh lab at OSU.
The code uploaded here should contain both well commented code as well as written explanation as to the broader purpose of the code. 
Files and documentation should be complete enough that someone new to that program and analysis should be able to understand why it is being run. 
To this end it the documentation should be written so that someone with an understanding of molecular biology but new to bioinformatics, like a new graduate student, can understand it 

For more information and the documentation style guide, please see the [style guide][templates] folder. 

# Resources

Most of the code here is written in two languages: UNIX/bash and R.
The code and documentation assumes a base level knowledge of the languages. 
If you are unfamiliar with either of them, the resources below might help. 
In addition there is myriad resources available online for both languages.
Stack Overflow and the Biostars forums are both wonderful places to get help for specific questions or errors you run into.

## R

R is a language primarily for data manipulation, analysis, and graphing.
It is incredibly powerful for these purposes, but rather limited for other uses.
By default R is used via a command line terminal. 
However, most people use [R studio][Rstudio] to provide a GUI for the program.
The same company also makes a number of frequently used packages known as the tidyverse. 

A good place to start with R is the book [Hands on Programming][Hands on programming].
Working through this book will provide an understanding of R syntax and how to do basic functions like installing packages.
Once you are familiar with writing code in R the book [R for Data Science][Data Science book] will provide training more relevant to what we use it for. 

Once you start working with R in ernest, it's useful to set up documents with both your code, explanation, and output in one place.
This is especially helpful if you are using an electronic lab notebook.
To this end the book [R Markdown: A definitive Guide][R markdown book] is an good place to learn how to make HTML (or other file format) notebooks.
Most of the documents in this repository are written in an R markdown notebook.

## UNIX/ BASH

Jobs submitted to the [supercomputer][OSC] are submitted to a linux system via command line or through shell scripts.
The shell we use is called Bash, and is the default shell on most linux systems.
The OSC has a [good tutorial][linux tutorial] on using command line. 
They also have a number of other resources to get you started using the command line interface on the supercomputer under their resources tab.

## Other Resources

- [OSU's Code Club][Code club] has a number of highly useful webinars and classes to teach you how to use the OSC and R
- The [Biostars Handbook][Biostars] is a great resource to get started on a number of more complex techniques like analyzing RNA-sequencing data.


[Rstudio]: https://posit.co/download/rstudio-desktop/
[templates]: [https://github.com/singhlabosu/BioinfoWorkflows/tree/Introductory-documents/Formatting%20and%20Styleguide]
[Hands on programming]: https://rstudio-education.github.io/hopr/
[Data Science book]: https://r4ds.hadley.nz/
[R markdown book]: https://bookdown.org/yihui/rmarkdown/

test
[OSC]: osc.edu
[linux tutorial]: https://www.osc.edu/content/linux-command-line-fundamentals
[Code club]: https://biodash.github.io/
[Biostars]: https://www.biostarhandbook.com/index.html
