---
description: Join two or more development histories together
---

# merge

### Synopsis

```
git merge
```

### Options

* \--commit
  * Merge branch with create commit

> :bulb: **Tip**
>
> Recommended always use `--commit` when you merging branch.

* \--no-commit
  * Merge branch without create commit
* \--ff
  * When is possible to resolve the merge as a `fast-forward` It will merge without create a commit&#x20;
* \--no-ff
  * Always create a merge commit in all cases, even the merge could instead resolve as a `fast-forward`
* \--ff-only
  * Resolve the merge as a `fast-forward` when possible. When not possible will refuse to merging and exit
* \-v
  * Be verbose.
* \-q
  * Operate quietly. Implies --no-progress
* \-m
  * Set the commit message to be used for the merge commit
* \--abort
  * Abort the current conflict resolution process, and try to reconstruct the pre-merge state
* \--quit
  * Forget about the current merge in progress, Leave the index and the working tree
*   \--continue

    * After a git merge stops due to conflicts you can conclude the merge by running&#x20;

    `git merge --continue`

### Commands

* Merge source branch to current branch

```
git merge <src-branch> --no-ff --commit -m <message>
```

> :notebook\_with\_decorative\_cover: **Note**
>
> `<src-branch>` is your source branch you want to merge into your current tracking branch
>
> `<message>` is commit message when it create merge commit
