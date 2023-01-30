#test

title: "Assignment 1: R Markdown practice"
author: "Charles Negash"
date: "`01/29/2023`"
documentclass: article
geometry: margin=1in
fontsize: 11pt
output:
  pdf_document:
    toc: false
    df_print: kable
    fig_caption: false
    number_sections: true
    dev: pdf
    highlight: tango
  html_document:
    theme: paper
    self_contained: true
    toc: false
    df_print: kable
    fig_caption: false
    number_sections: true
    smart: true
    dev: svg
urlcolor: blue
---

<!-- Write your Markdown below this line -->
# How the Course Works
The weekly interactive tutorials must be completed by the start of each week. Then each weekly
assignment will be due at the end of the week.

#Course Goals
By the end of this course students will be able to:

*  Use GitHub for creating a reproducible research document.\
         - My GitHub username is : *cnegash*
* Obtain, clean, transform and visualize a dataset using the R programming language.
* Interpret and predict dataset trends using statistical inference and models
*Critically examine and interpret statistical claims reported in mass media.

#Including Code
3.1 Running R Code in a chunk

  x <- 2+2

  x +3
  
 ## {1} 7
  
  The output of first line of code is not printed out because it is assigned to a variable instead.
  
  The second line of output is printed out instead, but this means that the calculated value has notbeen saved for future use

**3.2 Displaying Graphs**

ggplot2::qplot(data = iris, x = Sepal.Length, y = Sepal.Width)
