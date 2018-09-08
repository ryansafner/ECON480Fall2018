# ECON 480 Fall 2018
Econometrics lectures for Fall 2018 class at Hood College

## For Onlookers

You can open up each file individually to view on GitHub or download, but it may not render properly (*R*'s Markdown and Github's Markdown languages are slightly different). You can choose to download the entire set of slides as a *.zip* file, or clone the entire repository on your machine if you have *git*, or *R Studio* (see below).

Each lecture has two files associated with it. 

1. A *.pdf* file, which is an output that most are familiar with. Open with a PDF viewer like Adobe Reader or Preview (for Mac). Using the arrow keys or click through the slides as if they were any PowerPoint presentation. 
2. A *.rmd* file, which is a plain text file used to code these lectures using *R Markdown*. 

You can examine an *.rmd* file in *R Studio* to get a sense of how these slides were produced and compiled. Before we learn more about *R* and *R Markdown*, look for "chunks" of *R* code in the file, indicated by three apostrophes (```{r}). *R* runs the code and produces the results (according to certain options you can control) right in that portion of the document, to be included with the output of the document itself. 

The *.rmd* file is compiled using "knitr" to produce a *.pdf* file. It can easily be told to produce a *.doc* or an *html* webpage instead. 

### Using *R Studio* to Clone a Repository

1. In *R Studio*, use the drop down menu: File -> New Project -> Version Control -> Git
![](gitrstudio.png)
2. In the first field, enter the repository's URL (e.g. [http://github.com/ryansafner/ECON480Fall2018](http://github.com/ryansafner/ECON480Fall2018)}\)
3. In the second field, choose a name for the folder to be created on your computer
4. In the third field, choose a location for the folder to be created on your computer  
    - e.g. for me, I store it under `~/Dropbox/Teaching/Hood College/ECON 480 - Econometrics/`
5. Create project. This will clone the existing repository on GitHub into the folder you created on your computer. 

Now you have the entire repository (all the files on GitHub) in that folder, and you can edit the *.rmd* files with *R Studio*. 
