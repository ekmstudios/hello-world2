# Git

## What is Git?
- Version control
- Time machine
- check points (commits)
- Multiverse (branches)
- Synchronize (merging)

## What do I need?

- Install git

## Check settings

Once git is installed, run the following to check current settings:

- `git config --global user.name`
- `git config --global user.email` 

Initialize a folder for git

- In your terminal, navigate to the folder you want
- Run `git init`. This will create an invisible git folder
- To see the folder, run `ls -la`
- Then change directories into the git folder `cd .git`
- Then run `ls -la` again to display all the files in the .git folder.

Return to the main folder of your project.
- Run `cd ..`

Clear your terminal with the `clear` command.


## Staging Files

- `git add FILENAME`  
- `git add --all` adds all files in the project
- `git add -A` also adds all files in the project
- `git add .`  also adds all files in the directory
- `git commit -m "First Commit"

- `git log` displays a log output of your commits


## Git Environments

- Working
- Staging
- Commit

File States
- Tracked
- Untracked

Tracked Files
- Unmodified
- Modified
- Staged

Viewing Status
- `git status`


## Restoring Files
`git restore README.md`
`git restore .`
`git checkout .`



## Why GitHub?
- Cloud Repository
- Collaborative Development
- Project Management

## working with GitHub
- set up remote
- Push
- Fetch/Pull

