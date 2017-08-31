# Assignment 1

## Installation & Account Setup

In this assignment you will be setting up the software and online tools that you will be using throughout this course. Below there are links and instructions to relevant sites.

The first step is to create a [Github account](https://github.com/join?source=header) if you do not already have one: 

Next you will need to install the software we will be using (if you already have them installed make sure they are the latest versions):
   * R
   * RStudio
   * Git
   * Firefox (it is also possible to install Zotero desktop and not use Firesfox if you prefer)
   * Zotero plugin for Firefox

## Installing R
* Choose a [download mirror site](https://cran.r-project.org/mirrors.html) from the list that is close to you geographically  
* Download the version of R that is appropriate to your operating system
* Install R in a manner appropriate to your operating system ([MacOSX](https://youtu.be/Ywj6yNfc5nM), [PC](https://youtu.be/5ZbjUEg4a1g))

## Installing RStudio (Graphical User Interface for R)
* Download the free version of [RStudio](https://www.rstudio.com/products/rstudio/download/)
* Install RStudio in a manner appropriate to your operating system ([MacOSX](https://youtu.be/Ywj6yNfc5nM), [PC](https://youtu.be/5ZbjUEg4a1g))

## Installing Git
* Git is a version control system to keep track of our work and collaboration
* Instructions for setup can be found [here](https://help.github.com/articles/set-up-git/) and [here](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
* Download [Git](https://git-scm.com/downloads) 

## Firefox & Zotero
* An important aspect of the class is maintaining notes and documentation on out work in bibliographic software. In this class we wil use [Zotero](https://www.zotero.org/) in conjunction with the [Firefox 48.0.1](https://www.mozilla.org/en-US/firefox/new/) web browser. Please ensure you have these both installed on your machine.  
* Once you have these programs installed you can [download the Zootero reference list for the class](https://github.com/data-science-in-ed/Tools) and [upload it into Zotero](https://www.zotero.org/support/getting_stuff_into_your_library)  
        The file hudk4050-references.rdf contains bibliographic information for references used this semester.
          1. Download the the this repository by clicking the green button in the top right and selecting "Download Zip" 
          2. Extract the hudk4050-references.rdf file
          3. Import the hudk4050-references.rdf file into Zotero according to the instructions [here](https://www.zotero.org/support/getting_stuff_into_your_library).

## Connecting Git-Github-RStudio

You will also need to link your Github account to RStudio by following [these instructions](https://support.rstudio.com/hc/en-us/articles/200532077-Version-Control-with-Git-and-SVN).

For many students this will be the most challenging task this semester. Several errors can be corrected by following the instructions located [here](http://happygitwithr.com/troubleshooting.html).

A common error is: 

`error: unable to read askpass response from 'rpostback-askpass'`

The fix for most systems is:

* In RStudio, click on the "Tools" menu and select "Shell"
* Run the following command: `git push -u origin master` (*it might ask you for your git username and password. Supply this information, make sure it is correct*)
* Close the window
* Now make some more edits to some file so that you have new content to push click on the "push" button in RStudio and this time the push should work

If you are using a Mac and this does not fix your error please try [these instructions](https://github.com/core-methods-in-edm/Assignment1/blob/master/MAc%20Github%20help%20pages.pdf). 


## Swirl

* Once you have installed both programs, open RStudio (RStudio will automatically open R at the same time)
* R is modular, we can install mini-programs called *packages* within it like apps on your phone to do specific tasks, in this activity we will be using the Swirl package. Swirl is a teaching tool for learning R, it comprises questions and answers and a bit of AI (for positive reinforcement)
* Install the Swirl package by typing `install.packages("swirl")` in the console window (located on the left hand side of the RStudio interface). If you get an error message you can also install by clicking the "packages" tab in the right hand pane and then clicking "install".
* Once we have installed the package we need to turn it on, we do this by inputing the code `library(swirl)` - Swirl will tell you to type `swirl()` **but don't do that just yet!**
* First we need to load a lesson into Swirl, to do this cut and paste the following code into the console window (you will need to be connected to the internet):  
`install_course_github("DML-Learning-Analytics", "Pre-Workshop_Activity")`
* Once the lesson finishes installing type `swirl()`, Swirl will then guide you through setting up a user Id (please use your full name so we can identify you later). Choose the `Pre-Workshop Activity` course and the `Introduction to R` lesson when you have the option.
* At the completion of the lesson you will submit your answers through a Google form. We will collect information on how many questions you answer, how many attempts you took to answer each question and the time you answered
