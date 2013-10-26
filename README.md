RecordExpense
=============
$ mkdir ~/RecordExpense
# Creates a directory for your project called "RecordExpense" in your user directory

cd ~/RecordExpense
# Changes the current working directory to your newly created directory

git init
# Sets up the necessary Git files
# Initialized empty Git repository in /Users/jrMonkey/RecordExpense/.git/

touch README
# Creates a file called "README" in your RecordExpense directory


git remote add origin https://github.com/jrMonkey/RecordExpense.git
# Creates a remote named "origin" pointing at your GitHub repository

$git add README
# Stages your README file, adding it to the list of files to be committed

git commit -m 'first commit'
# Commits your files, adding the message "RecordExpense commit"

git push origin master
# Sends your commits in the "master" branch to GitHub
