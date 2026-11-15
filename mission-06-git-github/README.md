Mission 6: Git and GitHub

1. Task / Objective

To understand Git and GitHub, practise basic Git commands, create a new branch, and learn how Pull Requests are created and merged.

 2. Work Completed

TASK 6.1: Git Basics

| Git Operation | Command | Purpose |
|---|---|---|
| Initialise repository | `git init` | Creates a Git repository |
| Check status | `git status` | Displays modified and staged files |
| Stage changes | `git add README.md` | Adds selected changes to staging |
| Commit changes | `git commit -m "message"` | Saves a snapshot of staged changes |
| View history | `git log --oneline` | Displays recent commits |

Difference between staging and committing:

Staging selects the changes that will be included in the next commit. Committing saves those staged changes in the repository's version history.

 TASK 6.2: Branching

Created a new branch named `update-about`.

Commands used:
```bash
git switch -c update-about
git add README.md
git commit -m "Add my learning section"
git push -u origin update-about
```

TASK 6.3: Pull Request

- Opened the GitHub repository.
- Compared the `update-about` branch with the `main` branch.
- Created a Pull Request.
- Added a description explaining the README changes.
- Reviewed the changes.
- Merged the Pull Request successfully.

TASK 6.4: Git Commands Reference

| Git Command | Purpose |
|---|---|
| `git init` | Initialises a Git repository |
| `git status` | Shows the current repository status |
| `git add` | Stages changes |
| `git commit` | Saves staged changes in Git history |
| `git log` | Displays commit history |
| `git branch` | Lists or creates branches |
| `git switch` | Switches to another branch |
| `git push` | Publishes local commits to a remote repository |
| `git pull` | Retrieves and integrates remote changes |

3. Commands / Tools Used

- Git
- GitHub
- `git init`
- `git status`
- `git add`
- `git commit`
- `git log`
- `git branch`
- `git switch`
- `git push`
- `git pull`

4. My Understanding

Git is a version control system that tracks changes in project files. GitHub provides an online platform to host Git repositories and collaborate.

Branches help developers work on separate features or changes. Pull Requests allow changes to be reviewed before they are merged into the main branch.

5. Difficulties Faced

Understanding the difference between the base branch and the compare branch while creating a Pull Request.

6. How I Resolved Them

I understood that the base branch is the branch receiving the changes, while the compare branch contains the changes being proposed. Therefore, for this mission, `main` is the base branch and `update-about` is the compare branch.

I also learned that creating a branch locally does not automatically publish it online. Running `git push -u origin update-about` uploads the branch to GitHub.

7. Evidence / Files

- Git command notes
- Updated root `README.md`
- `update-about` branch
- Pull Request link and status
- Relevant commit history
 8. Commit Details

Commit message: `Complete Git and GitHub collaboration mission`

