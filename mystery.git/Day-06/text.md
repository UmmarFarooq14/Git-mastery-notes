Pushing Modified Files Without Using git add:
---------------------------------------------

Scenario:
--------

	You are working on a feature and have made changes to several already tracked files (files that were added to Git in previous commits).Your team lead asks you to quickly commit these changes with a clear message, without running git add separately for each file.


Command:
--------
	git commit -am "commit message."





Difference between git add. & git add *:
----------------------------------------

git add . :
-----------
--> It will push all the files/directories to staging area including hidden files/directories.

git add * :
-----------
--> It will push all the files/directories to staging area except hidden files/directories.
 

.gitignore:
-----------
	The .gitignore file tells Git to ignore specified files or directories so they are not tracked or pushed to the remote repository. If a file has already been pushed to the remote, adding it to .gitignore will not remove it from the remote. It only prevents new changes to ignored files from being tracked. Other files in the repository are not affected.

Note:-
-----
1) .gitignore prevents tracking of files you don't want in version control.
2) If a file is already in repo, .gitignore won't remove it, you need git rm --cached.
3) It won't affect the other files, it only applies to the files matching pattern inside the .gitignore.


How to push all the files/directories into all the branches:
-----------------------------------------------------------
command:
-------
git push alias-name 

