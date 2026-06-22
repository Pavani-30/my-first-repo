# my-first-repo

* Description
This project demonstrates the practical use of Git and GitHub for version control, collaboration, project management, automation, and deployment. The repository was created as part of a GitHub hands-on assessment to showcase essential workflows used in modern software development teams.

# Objective

The project covers the following GitHub concepts:

Repository creation and management
Cloning repositories to a local machine
Creating, staging, committing, and pushing files
Branch creation and feature development
Pull requests and code review workflows
GitHub Issues and Project Boards
GitHub Actions for Continuous Integration (CI)
Automated deployment using GitHub Actions
Forking and contributing to open-source projects
Git Submodules
GitHub Discussions
Versioning with Git Tags
Branch Protection Rules
Website hosting using GitHub Pages

# Workflow

* Creating a folder
  - mkdir project1
* Change directory
  - cd project1
* Initializing a repo
  - git init
* Cloning a repo
  - git clone https://github.com/Pavani-30/my-first-repo
* Change directory
  - cd my-first-repo
* Creating a file
  - touch hello_world.txt
* Staging a file
  - git add hello_world.txt
* Committing
  - git commit -m "Commit my first file"
* Push to github
  - git push -u origin main


# SECTION-1: Basic GitHub Operations

* Created a new GitHub repository named my-first-repo.  Added a README.md  file which explains the project.
* Cloned the repository to local machine using the terminal
git clone https://github.com/Pavani-30/my-first-repo.
* Listing the files- ls
* Create a file named hello_world.txt containing the text and staged and committed to git.
  touch hello_world.txt
  git add hello_world.txt
  git commit -m “First file”
* Push local commit to GitHub
git push -u origin main


# SECTION-2: Branching and Collaboration

* Created a new branch called add-logo and switch to that 
  git branch add-logo
  git switch add-logo
* Add a file named logo.png
  touch logo.png
  git add logo.png
  git commit -m “Image file”
  git push 
* Create a pull request from add-logo into main to download changes into main
  git pull
* Merge the pull request into main
  git switch main
  git merge add-logo



# SECTION-3: GitHub Issues and Project Management 

* Create an issue titled Fix broken links in README.
  An Issue is used to report, discuss, or track a task so that developers know there is a problem.
  Examples:
  1. Report a Bug
   Login button is not working
  2. Request a New Feature
   Add Dark Mode
* Create a GitHub Project board with columns such as To Do,In   Progress, and Done.
  To do- Work not started yet
  Progress- Work in progress
  Done- Completed work


# SECTION-4: GitHub Actions and Automation 

* Create a workflow file at .github/workflows/ci.yml that runs         automatically whenever code is pushed to main. 
* Push a change that triggers the workflow. 
  This workflow was created to understand the basics of GitHub Actions and Continuous Integration (CI). By automating this task, GitHub can automatically perform predefined actions whenever changes are pushed to the repository.


# SECTION-5:  Advanced GitHub Features

* Forked an open-source repository. Clone the fork locally. After
cloning, I created a new branch named update-readme to
make a small improvement.
* Creating a separate branch allows changes to be developed
safely without affecting the main branch.
* I added a Git submodule to my repository, committed the
changes, and pushed them to GitHub. A Git submodule is
used to include another Git repository inside a project while
keeping it as a separate repository.
* Enabled GitHub discussions using title Suggestions for new
features in a repo.


# SECTION-6: Best Practices and Versioning

* Created and pushed a Git tag named v1.0.0. A tag is a fixed
marker that points to a specific commit.
* It is usually used to mark releases or versions of a project.
* I configured branch protection rules on the main branch to
require at least one pull request review before any changes
can be merged. This ensures that all code changes are
reviewed by another team member before becoming part of
the main codebase


# BONUS ASSESSMENT

Created a repository named username.github.io. I created a
repository named username.github.io and added a simple HTML
page as the website's homepage. The repository was configured to
use GitHub Pages, which allows static websites to be hosted
directly from a GitHub repository


# Commands

* Checking the git version
git --version
* Giving credentials to git
git --config global user.name Pavani                     
git --config global user.email pavanigonthini@gmail.com
* Listing all the files and folders
ls  
* Creating a folder
mkdir project
* Changing directory
cd project
* Initializing a repo
git init
* Cloning the repo
git clone https://github.pavanigonthini.com
* Creating a file
touch index.html
* Checking status
git status
* Adding to staging area
git add
git add .
* Committing to local repo
git commit -m "version1"
* Checking the history of git
git log
git log --oneline
* Branching
git branch
git branch login
git checkout -b login
* Merging
git checkout main
git merge login
* Remote repo
git remote add origin https://github.pavanigonthini.com
git remote -v
* Pushing to GitHub
git push -u origin main
git push
* Pulling the changes
git pull
* Shows unstaged and staged files
git diff
git diff --staged
* Create and switch to branch
git checkout -b login
* Saves all uncommitted changes'
git stash
* Restore stashed changes
git stash pop
* Delete all uncommitted changes
git reset --hard HEAD
* Restoring file changes
git restore file
* Revert a commit
git revert sha
* Tag a release
git tag -a v1.0.0 -m "release"
