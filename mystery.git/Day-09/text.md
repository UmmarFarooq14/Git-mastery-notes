Concept of git stash:
---------------------
           --> git stash is used to temporarily save your uncommitted changes (both staged and unstaged) so you can switch branches or work on something else without committing.

Why Use Stash:
-------------
           1) when you need to switch branches quickly without committing.
           2) When you want to save work in progress temporarily.
           3) keep your commit history clean.

Common Commands:
---------------
           ------------------------------------------------------------------------------
           | Command                | Description                                       |
           | ---------------------- | ------------------------------------------------- |
           | `git stash`            | Save your changes and clear working directory.    |
           | `git stash save "msg"` | Save with a message (optional in newer Git).      |
           | `git stash list`       | Show all saved stashes.                           |
           | `git stash apply`      | Apply the latest stash but keep it in stash list. |
           | `git stash pop`        | Apply the latest stash and remove it from list.   |
           | `git stash drop`       | Delete a specific stash.                          |
           | `git stash clear`      | Remove all stashes.                               |
           ------------------------------------------------------------------------------

Visual Idea:
-----------

           [ Working Directory with Changes ] 
                      |
                   git stash
                      v
           [ Changes saved in stash stack, directory clean ]
                      |
                   git stash pop
                      v
           [ Changes restored from stash stack ]




Concept of git pull, git fetch and git merge:
---------------------------------------------


Git fetch:
----------

            It Fetch the updated data from remote repository to local repository and it merge in local repository but doesn't change working directory or current branch.Think of it as checking for updates.

command:
-------
             git fetch origin.

Git merge:
----------
           Combines changes from one branch to another branch.We can use it after fetching or switching a branch.

command:
--------
             git merge origin/main.

Git pull:
---------
           A shortcut from git fetch + git merge in one command.It downloads new changes and immediately merges them into your current branch.

command:
--------
             git pull origin main.
