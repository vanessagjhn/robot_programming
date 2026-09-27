# BASIC GIT COMMANDS CHEAT SHEET

## 1. git clone
**Purpose:** Copies an existing Git repository
**Syntax:** $git clone [repository]
**Options:**
	- '--branch <name>' : Clone specific branch
**Example:** git clone http://github.com/<username>/<repository_name>.git'


## 2. git status
**Purpose:** Shows the current status of your project
**Syntax:** $git status
**Options:**
	- '-s' / '--short' : Short format output
**Example:** git status -s


## 3. git add
**$git add [files/folders]**
Adds to the staging área the tracked changes in the specifiedx files (temporal)

## 4. git commit
**$git commit -m "description"**
Adds to the staging area the tracked changes in the specified files (permanent) with a description

## 5. git push
**$git push**
Uploads local repository with tracked changes to a remote (online) repository

## 6. git log
**$git log**
Shows the history of the commits and branches in your project
