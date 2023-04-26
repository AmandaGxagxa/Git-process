# Git-process
Version control software keeps track of every modification to the code in a special kind of database.

## On your github, go to the plus sign on your top right
- create a repository use the same name you did on your project folder.

## In you terminal

``` touch README.md ```
### Initialise your git in your folder
``` git init ```

### The git add command adds a change in the working directory to the staging area
- git add doesn't really affect the repository in any significant way—changes are not actually recorded until you run git commit.

``` git add . ```

### The git commit used to create a snapshot of the staged changes along a timeline of a Git projects history:

``` git commit -m "first commit" ```

### The git remote add is used to add a new remote:

``` git remote add origin git@github.com:alexpchin/<reponame>.git ```

### git push will push your code to the master branch of the remote repository defined with origin and -u let you point your current local branch to the remote master branch:
  
``` git push -u origin master ```
