# Branching
Branching offers a way to work on a new feature without affecting the main codebase. You can create a branch from Bitbucket, Jira Software, or from your terminal.

## How to branch in Github

1. From your terminal window, list the branches on your repository.
> git branch 
>  master
This output indicates there is a single branch, the master and the asterisk indicates it is currently active.
2. Create a new feature branch in the repository
> $ git branch <feature_branch>      

3.Switch to the feature branch to work on it.

> $ git checkout <feature_branch>      

4. You can list the branches again with the git branch command.

Commit the change to the feature branch:

> $ git add .  
> $ git commit -m "adding a change from the feature branch"      

5. Switch back to the master branch.

> $ git checkout master      

6. Push the feature branch to Bitbucket:

> $ git push origin <feature_branch>      

7. View the Source page of your repository in Bitbucket. You should see both the master and the feature branch. When you select the feature branch, you see the Source page from that perspective. Select the feature branch to view its Recent commits.

