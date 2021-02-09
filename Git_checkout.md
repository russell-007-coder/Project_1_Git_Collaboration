Git Checkout: The git checkout command lets you navigate between the branches created by git branch . Checking out a branch updates the files in the working directory to match the version stored in that branch, and it tells Git to record all new commits on that branch.

Example:

The following sequence checks out the master branch, reverts the Makefile to two revisions back, deletes hello.c by mistake, and gets it back from the index.

> $ git checkout master             (1)

> $ git checkout master~2 Makefile  (2)

> $ rm -f hello.c

> $ git checkout hello.c            (3)

switch branch

take a file out of another commit

restore hello.c from the index

If you want to check out all C source files out of the index, you can say

> $ git checkout -- '*.c'

the quotes around *.c. The file hello.c will also be checked out, even though it is no longer in the working tree, because the file globbing is used to match entries in the index (not in the working tree by the shell).

If you have an unfortunate branch that is named hello.c, this step would be confused as an instruction to switch to that branch. You should instead write:

> $ git checkout -- hello.c

