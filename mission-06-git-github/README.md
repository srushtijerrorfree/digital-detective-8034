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

TASK 6.3:
-- Opened the GitHub repository.

-- Compared the update-about branch with the main branch.

-- Created a Pull Request.

-- Added a description explaining the README changes.

-- Reviewed the changes.

-- Merged succesfully

TASK 6.4:
-->Git Command |Purpose
1. git init |Initialises a Git repository.
2. git status |Shows the current repository status.
3. git add |Stages changes.
4. git commit |Saves staged changes in Git history.
5. git log |Displays commit history.
6. git branch |Lists or creates branches.
7. git switch |Switches to another branch.
8. git push |Publishes local commits to a remote repository.
9. git pull |Retrieves and integrates remote changes.



3. Commands / Tools Used

-- Git

-- GitHub

-- git init

-- git status

-- git add

-- git commit

-- git log

-- git branch

-- git switch

-- git push

-- git pull

4. My Understanding

Git is a version control system that tracks changes in project files. GitHub provides an online platform to host Git repositories and collaborate.

Branches help developers work on separate features or changes. Pull Requests allow changes to be reviewed before they are merged into the main branch.

5. Difficulties Faced and How I Resolved Them

Difficulty: Understanding the difference between the base branch and the compare branch while creating a Pull Request.

Resolution: I understood that the base branch is the branch receiving the changes, while the compare branch contains the changes being proposed. Therefore, for this mission, main is the base branch and update-about is the compare branch.

Difficulty: Understanding why a newly created branch was not initially visible on GitHub.

Resolution: I learned that creating a branch locally does not automatically publish it online. Running git push -u origin update-about uploads the branch to GitHub.

6. Evidence / Files

-- Git command notes

-- Updated root README.md

-- update-about branch

-- Pull Request link and status

-- Relevant commit history

