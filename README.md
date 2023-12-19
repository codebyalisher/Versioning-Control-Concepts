# Versioning-Control-Concepts

Concept about The Version Control:
What is the Version Control?
It is the system that is used to track and maintain the changes during the development remotely among the developers and other team members.

✒️
The Command line
What are Unix commands?
Using Bash on Windows
Change directories and list contents
Creating and moving directories and files 
Pipes
Redirection 
Grep 
✒️
What is Git and GitHub?
Creating and cloning a repository
How Git works
Add and commit
Branches 
Remote vs. local 
Push and pull 
Example workflow
HEAD
Diff commands
Blame
Git commands:
1.	git init:
•	Initializes a new Git repository in the current directory.
2.	git clone <repository_url>:
•	Creates a copy of a remote repository on your local machine.
3.	git add <file(s) or directory>:
•	Stages changes for commit.
4.	git commit -m "<commit_message>":
•	Records changes made to the repository with a descriptive message.
5.	git status:
•	Shows the status of changes as untracked, modified, or staged.
6.	git log:
•	Displays a chronological log of commits.
7.	git pull:
•	Fetches changes from a remote repository and merges them into the current branch.
8.	git push:
•	Sends local commits to a remote repository.
9.	git branch:
•	Lists all branches in the repository.
10.	git branch <branch_name>:
•	Creates a new branch.
11.	git checkout <branch_name>:
•	Switches to a different branch.
12.	git merge <branch_name>:
•	Combines changes from a specified branch into the current branch.
13.	git remote -v:
•	Lists remote repositories associated with the current repository.
14.	git fetch:
•	Downloads changes from a remote repository but does not merge them.
15.	git diff:
•	Shows the differences between the working directory and the staging area.
16.	git reset <file(s)>:
•	Unstages changes.
17.	git reset --hard HEAD:
•	Discards all changes in the working directory and staging area.
18.	git pull origin <branch_name>:
•	Pulls changes from a specific remote branch and merges them into the current branch.
19.	git push origin --delete <branch_name>:
•	Deletes a remote branch.
20.	git tag -a <tag_name> -m "<tag_message>":
•	Creates an annotated tag for a specific commit.
21-Git blame filename/branchname->it tells the complete detail about the How,Who and when.
