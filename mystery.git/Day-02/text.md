Git Configuration:
------------------
Note:

	Open Git bash---> move to cd Documents/ --> create a directory using mkdir directory-name/ --> cd directory-name/---> then follow below steps.

Step-1:
-------

	Initialize the git working repository.
	
command:
--------
	git init


Step-2:
-------

		Before this we need  to create a GitHub account.
		
		--> create a Repository and keep it public and add a readme file-->u fill find button called code click on the code button-----> u fill find a HTTPS & SSH -----> Move to SSH and copy the key.
		-->Creating a alias name to the GitHub to push the repo's.
	
command:
--------
	git remote add alias-name and copy ssh-key from GitHub and paste.



Step-3:-
	Configure the user-name & email.

command:
--------
	git config --global user.name="user-name",
	git config --global user. Mail="user-mail"


Step-4:
-------
	Generate a key to connect the local repo with remote repo and for displaying the pull request in remote repo inside the files & Directories.
Command:
-------
	shh-keygen
	After this type enter 4 times---> It will generate two keys --->public and private ---> we need to get public key ---> using cd ~/.ssh/id_rsa.pub ()(or) cat id-number.--> copy the key and move to GitHub--> Go to ur Profile-->Setting--> select ssh and GPG keys--> select new ssh key--> paste the key.



Step-5:
-------
	To Check the alias name in git.
Command:
-------
	git remote -v



Step -6:
--------
	To check the list of user-name & mail.
command:
--------
	git config --global --list
