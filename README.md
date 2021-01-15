# Assignment 1

# new message 

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

## Part B: R Markdown

The final part of this assignment is for you to utilize all the software you just installed to modify an R Markdown file.

### Clone the repository to you computer
* In the top left corner of the repository page, click `Fork` - this step is often forgetten, try not to forget it!
* Then click `Code` and copy the URL for the repository
* Open RStudio and click `File` -> `New Project` -> `Version Control` -> `Git`
* Paste the URL into the `Repository URL` box
* Name your project in the `Project Directory Name` box
* Browse to an appropriate folder on your computer to put your project, I would suggest you make a folder for the class somewhere, don't put the project on the Desktop or in the Root Directory. Moving a project after you create it can cause problems later so it is best to put projects somewhere that is permanent.
* Click `Create Project`

### Edit the markdown document
* Once you have created your project, open the `Assignment1.Rmd` file by clicking on it in the `Files` pane of RStudio (bottom-right by default)
* Open the `R Markdown Cheat Sheet` (link available on the course website)
* Use the Cheat Sheet to make the following changes to the Assignment1.Rmd file:
  * Create a top level heading that says "Assignment 1"
  * Insert a link to your Github profile page
  * Create a second level heading that says "My Goals for HUDK4050"
  * Create a bulletted list that describes three goals you have for this class
  * Create another second level heading that says "Video Review"
  * Add a review of the class videos you have seen so far, write a sentence or two about what you would change and what you would keep
  * Create a table with two columns and three rows. In the header (first row) of the first column put the word "Skill", in the header of the second column put the word "Score". In the second row of the first column put a word that describes a skill you want to improve at, and in the second row of the second column put a score out of 10 that describes your current level of that skill. In the remaining two cells write your opinion of the class videos you have seen so far. 
  * Create another second level heading that says "This is how I am feeling about the semester"
  * Find an image of a piece of art that sums up how you are feeling about the semester ahead, upload it to the repository (add it to the folder where your project is located) and then insert it into the document
  * Generate an HTML document called "Assignment1.html" from your markdown code by pressing the "knit" button
  
### Commit-Push-Pull Request your assignment
* Now find the `Git` tab in RStudio - top right pane - and click it
* Click `Commit`to open the Git interface
* In the left hand pane check the boxes for your `Assignment1.Rmd`, your HTML file file and your image file
* Write a message in the `Commit Message` box, something that describes the work you have done like "Uploading assignmnet 1 files"
* Click `Commit`
* Click `Push` (top right) a dialog box should appear with a message like, "2 files changed, 20 insertions"
* Now return to Github and refresh the page, your edited .Rmd file and your image file should now be in the repository
* Next, to submit your assignment click `Pull Requests`(top left) and then `New pull request` and then `Create Pull request`
* Congratulations! You have just submitted your assignment. You can update it at any time by going through the same process `Commit` -> `Push` -> `Pull Request`


