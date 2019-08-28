Git Commands I tried
--------------------------- 
```sh
git config --global user.name "Your Name Here"
git config --global user.email "your_email@youremail.com"
```

** After Creating online Repository and local folder for the same, initializae the GIT ** 
```sh
git init
git status
git add Readme.txt
git commit -m “Add Readme.txt” aleternatively git commit -am “Add Readme.txt”
git remote add origin https://github.com/username/myproject.git
git remote -v
git push -u origin master
```
** Un track a file **
```sh
git rm --cached FILENAME
git rm -r --cached quickStart/dist  //here -r stand for recursive
```
** More commands **
https://help.github.com/articles/fetching-a-remote/
```sh
git clone
git fetch
git merge
git pull
```

Commands Summary @ https://confluence.atlassian.com/bitbucketserver/basic-git-commands-776639767.html
```sh
git branch //List all the branches in your repo, and also tell you what branch you're currently in
git checkout <branchname> //Switch from one branch to another
git checkout -b <branchname> //Create a new branch and switch to it

git fetch origin //origin is the remote name we configured
get merge origin/master //merge fetch changes to local branch master
git pull origin master // does both FETCH and MERGE
```

HOW DID I RESOLVE A CONFLICT
```sh
* git pull original master // this results in git showing a CONFLICT
* git diff //Show conflict on terminal
* Go to Editor, open file which has conflicts; Save file
* git add [filenameWithConflict]
* git commit -am "message"
* git status // to see changes
* git push origin master
```

Git Resources i referred for learning.
---------------------
http://readwrite.com/2013/09/30/understanding-github-a-journey-for-beginners-part-1/
https://guides.github.com/activities/hello-world/

VI commands basic
----------------
https://www.tutorialspoint.com/unix/unix-vi-editor.htm
```sh
i //start edit mode
Esc Esc //go to commands prompt
ZZ //Save and Exit Vi
:q // just exit
```


