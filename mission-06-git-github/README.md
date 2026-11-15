TASK 6.1:
-->Git operation	|Command	|Purpose
1. Initialise repository	|git init	|Creates a Git repository
2. Check status	|git status	|Displays modified and staged files
3. Stage changes	|git add |README.md	Adds selected changes to staging
4. Commit changes	|git commit -m "message"	|Saves a snapshot of staged changes
5. View history	|git log --oneline	|Displays recent commits
-->Difference between staging and committing:

Staging selects the changes that will be included in the next commit. Committing saves those staged changes in the repository's version history.

TASK 6.2:
Created a new branch named update-about.

-->Commands used:
git switch -c update-about
-->Then used:
git add README.md
git commit -m "Add my learning section"
git push -u origin update-about