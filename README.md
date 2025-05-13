# Starting out with Git and some useful data tricks

## Purpose

This project is intended to provide an introduction to Git and its use with an online repository, such as GitLab (or GitHub) for SANBI staff that are becoming familiar with the use of R, RStudio, Quarto and similar tools to create reproducible and shareable content. 
The content is very much limited to the basics of that context and there are many features and abilities of the software and platforms that are not mentioned or explored. 
It is also peppered with a few recommendations for keeping your workflows organised and conducive to collaboration and easing the path towards reproducible science.
Many of those suggestions are personal preferences that might be achieved in other ways.

## Preparing for the lesson

### Create a GitHub or GitLab profile (free)

To avoid potential lengthy delays during the tutorial, please sign up for a free personal [GitHub](https://github.com/signup) or [GitLab](https://gitlab.com/users/sign_up) account.

GitHub is the chosen platform for the SANBI NBA work. 
Further information on the platforms can be read on their respective websites. 
We (the marine team) have done most of our work on GitLab up until now, as it allows easy structuring of groups and subgroups to organise our projects and our team is small. 
But, if you want to have more than 5 members on your project and want to remain on the free tier, you'll likely want to opt for GitHub.

### Clone the project repository

To clone this repository in RStudio,

  1.  Go to the [GitLab repository](https://gitlab.com/nba_2025/git_tutorial) or the [GitHub repository](https://github.com/jockongit/git_tutorial/tree/main), depending on which platform you signed up with.
  2.  Copy the relevant '*Clone with ...*' URL from the project page under the *Code* drop-down menu (you need to have connected your machine to an online GitLab or GitHub profile prior).
  3.  Within RStudio, create a new project (under *File* menu) and select *Version Control* and then *Git* to paste the copied URL. Ensure you're happy with the directory where the project will be saved before you hit *Create Project* (**hint: I tend to save all my R projects in one 'Rprojects' folder, so that it is easy to back them up and I always know where to find them.**)  
      
Once cloned, you can open the html files or the Quarto (*.qmd*) source files, both of which are in the *quarto* folder.

## Status

This project is in development and intended to be presented at a SANBI training workshop in May 2025.

## Acknowledgments

Much of the Git content is reproduced from teaching materials provided by [Fathom Data](https://www.fathomdata.dev/) and online resources, which I will try to link to or acknowledge in the document.