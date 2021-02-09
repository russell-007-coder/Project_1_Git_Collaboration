Gitflow Workflow is a Git workflow that helps with continuous software development and implementing DevOps practices. The Gitflow Workflow defines a strict branching model designed around the project release.

# *Gitflow Workflow*
 
**Gitflow Workflow** is a Git workflow design that was first published and made popular by Vincent Driessen at nvie. The Gitflow Workflow defines a **strict branching model** designed around the project release. This provides a robust framework for managing larger projects.  

Gitflow is ideally suited for projects that have a **scheduled release cycle**. It assigns very specific roles to different branches and defines how and when they should interact. In addition to feature branches, it uses individual branches for preparing, maintaining, and recording releases. Of course, you also get to leverage all the benefits of the Feature Branch Workflow: **pull requests, isolated experiments, and more efficient collaboration**.

It contains five types of branches:

1. The production branch

2. The develop branch

3. Feature branches

4. Release branches

5. Hotfix branches

Initializing Git Flow
To initialize the Git flow, you go to the left-hand sidebar in Fork and right-click one of your branches. You’ll see a menu called Git Flow. Under Git Flow, you’ll see initialize Git Flow.

![SSH](https://zellwk.com/images/2018/git-flow/git-flow-init.png)

Release Branch

![SSH](https://zellwk.com/images/2018/git-flow/atlassian-release.png)

1. The release branch will start from the develop branch

2. You’ll create commits to fix any bugs

3. When you’re ready, you push into master

4. You also push the changes back into develop

Hotflix branches

The hotfix branch is used when you have a bug on a master branch that you know you can fix quickly.

Create a branch from master

Fix the bugs

Merge in into master

Merge it into develop at the same time

![SSH](https://zellwk.com/images/2018/git-flow/atlassian-hotfix.png)


# *Summary*

***The overall flow of Gitflow is:***

*1. A develop branch is created from master.*

*2. A release branch is created from develop.*

*3. Feature branches are created from develop.*

*4. When a feature is complete it is merged into the develop branch.*

*5. When the release branch is done it is merged into develop and master.*

*6. If an issue in master is detected a hotfix branch is created from master.*

*7. Once the hotfix is complete it is merged to both develop and master.*

