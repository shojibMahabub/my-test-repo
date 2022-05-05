# Dev requirements
  - create a separate branch
  - create file main.js
  - create file .env.local
  - create file .env.development
  - create file .env.production
  - add .gitignore
  - ignore .env.local file

# Client requirements
  - create an ecommerce website
  - create a backend API
  - create a frontend API

# Commands
  - initialize git repo in local - `git init`
  - connect remote repo with local repo - `git remote add origin <repo_url>`
  - clone a remote repo in local - `git clone <repo_url>`
  - add files to local repo - `git add <file>`
  - commit changes to local repo - `git commit -m "message"`
  - see status of local git repo - `git status`
  - git pull command - `git pull origin <branch-name>`
  - push changes to remote repo - `git push origin <branch name>`
  - pull all branches - `git fetch --all`
  - view git commit - `git log`
  
  - branching
    - create a new branch - `git checkout -b <branch name>`
    - switch to a branch - `git checkout <branch name>`
    - delete a branch - `git branch -d <branch name>`
    - rename a branch - `git branch -m <branch name>`
    - show branch name - `git branch`


  - merging and rebasing
    - rebase one branch code with another - `git rebase <branch name>`
    - merge one branch code with another - `git merge <branch name>`

# Branch guide
  - master branch == prodcution == user will use this version of code
  - stagigng branch == testing == SQ will test this version of code
  - dev branch == development == Developer will work on this version of code