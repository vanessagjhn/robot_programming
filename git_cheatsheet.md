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
**Purpose:** Adds to the staging área the tracked changes in the specifiedx files (temporal)
**Syntax:** $git add [files/folders]
**Options:**
	- '-A' / '--all' : Stage all changes across the entire Git repository


## 4. git commit
**Purpose:** Adds to the staging area the tracked changes in the specified files (permanent) with a description
**Syntax:** $git commit -m "description"
**Options:**
	- '-m <msg>' : Commit message
**Example:** git commit -m "message"


## 5. git push
**Purpose:** Uploads local repository with tracked changes to a remote (online) repository
**Syntax:** $git push
**Options:**
	- 'origin <branch> : Push to a specific remote branch
**Example:** git push origin branch


## 6. git log
**Purpose:** Shows the history of the commits and branches in your project
**Syntax:** $git log
