Check Version:		 git –version
Create directory:	mkdir 
Make local Ripository : 		mkdir
Initialize a local Git repository: 	git init
For creating File:	touch filename(Ex: Frist.text)
Check status or file info: 	git status
Add a file to the staging area: 	git add filename(Ex: Frist.text)
Check status or file info: 	git status
Set Email: 	git config --global user.email sajibcse28@gmail.com
Set name: git config --global user.anem "Sajib"
Then command 	:x 
View change:	git log
View changes (detailed):	git log –summary
Commit changes: 	git commit -m "[commit message]"
staging  all file: git add .
View single line commit: git log –oneline
View by commit Id:	git show id(Ex 1ee1630)
After staging view difference : git diff – staged
Difference between two commit : git diff id id(Ex 1ee1630 Ex 1ee1630)
Remove file from git directory: git rm filename(Ex Second.txt)
Unstage the file to current commit: git reset HEAD filename (Ex Second.txt) 
Back to coomit Id: 	git checkout id [file-name.txt]
Create a local copy of a remote repository:	git clone ssh://git@github.com/[username]/[repository-name].git [your repository link ] you can change your local repositoy name by change name
Push changes to remote repository (and remember the branch) : git push -u origin master
----
Then put username and password info
Branching
List branches (the asterisk denotes the current branch):	git branch
Create a new branch:	git branch [branch name]
Switch to a branch:	git checkout [branch name]
git merge [branch name]:	Merge a branch into the active branch
Create a new branch and switch to it:		git checkout -b anotherbranch

Fork
Go to home :	cd ~
Create a local copy of a remote repository:	git clone https://github.com/sajib28/git.git (link)
