# anna-university-workshop
learning how to use git entirely 
sudo apt-get install git ->to install git in terminal
git clone (copy the link in the github repository link) ->to clone the repository
git status -> to see the status of file created in system
git add file.txt ->to add the file from your system to staging area (to add all files->git add --all)
git commit -m "type the message here" ->to move the file from staging area to permanant staging area.
git push orgin master ->to move from staging area to github

CREATING BRANCH:
git branch -a ->to see what are the branches available
git checkout -b branch name ->to create branch

TO MERGE MASTER AND BRANCH:
go to master by->it checkout master
git merge mybranch->to merge them in staging place
git push origin master ->to reflect in remote place i.e.git

TO DELETE BRANCH:
 git branch -d mybranch
 git push origin --delete mybranch
 
 TO GET FILE FROM STAGING AREA TO LOCAL AREA:
 git reset HEAD file.txt
 
 TO REMOVE THE CHANGES MADE PREVIOUSLY:
 git checkout -- file.txt ->can be done only in local
 
 TO SWITCH FROM BRACH TO MASTER WHILE WORKING IN BRANCH:
 git stash ->to make the file into stash..Now you can checkout
 git stash pop ->to regain the work done.
