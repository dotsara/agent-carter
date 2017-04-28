# test-deleting-forked-repo
Have a public repo, fork it, delete the original: what happens?

[GitHub says:](https://help.github.com/articles/what-happens-to-forks-when-a-repository-is-deleted-or-changes-visibility/)
> When you delete a public repository, one of the existing public forks is chosen to be the new parent repository. All other repositories are forked off of this new parent and subsequent pull requests go to this new parent.

So, let's just see!

Adding an edit in the fork just to have one, next I'll delete the original repo.

SWEET. At least in this case all that happened after deleting the original is that the "forked from" bit disappeared from this repo. :tada: 
