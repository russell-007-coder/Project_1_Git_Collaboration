Git merge

Merging is Git's way of putting a forked history back together again. The git merge command lets you take the independent lines of development created by git branch and integrate them into a single branch. Note that all of the commands presented below merge into the current branch.

Merge branches fixes and enhancements on top of the current branch, making an octopus merge:

Example

> $ git merge fixes enhancements

Merge branch obsolete into the current branch, using ours merge strategy:

> $ git merge -s ours obsolete
 Merge branch maint into the current branch, but do not make a new commit automatically:

> $ git merge --no-commit maint
