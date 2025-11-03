Concept of merge conflict:
--------------------------
    A merge conflict occurs in Git when one or more developers edit the same part of a file and Git cannot automatically determine which change is correct. This usually happens during a merge or rebase.

Resolve-Steps:
--------------
Step-1:Identify the conflict
----------------------------

    -->  Git will show a message and mark the conflicting file(s).
    -->  Open the file to see conflict markers like:

        <<<<<<< HEAD
        Your changes
        ===========

Other developer’s changes
>>>>>>> branch-name

Step-2: Discuss and decide
--------------------------


      Communicate with the other developer(s) to decide which changes to keep or how to combine them.

Step-3: Edit the file
----------------------

      Remove the conflict markers (<<<<<<<, =======, >>>>>>>) and keep the correct code.

Step-4: Save and exit the file
------------------------------

Step-5:Stage the resolved file
------------------------------
command:
------
    git add <file-name>

Step-6:Commit the resolution
----------------------------
command:
-------

git commit -m "Resolved merge conflict in <file-name>"

Step-7:Push the changes
command:
-------
git push origin <branch-name>
