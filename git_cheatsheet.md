# BASIC GIT COMMANDS CHEAT SHEET

## 1. git clone
**Purpose:** Copies an existing Git repository
**Syntax:** $git clone [repository]
**Options:**
	- -b, --branch <name>
		Clone specific branch
	- -o <name>, --origin <name>
		Instead of using the remote name origin to keep track of the upstream repository, use
		<name>.
**Example:** git clone http://github.com/<username>/<repository_name>.git'


## 2. git status
**Purpose:** Shows the current status of your project
**Syntax:** $git status
**Options:**
	- -s, --short
		Short format output
	- --long
		Long-format. This is the default.
**Example:** git status -s


## 3. git add
**Purpose:** Adds to the staging área the tracked changes in the specifiedx files (temporal)
**Syntax:** $git add [files/folders]
**Options:**
	- -A, --all
		Stage all changes across the entire Git repository
	- --ignore-errors
           If some files could not be added because of errors indexing them, do not abort the
           operation, but continue adding the others.

## 4. git commit
**Purpose:** Adds to the staging area the tracked changes in the specified files (permanent) with a
description
**Syntax:** $git commit -m "description"
**Options:**
	- -m <msg>. --message=<msg>
		Commit message
**Example:** git commit -m "message"


## 5. git push
**Purpose:** Uploads local repository with tracked changes to a remote (online) repository
**Syntax:** $git push
**Options:**
	- -d, --delete
		All listed refs are deleted from the remote repository. This is the same as prefixing
		all refs with a colon.


## 6. git log
**Purpose:** Shows the history of the commits and branches in your project
**Syntax:** $git log
