# my-first-repo

* Description
This task explains the creating a folder and cloning a repository into local computer. We created  a file named hello_world.txt. It is staged and committed to local computer and pushed to github.

* Workflow

# Creating a folder
mkdir project1
# Change directory
cd project1
# Initializing a repo
git init
# Cloning a repo
git clone https://github.com/Pavani-30/my-first-repo
# Change directory
cd my-first-repo
# Creating a file
touch hello_world.txt
# Staging a file
git add hello_world.txt
# Committing
git commit -m "Commit my first file"
# Push to github
git push -u origin main
