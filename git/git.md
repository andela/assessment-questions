##Git Assessment Questions

_The correct answers are highlighted in **bold**, or indicated_

1. For a gitignore file, what will be the pattern for ignoring all files with extension `.ogg` in the whole project
	- `*.ogg` (correct)
	- `/**/*.ogg` (correct)
	- `!*.ogg`
	- `*.*`


2. If you have staged a file say `example.py` ready for commit but you wish to unstage it, which command will you use.
	- `git remove example.py`
	- `git checkout example.py`
	- `git checkout -- example.py`
	- `git reset HEAD example.py` (correct)


3. Which of the following phrases in a commit message will close `issue 54`. (_Using 
	GitHub issue tracker_)
	- "...close issue 54"
	- **"...close #54"**
	- "...close issue #54"
	- "...closes issue #54"


4. What does `git log -2` do?
	- It's not a valid git command
	- Limits the length of each git log to 2 lines
	- **Gives the last 2 git entries**
	- Gives the git log for the last 2 days


5. If you wish to overwrite the previous git commit with a new one, which command will you use?
	- `git commit --overwrite`
	- `git commit --amend` (correct)
	- `git commit --reset`


6. Often, when you’ve been working on part of your project, things are in a messy state and you want to switch branches for a bit to work on something else. The problem is, you don’t want to do a commit of half-done work just so you can get back to this point later. Which command do you use to save this unfinished state of your project?
	- `git commit --temporary`
	- `git stash` (correct)
	- `git stash apply`
	- `git commit --stash`


7. What does `git branch -m br1 br2` do?
	- Moves from branch br1 to br2
	- Moves from branch br2 to br1
	- **Renames branch br1 to br2**
	- Renames branch br2 to br1


8. While switched on the `master` branch, which command will be used to merge a branch named `hotfix` with the `master` branch?
	- `git merge master/hotfix`
	- `git merge master hotfix`
	- `git merge hotfix` (correct)
	- `git merge hotfix/master`


9. Which command will be used to delete a branch named `feature-12`?
	- `git branch delete feature-12`
	- `git branch -delete feature-12`
	- `git branch -d feature-12` (correct)
	- `git branch rm feature-12`


10. If you wish to download the changes from a remote (i.e. `origin/master`); without modifying your working directory yet, which command will you use?
	- `git pull --no-overwrite origin master`
	- `git pull origin master`
	- `git fetch --all`
	- `git fetch origin master` (correct)


11. You are working on a project with a colleague. She created a feature branch (feature/user-profile) and pushed it to the repository. What single command can you run to pull and create that remote branch locally?
	- `git pull --rebase origin feature/user-profile`
	- `git pull origin feature/user-profile`
	- `git checkout -b feature/user-profile origin feature/user-profile` (correct)


12. How do you undo a branch merge?
	- `git merge --undo`
	- `git merge --abort` (correct)
	- `git undo merge`
	- `git merge undo`


13. Other than `git merge`, which other command is used for integrating changes from one branch to another?
	- git join
	- **git rebase**
	- git checkout
	- git squash


14. Which of the following is not a Git Workflow?
	- Anarchy Workflow
	- Centralized Workflow
	- Integration-Manager Workflow
	- Dictator and Lieutenants Workflow

15. What's the name of scripts that run automatically every time a particular event occurs in a Git repository?
	- pre-commit scripts
	- Git bash
	- Git bang
	- **Git hooks**







