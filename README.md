# git-masterclass

### Version Control

Version control, also known as source control, is the practice of tracking and managing changes to software code. Version control systems are software tools that help software teams manage changes to source code over time [Source: Atlassian.](https://www.atlassian.com/git/tutorials/what-is-version-control)

### Difference Between Git and GitHub

Git is a version control system that lets you manage and keep track of your source code history. GitHub is a cloud-based hosting service that lets you manage Git repositories. If you have open-source projects that use Git, then GitHub is designed to help you better manage them [Source: Dev Mountain.](https://devmountain.com/blog/git-vs-github-whats-the-difference/)

### Other GitHub Alternatives

- GitLab
- Bitbucket
- SourceForge

### Difference between Git Fetch and Git Pull

The key difference between git fetch and pull is that git pull copies changes from a remote repository directly into your working directory, while git fetch does not. The git fetch command only copies changes into your local Git repo. The git pull command does both [Source: The Server Side.](https://www.theserverside.com/blog/Coffee-Talk-Java-News-Stories-and-Opinions/Git-pull-vs-fetch-Whats-the-difference)

Git fetch basically imports the commits to local branches so as to keep up-to-date with what everybody is working on. Git Pull basically brings the local branch up-to-date with the remote copy that will also update the other remote tracking branches [Source: Geeks for Geeks.](https://www.geeksforgeeks.org/git-difference-between-git-fetch-and-git-pull/)

### Git Rebase

The git rebase command allows you to easily change a series of commits, modifying the history of your repository. You can reorder, edit, or squash commits together.

Typically, you would use git rebase to:

- Edit previous commit messages
- Combine multiple commits into one
- Delete or revert commits that are no longer necessary

[Source: GitHub Docs.](https://docs.github.com/en/get-started/using-git/about-git-rebase)

Rebase is one of two Git utilities designed to integrate changes from one branch onto another. Rebasing is the process of combining or moving a sequence of commits on top of a new base commit. Git rebase is the linear process of merging.

A Git rebase changes the base of the developer’s branch from one commit to another, so it looks like they have created their branch from a different commit. Internally, Git creates a new commit and applies it to the specified base. However, it's essential for everyone involved to understand that although the branch appears the same, it's made up of entirely new commits. When you perform a Git rebase, you are, in effect, rewriting history.

Syntax for launching a standard Git rebase:

`git rebase <base>`

Syntax for launching an interactive Git rebase:

`git rebase --interactive <base>`

[Source: Simplilearn.](https://www.simplilearn.com/what-is-git-rebase-command-article)

### Git Cherry-pick

Git Cherry-pick is a powerful command that enables arbitrary Git commits to be picked by reference and appended to the current working HEAD. Cherry-picking is the act of picking a commit from a branch and applying it to another. Git cherry-pick can be useful for undoing changes. For example, say a commit is accidentally made to the wrong branch. You can switch to the correct branch and cherry-pick the commit to where it should belong.

Syntax for Git Cherry-pick:

`git cherry-pick commitSha`

In this example `commitSha` is a commit reference. You can find a commit reference by using `git log`.

[Source: Atlassian.](https://www.atlassian.com/git/tutorials/cherry-pick)
