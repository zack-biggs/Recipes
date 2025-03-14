# Spring Git Workshop
## 3/14/2025 What I learened
I learned how to connect remote and local repositories. 
git status -> This will give us the status of the current repository. 
git add     -> This adds a file or a commit for tracking. 
git commit -> This makes a commit from what was added. You need to add a message.
git log       -> More information about the commits. It lists all commits made. 
git diff       -> Shows the difference between what was last checked in and what has changed in        the file.
git commit -m -> The -m option allows us to give a name for the commit

You always have to add files for committing before committing. Unsure how to un-add if needed. 
Adding process is basically deciding what all you want to be included in a certain commit before you do the commit. You can add and remove files from the staging area before the commit is made. Add basically adds files to the “staged for commit” status. 

git diff               -> This only looks at unstaged changes.
git diff –staged -> This will compare with the staged changes.

HEAD -> This is always the most recent commit. You can a step back from HEAD with ~# where # is a number of steps back. You use this with git diff to see changes further and further back. 

with git log you can specify the number of commits you want to view with -. You can also see a more condensed list by typing the -oneline option. 

You can also specify a hash (commit ID) that you want to compare with. Usually you only need the first 4 numbers or so. 

git restore -> This is what you use to undo unstaged changes. To restore to a specific commit you use the -s option followed by the commit hash (or some portion thereof). 

The powerpoint is available online for reference. 

Git does not track empty folders.

.gitignore files do need to be tracked.

SSH is considered more secure than HTTPS
