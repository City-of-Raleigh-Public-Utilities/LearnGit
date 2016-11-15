#LearnGit
PUGIS Internal GitHub Training

##Step 0
Download GitHub Desktop at https://desktop.github.com/
##Step 1
Copy the git clone url from the right side of the project webpage. Start git shell, ```cd (directory)``` go to directory you want clone to and enter ```git clone ``` followed by the url just copied. This will put a copy of the project on local machine. If repository already existed use ```git pull``` to get updated documents.
![Clone repository](/screenshots/Clone.PNG =200x120 "Clone Repo Url")

![Shell command](/screenshots/Shell.PNG =200x120 "Clone to Local Directory")
##Step 2
Change directory to working directory ```cd (directory)```
##Step 3
Create or edit files in your working directory
##Step 4
Add edits to file locally (use specific file name or use " ." which is a wildcard for selecting everything in the directory)
```git add (filename)```
##Step 5
Adds comments to file before upload
```git commit -m (a few words of comment, double-quoted)```
##Step 6
Pushes doc to default
```git push```

##In case of problems
You can use the ```git stash``` command to clear unwanted commits or other problems

[To the beginning](##Step 0)
