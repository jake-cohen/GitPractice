#Git Cheatsheet
**Name:** Jake Cohen
**Date:** June 7, 2016

Connect the GitHub repo to the local repo (folder) to get them to communicate

First, make Git aware that you're working with a new repository.  
Navigate to the folder and type `git init` to initialize.

Then, go to GitHub and create a new repo with the same name as your local repo. From that repo in terminal, type `git remote add origin [URL of your remote repo]`

**Add** = makes git aware that you have a new file  
**Commit** = log the version of the file you've been working on.  
This happens on the local computer

git add [file] = adds the file to the local repo
but then just git commit (w/ no file name) = will pull up a new editor window to log changes.
OR git commit -m "[changes]" = this is the easier way to do it.

**Push** = sending the local changes up to GitHub
git push -u origin master

Once a file has been added, future changes can be made with:
git commit -am "[changes]"

-a "flags" the file (the equivalent of adding) so that you don't have to add separately

**Clone** = copying someone else's repo onto your computer.