# version-control-learnable-
This is the second task of learnable 2025/2026 (front end development track)

VERSION CONTROL

Version control is simply the practice of keeping and managing changes to source code over time. It is otherwise known as source control or revision control. It enables software engineering teams to track modifications, revert to previous versions, and collaborate simultaneously without overwriting work.

EXPLAIN THE DIFFERENCE BETWEEN GIT AND GITHUB

Git is a distributed version control system that tracks and manages changes in source code efficiently, WHEREAS GitHub is a web-based platform that hosts Git repositories and adds collaboration features for managing code online.

ALTERNATIVES TO GITHUB

* Github
* Bitbucket
* Sourceforge

DIFFERENCE BETWEEN GIT FETCH AND GIT PULL

The "git pull" command is a combination of "git fetch" and "git merge." It fetches changes from the remote repository and automatically merges them into the current branch. Whereas the "git fetch" command only retrieves changes from the remote repository but does not automatically merge them into the current branch. In other words, "git fetch" is preferably used when you want to see what updates are available on the remote repository without disrupting your current work, allowing you to review them first, while "git pull" is to be used when you are confident that the remote changes will not conflict with your local work and you want to quickly synchronize your local branch with the remote.

GIT REBASE AND ITS COMMANDS

Git rebase integrates changes by replaying your commits on top of the latest state of another branch, creating a cleaner, linear history. In simple terms, assuming you are working in a team but your colleagues got their work merged to the main before yours, when you eventually send yours, it will be merged to the main based on the latest updates, and this process streamlines the commit process, making it neater and easily trackable. The command is as follows:

git rebase <branch-name>

GIT CHERRY-PICK AND ITS COMMAND

Git cherry-pick allows you to apply a specific commit from one branch onto another without merging the entire branch. It selectively applies individual commits.

The command:

git cherry-pick <commit-hash>