Working Area:
------------

		--> After this create a files in git using the Linux commands.

command:
--------

		--> touch / cat/ vim -----> use to create the file.

Ex:-
----

1) touch f1
2)  cat > f1 -->then enter the data and press ctr + d to get back from terminal in normal user.
3) vi f1 ---> go to insert mode (press i) ---> add data --> press :wq!(w-->save, q-->quit)---> to get a out from vi editor.

--> After creating a file u need a push file from working area to staging area using a command "git add filename"(for a single file).

Staging Area:
------------
	-->It is like a giving a save-point to file what does it represents with a clear message.

Local Repo:
-----------
	-->Local means the place where we can make the changes and track the code.

Remote Repo:
------------
	-->Remote it is a place where we can store the source code.



Git Work Flows:
---------------

--> Working Area(Untracked Files)-------------> Staging Area---------------> Local Repo---------------> Remote Repo 
                               git add                    git commit                   git push

Git Basic Commands:
-------------------

1) To check the installed version                      -----> git --version.
2) Clone a remote repository to local machine          -----> git clone <copy the https-link>
3) To check the status of a file                       -----> git status.
4) To check the commit history                         -----> git log 
5) To display the commit history of previous 3 commits -----> git log -3
6) To display the commit history in one-line           -----> git log ---oneline.
7) To see the changes in branches                      -----> git diff.
8) Removing a file from git                            -----> git rm filename.
9) Renaming a file                                     -----> mv old-name new-name.
10) Moving a file from one location to another location -----> mv source of file destination of file.
