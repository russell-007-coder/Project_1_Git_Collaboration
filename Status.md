git status shows the current state of your Git working directory and staging area.

What Does git status Do?
When in doubt, run git status. This is always a good idea. The git status command only outputs information, it won't modify commits or changes in your local repository.

A useful feature of git status is that it will provide helpful information depending on your current situation. In general, you can count on it to tell you:

Where HEAD is pointing, whether that is a branch or a commit (this is where you are "checked out" to)
If you have any changed files in your current directory that have not yet been committed
If changed files are staged or not
If your current local branch is linked to a remote branch, then git status will tell you if your local branch is behind or ahead by any commits
During merge conflicts, git status will also tell you exactly which files are the source of the conflict.

How to Use git status
Common usages and options for git status
git status: Most often used in its default form, this shows a good base of information
git status -s: Give output in short format
git status -v: Shows more "verbose" detail including the textual changes of any uncommitted files
