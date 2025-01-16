# THEE_2024reproducibility
Purpose: showcase reproducibility principles & GitHub for Theoretical Ecology and Evolution research practical (Fall 2024)
 
# Introduction
A readme file is the first thing a collaborator will encounter when you share your project with them. Its purpose is to orient them to your project: brief but detailed!

Structure it from wide to narrow: Start with the title and a short description of the project's motivation/purpose. If you have main results, you can list them here. Then explain how the project can be installed (e.g., any required dependencies like R or RStudio (versions?), any required packages). Next describe how the files are structured in the repository (which files run the code?, where can collaborators find the data?, etc.).

# How to install
You will need R and RStudio. Any newer version should work (I used R 4.3.3 and RStudio 2023.12.1).

If you want to "print" the R notebook file to a .pdf or .html file (this is called "knitting" the notebook file), you will need to install the knitr package (version 1.49 or better). You can use the command: `install.packages("knitr")`

# File structure
In this repository there are no sub-folders.
The 2 .pdf files ("THEE_ResearchPractical--Reproducibility_2024-10-15.pdf" and "THEE_ResearchPractical--GitTutorial_2024-10-15.pdf") contain the lecture slides and exercises we did in-class.

The code for the exercises and their solutions is found in the file "reproducibility.Rmd" (with a knitted .html version as well).

When you run reproducibility.Rmd, it will produce .csv files whose names will be in the format "numbers_1_to_10--multiplier \d .csv". These files are in the main folder but it would be ideal if the code and all the files it produces was found in a dedicated subfolder.

**To do: update file structure!!**
   - change code to save output files in their own dedicated folder

