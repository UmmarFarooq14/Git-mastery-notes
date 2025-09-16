Concept of Branching:
---------------------


What is a Branch in Git:
-----------------------
	-->A branch is like a separate line of development in your project.

1)Think of it as a pointer to a specific commit.
2)It lets you work on new features, bug fixes, or experiments without affecting the main code.
3)When ready, you can merge your branch back into another branch (like main).

Why Use Branches:
-----------------

1)Isolate work: Work on a feature or bug independently.
2)Parallel development: Multiple people can work at the same time.
3)Safe experimentation: Test ideas without breaking the main project.
4)Organized workflow: Easier code reviews and CI/CD.


How Branches Work (Simple Flow):
--------------------------------

1)Start with a main branch (often main or master).
2)Create a new branch to work on something:
command:
---------
-->git branch branch-name.

How to switch one-branch to another branch:
-------------------------------------------
command:
-------
--> git checkout branch-name.
--> git switch branch-name.

Visual Example:
---------------

main ───●──●──●─────────────●
          \                 /
           feature-1 ──●──●─


To create a new-branch and switch it to created-branch:
-------------------------------------------------------
command:
--------
--> git checkout -b branch-name.

Related Commands to branches:
-----------------------------
--> To display remote branches                          -----> git branch -r.
--> To display all the branches                         -----> git branch -all.
--> To display the branch in local                      -----> git branch.
--> To delete a branch in local                         -----> git branch -d branch-name.
--> To delete a branch in remote repo                   -----> git push alias-name :branch-name.
--> To modify the name of the branch                    -----> git branch -m <old-name> <new-name>.
