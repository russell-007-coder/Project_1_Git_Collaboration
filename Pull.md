Git Pull: The git pull command is used to fetch and download content from a remote repository and immediately update the local repository to match that content. Once the content is downloaded, git pull will enter a merge workflow. A new merge commit will be-created and HEAD updated to point at the new commit. 

Example

Update the remote-tracking branches for the repository you cloned from, then merge one of them into your current branch:

> $ git pull

> $ git pull origin

Normally the branch merged in is the HEAD of the remote repository, but the choice is determined by the branch.<name>.remote and branch.<name>.merge options; see git-config[1] for details.

Merge into the current branch the remote branch next:

> $ git pull origin next

This leaves a copy of next temporarily in FETCH_HEAD, and updates the remote-tracking branch origin/next. The same can be done by invoking fetch and merge:

> $ git fetch origin

> $ git merge origin/next

If you tried a pull which resulted in complex conflicts and would want to start over, you can recover with git reset.
