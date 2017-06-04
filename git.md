## Git Commands

### Working directory - Stage a file
`git add filename`

#### Working directory - Stage all files/changes

`git add .`

#### Working directory - Reset the changes in a file

`git checkout filename`

#### Working directory - Reset the changes in all tracked files

`git checkout .`

#### Working directory - Remove untracked files (interactive mode)

`git clean -i`

#### Working directory - Remove all untracked files
`git clean -f`

#### Staging - Unstage a staged file

`git reset filename`

#### Staging - Unstage all staged files

`git reset --hard`

#### Staging - Commit

`git commit -m "Message... (Use present tense)"`

### See the logs/commits

`git log
git log --oneline
git log --oneline --graph`

#### Git - set your user name and email address global.

`git config --global user.name "John Doe"
git config --global user.email johndoe@example.com`

#### Git - set your user name and email address per repository.

`git config user.name "John Doe"
git config user.email johndoe@example.com` 
