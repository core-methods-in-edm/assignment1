# Assignment 1

[link] (https://github.com/mahshaddav81)

## My Goals for HUDK4050
*Learn more about Git, R, Github, RStudio
*Try new ways to organize data in the office
*Use what I learn in my research data management later

## Video Review
The videos are great in that they cover a lot of complicated materials in a very clear and relatively simple language. Although closed captions and transcripts are available, I would love for Charles to speak a bit more slowly so that I can follow along better. He's too fast. I have the same critique for the Zoom workout video. I had to pause and try each practice and resume playing the video. I don't know how people managed to do it live at that pace. I would not change a thing about the way the course is organized and presented: very neat.

Skill | Score |
------|-------|
Coding|   2   |
Great |  Fast |


## This is how I am feeling about the semester:
![](/Desktop/Core Methods Data Mining/optimism.jpg)


## Part A: Installation & Account Setup

In this assignment you will be setting up the software and online tools that you will be using throughout this course. Below there are links and instructions to relevant sites.

The first step is to create a [Github account](https://github.com/join?source=header) if you do not already have one: 

Next you will need to install the software we will be using (if you already have them installed make sure they are the latest versions):
   * R
   * RStudio
   * Git
   
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

## Connecting Git-Github-RStudio
* You will also need to link your Github account to RStudio by following [these instructions](https://support.rstudio.com/hc/en-us/articles/200532077-Version-Control-with-Git-and-SVN).
* For many students this will be the most challenging task this semester. Several errors can be corrected by following the instructions located [here](http://happygitwithr.com/troubleshooting.html).

A common error for Macs is: 

`error: unable to read askpass response from 'rpostback-askpass'` or a similar error saying that Git is missing.

The fix is often:

* In RStudio, click on the `Tools` menu and select `Global Options` and then `Git/SVN`
* The `Git executable` box should contain the following filepath: `/usr/local/git/bin/git` if it does not contain this **EXACT** filepath (I.E. it says something like `local/git`) then click `Browse` and locate the `git` file at `usr/local/git/bin/git` and click `OK`.
* Click `Apply` and then `OK`
* Exit RStudio and then reopen, you should see a `Git` icon when you complete Part B below.




