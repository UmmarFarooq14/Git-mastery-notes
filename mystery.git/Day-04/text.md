Git Reset Concept:
-----------------

Scenario:
---------
	If you have accidentally staged a file (moved it from the Working Directory to the Staging Area) and your developer asks you to keep it only in the Working Directory (un-staged), you can use the following command:

Command:
--------
	git reset filename ------->for a single-file.
	git reset          -------->for all the files.
	git restore --staged filename ------>without modifying a content in file.



Git revert Concept:
-------------------

Scenario:
---------
	Imagine you are working on a project with your team, and someone pushed a commit that introduced a bug in production. Instead of deleting the commit (which would rewrite history), your team decides to safely undo that commit while keeping the history clean and traceable.

command:
--------
	git log --oneline
	git revert <commit-id>.

Note:-
------
	-->In git revert if the file is a new file then file and inside the content and also file/directory will be deleted .
	-->In git revert if the file is a modified file then updated content will be deleted and file remains same.


Note:-
----
	-->We want to see which files are prepared and ready to be saved in the next commit.
command:
--------
	git show --pretty="" --name-only commit-id.
 
	-->This command will display the names of files in committing stage.

