# Useful Batch Files
## Remember to add folder to your PATH so you can use your files anywhere!!

## gitbat.bat
### Purpose: git add --all, git commit -m, git push all in one
* Usage: gitbat \<p1\> \<p2\>
* Parameter 1: commit message must be in quotes or will not parse correctly
* Parameter 2: name of branch
* Note: Second parameter is optional, will default to master if omitted, first parameter is mandatory

## setupgit.bat
### Purpose: initialize a git repository
* Usage: setupgit \<p1\>
* Parameter 1: name of repository \(no spaces\)
* Note: Should be pretty straightforward, make sure you are in the directory you want to create a new repo.  I think you may have to initialize a repository of the same name from github first, not tested yet

## rmgitbr.bat
### Purpose: delete a finished branch remotely and locally, then recreate the branch
* Usage: rmgitbr \<p1\>
* Parameter 1: name of branch \(no spaces\)
* Note: deletes branch then checks out and creates branch again.

# Useful Resources
* [Dos Tips](http://www.dostips.com/DtTutoFunctions.php)
* [Git Branching](http://stackoverflow.com/questions/2003505/how-to-delete-a-git-branch-both-locally-and-remotely)
* [Adding Repo From Command Line](https://help.github.com/articles/adding-an-existing-project-to-github-using-the-command-line/)
