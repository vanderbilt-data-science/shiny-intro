# shiny-intro
Introduction to shiny 

## Overview

Shiny is a mature approach to building interactive apps that is more formal than other popular frameworks, such streamlit. This presents both a challenge and greater flexibility and power. To use Shiny you must first learn about and get comfortable with the basic principles of reactive programming. In this workshop, we cover the essential concepts of reactive programming and of the Shiny framework. We'll use Hadley Wickham's [Mastering Shiny](https://mastering-shiny.org/). The goal is that after the workshop, you can continue self-study of Shiny by reading and working examples from the remainder of the book.



## Resources

There are numerous resources for learning shiny online. Note that there is an older approach and a newer approach to shiny apps. In the newer approach, there is a single app file that combines the user interface (ui) code, the server code, and the call to start the shiny function. In the older approach, the ui code is in a separate file from the server code. 

The main text for this tutorial is https://mastering-shiny.org/.

The solutions to exercises is in https://mastering-shiny-solutions.org/

A collection of learning resources is available at https://shiny.rstudio.com/tutorial/. 

An excellent collection of online interactive primers is available at https://rstudio.cloud/learn/primers.

## Note: Maturing Your Code into an Application

Many projects begin as notebooks, employing literate and exploratory programming. If you wish to build an interactive application, you'll want to mature your code first in order to have an understandable and maintainable app. The process is similar wheter you are working in R or Python. 

1. Extract your code into a script (see https://bookdown.org/yihui/rmarkdown-cookbook/purl.html)
2. Refine/refactor your code into documented functions 
3. Define the required elements for interactivity: What do you need from the user? What do you need to show the user?
4. Code the user interface (ui) and the server, leaving as much code as possible in your original script (see https://mastering-shiny.org/scaling-functions.html). 
