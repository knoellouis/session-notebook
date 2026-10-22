LOCAL REPOSITORY

Initialize a Git repository - git init

Create .gitignore file - touch .gitignore

Add files to .gitignore - nano .gitignore (.DS_Store)

View content of .gitignore file - cat .gitignore

Check status - git status

Add changes - git add .gitignore (or git add . to add all files / changes)

Commit the changes - git commit -m "message about what was changed"

See the changes in one line - git log --oneline

Undo changes in a file before staging:

- git restore .gitignore(for example - this will restore the .gitignore to its previous state before its last changes)

Undo changes in a file after staging:
git restore --staged <file name>
