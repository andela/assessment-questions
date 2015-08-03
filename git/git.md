##Git Assessment Questions

_The correct answers are highlighted in **bold**, or indicated_

1. For a gitignore file, what will be the pattern for ignoring all files with extension `.ogg` in the whole project
	- `*.ogg`
	- `/**/*.ogg` (correct)
	- `!*.ogg`
	- `*.*`


2. If you have staged a file say `example.py` ready for commit but you wish to unstage it, which command will you use.
	- `git remove example.py`
	- `git checkout example.py`
	- `git checkout -- example.py`
	- `git reset HEAD example.py` (correct)


3. Which of the following is not recommended for a good commit message
	- Limit the subject line to 50 characters
	- Separate subject from the body with a blank line
	- Use the body to explain what and why vs. how
	- **Keep it brief, less than 10 words**

4. What does `git log -2` do?
	- It's not a valid git command
	- Limits the length of each git log to 2 lines
	- **Gives the last 2 git entries**
	- Gives the git log for the last 2 days


5. If you wish to overwrite the previous git commit with a new one, which command will you use?
	- `git commit --overwrite`
	- `git commit --ammend` (correct)
	- `git commit --reset`


