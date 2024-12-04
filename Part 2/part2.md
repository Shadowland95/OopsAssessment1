1.	List three major version control software for software engineering.

1 Git \
2 Mercurial \
3 Svn

2.	What are the main advantages to using Git in your software development, and how is it useful for game developers.

You can send files of codes to Git and make a update/ or changes to the code you also you can make copys of the same file to work on they can even work offline 
and the history of changes will be preserved. Being able to also commint on what changes or fixes have been made can help.

3.	Define the following terms in relation to Git. Branch, Pull, Push, repository, working copy, merge

Branch: A sperate line of development that dverges from the main codebase. \
Pull: Downloading a copy of the code and/or file from the repostory \
Push: Uploading the updated code/file to GitHub followed by adding a commint of the changes/fixes have been made \
Repository: The Repository let's you search for a certain file that you may be looking for and hold all the commints and changes that have been made \
Working Copy: The current state of the files in your local directory that you're working on. It is the latest snapshot of the project files as they exist on your local machine \
Merge: The process of integrating changes from one branch into another, typically from a feature branch into the main branch 

4.	If you are working at a company, which of their policies and procedures might relate to using version control systems such as Git.

Branching Strategy: Some one that has control of creating, mergeing and deleting branches \
Commit Messages: Writing messages of meaningful and clear messages \
Code Review: Procedures for reviewing code changes before they are merged into the main branch. \
Release Management: Policies related to the deployment of code and how version control supports release cycles 

5.	Merge conflicts can occur while using git. List merge tools or diff tools you can use to help you merge and deal with conflicts. 

KDiff3: A diff and merge tool that shows differences between files and helps resolve conflicts \
Meld: A visual diff and merge tool for comparing files and directories \
Beyond Compare: A tool for comparing files and folders, with merging capabilities \
Araxis Merge: A commercial tool for comparing and merging files and folders 

6.	In a merged source code file, how does Git let you know there is a conflict? 

When the file fails to merge and files it will show some confilct markers to let you know where the problem is you will however need to resolve them manually 

7.	What are the steps you can take to resolve Git conflicts? 

Identify Conflicts: Open the conflicted files and look for conflict markers. \
Resolve Conflicts: Edit the files to resolve the differences between conflicting changes. \
Mark as Resolved: After editing, mark the conflicts as resolved by adding the files to the staging area with git add. \
Commit: Complete the merge by committing the resolved changes using git commit 

8.	What does git revert do, and how can you use it? 

Using git revert will create a new commit however it will undo the changes that was made i the previous commit. It does not alter the commit history but rather adds a new commit that reverses the effects of a specified commit 

9.	What does git reset do, and how can you use it? 

Function: git reset changes the current branch’s history and can modify the staging area and working directory. It can be used with different options (--soft, --mixed, --hard) to control how much is undone.\
Usage:\
--soft: Moves the branch pointer but leaves the working directory and staging area as is.\
--mixed: Moves the branch pointer and resets the staging area but keeps the working directory.\
--hard: Resets everything (branch pointer, staging area, and working directory).

10.	What is the difference between git revert and git reset?

git revert: Creates a new commit that reverses the changes of a previous commit. It is safe for undoing changes in shared branches.\
git reset: Alters the commit history and can discard changes from the staging area and working directory.\
It is useful for local changes and can be destructive if used improperly.

11.	True or False: It is okay to commit broken code to the main branch.

False

12.	True or False: You should commit related changes. For example, fixing two different bugs should produce two separate commits.

True

13.	Describe what is DevOps, how is it useful for game developers?

DevOps is a combination of both Development (Dev) and IT operation (Ops) to improve collaboration, efficency and speed of delivering software for game developers.

DevOps can:

Automate Builds: Set up continuous integration to automatically build and test games.

Streamline Deployment: Automate the deployment process to various environments (development, staging, production).

Improve Collaboration: Enhance communication and collaboration between development, QA, and operations teams.

14.	List what tools can be used with DevOps. Give a brief description of each one. (at least 3)

Jenkins: An open-source automation server used to build, deploy, and automate software projects. It supports continuous integration and delivery pipelines.\

Docker: A platform for containerizing applications, ensuring consistent environments across development, testing, and production.

Kubernetes:  An orchestration platform for managing containerized applications at scale, automating deployment, scaling, and operations.


15.	What is CI/CD and how can it be used to automate the game development process?

CI/CD stands for Continuous Integration and Continuous Deployment/Delivery:

Continuous Integration (CI): Automates the process of integrating code changes into a shared repository frequently, ensuring that new changes do not break existing functionality.\
Continuous Deployment/Delivery (CD): Automates the release of code changes to production or staging environments, ensuring that new features and fixes are delivered quickly and reliably.

For game development, CI/CD helps by:

Automating Builds: Regularly building the game to catch issues early.\
Running Automated Tests: Ensuring new code does not introduce bugs or regressions.\
Deploying Updates: Quickly rolling out updates or patches to players, improving the overall release process.
