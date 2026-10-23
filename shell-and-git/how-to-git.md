## LOCAL REPOSITORY

Initialize a Git repository - git init

Create .gitignore file - touch .gitignore

Add content to .gitignore file - nano .gitignore (.DS_Store)

View content of .gitignore file - cat .gitignore

Check status - git status

Add changes - git add .gitignore (or git add . to add all files / changes)

Commit the changes - git commit -m "message about what was changed"

See the changes in one line - git log --oneline

Undo changes in a file before staging:

- git restore .gitignore(for example - this will restore the .gitignore to its previous state before its last changes)

Undo changes in a file after staging:
- git restore --staged <file name>

---

## REMOTE REPOSITORY

Open up github and create a new repository

In the terminal:

git remote add origin <ssh>

git remote -v

git add .

git commit -m 'with a meaningful message'

git push -u origin main (-u means upstream)

---

## GIT BRANCHES

Create a new branch - git switch -c 'feature new bla bla bla' (on this branch you can change your code and it will not directly affect the main/ master branch)

Check status - git status

Add the branch / changes - git add . 

Commit the branch / changes - git commit -m 'meassage'

Go back to the main branch - git switch main

If you want to switch to the previous branch you were on - git switch -

Create a new Repository on Github with the same name as your remote repository

Then connect the remote to the local (make sure you're on the main branch) - git remote add origin <ssh>

Check to see if its connected by running - git remote (you should see origin)

Set main branch - git branch-M main

Push your changes from local to remote - git push -u origin main

Switch to your branch - git switch <branch name>

Check status - git status

Push branch from local to remote - git push origin <branch name>

Get a list of branches - git branch

List all branches (local and remote) - git branch -a

Delete a branch - git branch -d <branch name>

---

## MERGING BRANCHES

Go to Github and click on Compare and pull request

You can give it a title and description (give a good one)

Review changes

Click Create Pull Request

A colleage usually confirms the merge request 

---

## PULL CHANGES TO LOCAL 

Go to your terminal and switch to main branch - git switch main

Pull the changes - git pull

ℹ️ Best practice is to delete the branch once it has been merged and pulled so that it keeps the git and Github environment clean

