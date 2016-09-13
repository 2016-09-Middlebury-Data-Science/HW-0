Homework 0
================

You are currently in the GitHub repository (repo) for `HW-0`. You must have completed all the steps in [Setting Up](https://rudeboybert.github.io/MATH216/jekyll/update/2016/09/12/getting-started.html).

Learning Goals
--------------

-   You will not be doing anything substantive for HW-0, but rather practicing the homework and final project submission process for the semester.
-   The submission process partially mimics how a lot of collaborative work is done in practice on [GitHub](https://github.com/), a web-based repository hosting service that is widely used by the open-source coding community. Think of it as a social network for code and data.
-   As a result, you'll learn some GitHub lingo: fork, commit, push, and pull request.
-   All work in this class will be submitted in [R Markdown](http://rmarkdown.rstudio.com/), which is a tool for reproducible research that allows for seamless integration between R code, R output, graphs, and text input. For those of you new to it, you'll see why it makes sharing statistical analyses easy in `HW-0.Rmd`.

Homework
--------

This process will be the same for all homeworks and the final project.

1.  **Fork the repo**:
    1.  "Fork" is GitHub lingo for "make a copy of my own". In the top right corner of this page, click on *Fork* and select your GitHub account. This forks a copy of this original master repo `HW-0` to your GitHub account.
    2.  In the top left of the page, you should see "YOUR\_GITHUB\_ID/HW-0 forked from 2016-09-Middlebury-Data-Science/HW-0" in blue. This allows you to distinguish between your copy of the repo and the master copy. You will be editing your copy only.
    3.  Click on the green button *Clone or download* and copy the contents of the `https` URL to your clipboard. This is your repo's web address.

2.  **Create an *RStudio Project* based on this repo**: RStudio Projects are a useful way to compartmentalize different projects you are working on. You will copy the `HW-0` repo from GitHub to a local copy on your computer via an RStudio Project. From RStudio go to *File* -&gt; *New Project...* -&gt; *Version Control* -&gt; *Git* and
    1.  Paste the clipboard contents into Repository URL.
    2.  Type `HW-0` as the project directory name.
    3.  Select the project subdirectory you want this to be saved in. A new folder with all the above files should be created along with a `HW-0.Rproj` file. You can click on this file in the future to open this project.

3.  **Do your homework**: Open `HW-0.Rmd` in RStudio and follow instructions.
4.  **Push your changes to `HW-0.Rmd` to GitHub**: "Push" is GitHub lingo for "sync the online version of your repo with your local copy of the repo".
    -   Select the *Git* panel. You will see a list of all files that were modified.
    -   Click the checkbox next to `HW-0.Rmd` to select it for syncing with GitHub and click *Commit*. "Commit" is GitHub lingo for "prepare to sync", i.e. check if GitHub can accept these changes.
    -   Add a brief commit message describing your changes and click *Commit*. Typically this will be an informative message to yourself like "Updated file X" or "Reorganized documents folder" etc.
    -   Push your changes to GitHub:
        -   **Do this only the first time you push anything to GitHub**: Go to *Tools* -&gt; *Shell...* -&gt; type `git push` and follow instructions. You only need to do this once.
        -   **For all subsequent pushes**: Click the *Push* button.

5.  **Submit your homework via pull request**: A "pull request" is a "request to merge the changes in your forked repo with the master repo", in this case the original master copy of `HW-0`. It will notify the master repo owner, who can then inspect the proposed changes. This make collaboration on very large projects easy. We will, however, stop short of actually merging any changes into the master repo, and I will only look at your work.
    -   Go to your forked repo on GitHub and ensure that the files have updated.
    -   Click *New pull request*.
    -   Click *Create pull request*.
    -   In the title field type your name and leave a comment, then click *Create pull request*. I will get an email notification. Your homework will only be complete after I respond to your pull request.

Things to Keep in Mind
----------------------

1.  Once you've forked a copy of HW-X, you should only be looking at the GitHub page of
    -   your fork marked "YOUR\_GITHUB\_ID/HW-X forked from 2016-09-Middlebury-Data-Science/HW-X" in blue on the top right
    -   and not the original master repo marked "2016-09-Middlebury-Data-Science/HW-X".

2.  RStudio projects are self-contained meaning you can only push file changes to GitHub if you are currently working in that project. If you want to switch between projects, in the top right of RStudio you can toggle between projects by clicking on the arrow.
3.  This process is the same for anything you find on GitHub! For example, if you are following election news on Nate Silver's data journalism site [538](http://fivethirtyeight.com/), you can fork a copy of the data corresponding to many of their articles here <https://github.com/fivethirtyeight/data>
4.  This is not a class on GitHub and we'll only be using a small sliver of its functionality. If you want to learn more however, Jenny Bryan at UBC has written an excellent online book [Happy Git and GitHub for the useR](http://happygitwithr.com/).

Help! This Isn't Working!
-------------------------

I anticipate this not working for many of you the first time, hence this is just a practice HW-0. If you encounter issues, don't panic and come see me during office hours.
