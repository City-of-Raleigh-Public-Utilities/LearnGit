#LearnGit
PUGIS Internal GitHub Training

##Make local copy and use repository
##*Step 0
Download GitHub Desktop at https://desktop.github.com/
##Step 1
Copy the git clone url from the right side of the project webpage. 
Start git shell, ```cd (directory)``` go to directory you want clone to and enter ```git clone ``` followed by the url just copied. This will put a copy of the project on local machine. 
If repository already existed use ```git pull``` to get updated documents.
![Clone repository](/screenshots/Clone.PNG "Clone Repo Url")

![Shell command](/screenshots/Shell.PNG "Clone to Local Directory")
##Sync your changes on repository with master
##Step 2
Change directory to working directory ```cd (directory)```
##Step 3
Create or edit files in your working directory and save edits
##Step 4
Add edits to repository locally (use specific file name or use " ." which is a wildcard for selecting everything in the directory)
```git add (filename)```
##Step 5
Adds commitment comments to repository before upload
```git commit -m "(a few words of comment, double-quoted)"```
##Step 6
Pushes doc to master repository
```git push```

##In case of problems
You can use the ```git stash``` command to clear unwanted commits or other problems
