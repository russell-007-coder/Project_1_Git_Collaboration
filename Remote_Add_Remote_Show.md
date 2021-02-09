# *REMOTE ADD/ REMOVE/ SHOW*

![remote](https://wac-cdn.atlassian.com/dam/jcr:df13d351-6189-4f0b-94f0-21d3fcd66038/01.svg?cdnVersion=1253)

It manages the set of repositories ("remotes") whose branches you track.

> git remote



## *Example*

- *add*

To add a new remote, use the git remote add command on the terminal, in the directory your repository is stored at.

The git remote add command takes two arguments:

-A remote name, for example, origin

-A remote URL, for example, https://github.com/user/repo.git

For example:

$ git remote add origin https://github.com/user/repo.git
# Set a new remote

$ git remote -v
# Verify new remote
> origin  https://github.com/user/repo.git (fetch)
> origin  https://github.com/user/repo.git (push)

- *remove*

Use the git remote rm command to remove a remote URL from your repository.

The git remote rm command takes one argument:

A remote name, for example, destination

Example:
These examples assume you're cloning using HTTPS, which is recommended.

$ git remote -v
# View current remotes
> origin  https://github.com/OWNER/REPOSITORY.git (fetch)
> origin  https://github.com/OWNER/REPOSITORY.git (push)
> destination  https://github.com/FORKER/REPOSITORY.git (fetch)
> destination  https://github.com/FORKER/REPOSITORY.git (push)

$ git remote rm destination
# Remove remote
$ git remote -v
# Verify it's gone
> origin  https://github.com/OWNER/REPOSITORY.git (fetch)
> origin  https://github.com/OWNER/REPOSITORY.git (push)

- *show*

Invoking git remote with the -v option will print the list of bookmarked repository names and additionally, the corresponding repository URL. The -v option stands for "verbose". Below is example output of verbose git remote output.
Gives some information about the remote <name>.
With -n option, the remote heads are not queried first with git ls-remote <name>; cached information is used instead.
