# GitHUB_Basics
i will write all the basic github commands here : <br>
git clone address of the repo. <br>
cd - change directory. <br>
Basic Git Commands

git init: Initializes a new Git repository in the current directory.

git init
git clone: Clones a repository from a remote server to your local machine.

git clone <repository_url>
git add: Adds files to the staging area.

git add <file>
git add . # Adds all modified and new files
git commit: Creates a new commit with changes in the staging area.

git commit -m "Commit message"
git status: Shows the current state of the repository.

git status
git diff: Shows the changes between the working directory and the staging area.

git diff
Branching and Merging

git branch: Lists all branches in the repository.

git branch
git branch : Creates a new branch.

git branch <branch-name>
git checkout: Switches to the specified branch.

git checkout <branch-name>
git merge: Merges the specified branch into the current branch.

git merge <branch>
Remote Repositories

git fetch: Retrieves changes from a remote repository.

git fetch
git pull: Fetches changes from the remote repository and merges them into the current branch.

git pull
git push: Pushes local commits to the remote repository.

git push
git remote: Lists all remote repositories.

git remote
git remote add: Adds a new remote repository.

git remote add <name> <url>
Managing History

git log: Displays the commit history of the current branch.

git log
git revert: Creates a new commit that undoes the changes introduced by a specified commit.

git revert <commit>
git reset: Moves the branch pointer to a specified commit.

git reset <commit>
Additional Commands

git stash: Stashes changes in the working directory.

git stash
git stash pop: Applies and removes the most recent stash.

git stash pop
git tag: Lists all tags in the repository.

git tag
git tag -a: Creates an annotated tag at the current commit with a custom message.

git tag -a <tag-name> -m "Message"