# Beginners Guide for Console Commands

## Useful Commands

* ls 	= List (content of directory)
* cd 	= change directory
* cd .. 	= eine ebene höher
* pwd  = shows current directory
* ctrl c = stop
* ls --help 	= Übersicht an options für dieses command
* mkdir 		= make directory
* mv 		= move or rename
* cp 		= copy
* rm 		= remove
* touch		= creates empty textfile
* wc		= word count (lines, words, characters)

>		Try these Commands yourself now!


Github Commands:

Command 	  Description
git status 	Show which files are modified locally or new
git diff 	  Show changes
git add 	  Add a file to change tracking and stage
git reset   HEAD 	Untrack a file or unstage
git checkout 	Undo changes to a file (before commit)

git commit 	Make changes permanent
git log 	  Show history of commits
git reset   HEAD~ 	Undo the last commit, retain changes in the working directory
git reset   HEAD~ --hard 	Undo the last commit, remove changes from the working directory

git pull 	  Fetch the commits from a remote repository and merge them with the current working directory (i.e. does a fetch and a merge in one)
git push  	Push the commits from the local repository to a remote repository
git fetch 	Fetch the commits from a remote repository into the local repository
git merge 	Merge the commits from the local repository with commits fetched from a remote repository (actually this works on branches; this will be explained in the git tutorial part 2)
