
# Git-and-Gitlab-Practical
## Task
## 1. GitHub Tasks
### 1.1 Create two repositories on GitHub
### ~ Public
### ~ Private
### Public Repository
![](./img/public%20repo.png)
### Private Repository
![](./img/private%20repo.png)
## Subtask 2: Local Development
#### 2.Clone both repositories on your local machine using HTTPS.

Git clone:https://github.com/iampooja-jadhav/task-repo.git/Private-repo 

Git clone:https://github.com/iampooja-jadhav/public-repo.git/Public-repo

#### 3.In the private repository:
#### create a branch dev.
#### git checkout -b dev

~ Add a few files (e.g., index.html, readme.md) and make at least two commits.

## index.html
![](./img/index.png)

git add .

git commit -m "added file"

#### ~Push the dev branch on github
Git push -u origin dev

## Subtask 3: Collaboration Workflow
#### 4.On GitHub, create a Pull Request (PR) to merge dev into main.
![](./img/pull%20or%20merge.png)

## 2.: GitLab Tasks
### Subtask 4: GitLab Repository Setup
#### 
Create a private repository on GitLab.
![](./img/gitlab%20repo.png)

#### Clone it on your local machine using SSH (not HTTPS).
git clone   git@gitlab.com:jadhavpooja87970/test-repo-private.git

#### Create a simple project structure (e.g., src/app.py, docs/guide.md).
Src/app.py

![](./img/src.png)

Docs/guide.md

![](./img/docs.png)

## Subtask 5: Repository Mirroring
### Create a mirror setup:
#### mirror setting
![](./img/mirror%20.png)

#### Set the GitHub private repo as the mirror of your GitLab repo.
#### Push some changes to GitLab and verify if the changes reflect in GitHub automatically.
git add .

git commit -m  "added app.py and guide file"

git push -u origin main

## Final View of repo

## Github
![](./img/github.png)

## Gitlab

![](./img/gitlab.png)

### Key Tasks
#### GitHub (Part 1):
Create public + private repositories

Work with branches (dev → main)

Practice pull request workflow

Use HTTPS for cloning

### GitLab (Part 2):
Create private repository

Use SSH for cloning

Set up project structure

Configure mirroring from GitLab to GitHub.

### Conclusion
#### Learn to maintain synchronized development across two different Git platforms (GitHub and GitLab) while practicing proper version control and collaboration workflows.
#### This assignment focuses on key Git operations, branch management, pull request workflows, and cross-platform repository mirroring.

