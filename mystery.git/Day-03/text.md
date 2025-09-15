Working Area:
------------

--> After this create a files in git using the Linux commands.

command:
--------

touch / cat/ vim -----> use to create the file.

Ex:-

--> touch f1
--> cat > f1 -->then enter the data and press ctr + d to get back from terminal in normal user.
--> vi f1 ---> go to insert mode (press i) ---> add data --> press :wq!(w-->save, q-->quit)---> to get a out from vi editor.

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

-- To check the installed version                      -----> git --version.
-- Clone a remote repository to local machine          -----> git clone <copy the https-link>
-- To check the status of a file                       -----> git status.
-- To check the commit history                         -----> git log 
-- To display the commit history of previous 3 commits -----> git log -3
-- To display the commit history in one-line           -----> git log ---oneline.
-- To see the changes in branches                      -----> git diff.
-- Removing a file from git                            -----> git rm filename.
-- Renaming a file                                     -----> mv old-name new-name.
-- Moving a file from one location to another location -----> mv source of file destination of file.
