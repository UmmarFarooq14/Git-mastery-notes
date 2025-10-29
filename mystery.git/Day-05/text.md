How to delete a untracked files in git:
---------------------------------------
Scenario:
---------
    --> You are working on a project, and over time you’ve created multiple temporary or test files (e.g., .log, .tmp, build files) that are not tracked by Git. These files clutter your working directory, and your manager asks you to clean them up to maintain a tidy repository.


To delete untracked files we will use two commands:
------------------------------------------------------

    1) git clean -n ----> It will display the all files what are all  going to delete.
    2) git clean -f ----> It will delete the files in untracked area.



Changing a repository from Public to Private:
---------------------------------------------
Scenario:
---------

    --> You have a public repository on GitHub that contains some sensitive code or internal project files. Your manager has asked you to make it private so that only authorized team members can access it.

In CLI:
-------
Steps:
------

    1) Navigate to Repository u want to change.
    2) gh repo edit <owner>/<repo> --visibility private.
    3) gh repo view --json name, visibility.


In GUI:
------

    Go to GitHub---->open the repository u want to change---->go to setting----> scroll down bottom ---->select change visibility to private.
