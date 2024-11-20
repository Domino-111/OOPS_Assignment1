## Questions:

1.	List three major version control software for software engineering.
	- Git
	- Mercurial
	- Apache Subversion
	
2.	What are the main advantages to using Git in your software development, and how is it useful for game developers.
	
	The main advantages for using Git are:
	a) Being able to upload and download new changes to any project at will
	b) Creating branches for testing of individual code without interferring with the main code
	c) Recall changes in the history i.e. nothing is deleted forever, everything can be recovered
	
3.	Define the following terms in relation to Git. Branch, Pull, Push, repository, working copy, merge
	
	- Branch: A branch is a section of the repository with its own changes and history that doesn't affect other branches
	- Pull: It means to download the latest version of a repository and branch
	- Push: It means to upload changes made to a branch in a repository so others may 'Pull' the changes made
	- Repository: Essentially acting as the file where everything is saved and kept
	- Working Copy: It's multiple files with the subdirectory '.git'
	- Merge: To merge is to combine branches into one another
	
	
4.	If you are working at a company, which of their policies and procedures might relate to using version control systems such as Git.
	- It would fall under the ICT Standard Operating Environment or Data Analysis policies and procedures
	
5.	Merge conflicts can occur while using git. List merge tools or diff tools you can use to help you merge and deal with conflicts.
	- 'git mergetool' is a tool used to help with merge conflicts, it is versatile being able to resolve issues with every file that has a conflict (skipping files without a conflict) or target specific files to resolve.
	- Visual Studio is used to help with merge conflicts as it allows users to view the code and identify where the conflict is
	- 'git status' helps with conflicts by identifying and alerting about conflicts
	- 'git diff' helps find differences between states of a repository & files
	
6.	In a merged source code file, how does Git let you know there is a conflict?
	- The status command will identify any conflict issues
	
7.	What are the steps you can take to resolve Git conflicts?
	1. Open the file and make any necessary changes
	1. After editing, use the git add a command to stage the new merged content
	1. Create a new commit
	1. Git will create a new merge commit to finalize the merge
	
8.	What does git revert do, and how can you use it?
	- git revert undoes the latest commit without deleting the changes of that commit, the revert will create a new commit having inversed the changes specified. This is useful as you can safely go back a commit without fully removing the previous changes in case you want to use them again.
	
9.	What does git reset do, and how can you use it?
	- git reset deletes all the commits after a specific one and sets you back there starting the commit chain again. This is useful as you can use it to remove all unecessary commits that were made and keep the relevant ones, i.e. removing commits where grammar was changed to make way for a commit containg new lines of code
	
10.	What is the difference between git revert and git reset?
	- Revert takes you back to a commit without removing the changes of the latest commit while reset deletes all the commits & changes after a specific commit
	
11.	True or False: It is okay to commit broken code to the main branch.
	- False
	
12.	True or False: You should commit related changes. For example, fixing two different bugs should produce two separate commits.
	- True
	
13.	Describe what is DevOps, how is it useful for game developers?
	- DevOps is a methodology used by IT and software developers, it's a system combining development (Dev) and operations (Ops) to create an efficient, fast and secure set processes. DevOps is useful for game developers cause it simplifies and streamlines the game development process and gives an end-to-end view of the project
	
14.	List what tools can be used with DevOps. Give a brief description of each one. (at least 3)
	a) Git: A communal program used to share code and files quickly allowing any authorised persons to add, remove or edit
	b) Docker: One of the most widely used tools to deliver software in packages called containers, it’s pretty simple to use with a vast ecosystem of users
	c) Ansible: A flexible and powerful tool to automate configuration tasks and infrastructure management, it can work with cloud and on-premises resources and has become one of the favorite tools of IT operators
	
15.	What is CI/CD and how can it be used to automate the game development process?
	-  CI/CD stands for continuous integration and continuous delivery/deployment, it aims to streamline and accelerate the software development lifecycle. CI/CD automates the manual human intervention traditionally needed to get new code from a commit into production, downtime is minimised and code releases happen faster. With the ability to more quickly integrate updates and changes to code user feedback can be incorporated more frequently and effectively.