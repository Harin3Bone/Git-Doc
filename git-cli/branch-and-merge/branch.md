---
description: List create or delete branches
---

# branch

### Synopsis

```
git branch
```

### Options

* \-a
  * List all branches and remotes
* \-f
  * Force to do command.
* \-d
  * Delete a branch.

> :bulb: **Tip**
>
> You can use `-D` instead of shortcut of `--delete --force`

* \-m
  * Move or rename a branch corresponding reflog.
* \-c
  * Copy a branch and the corresponding reflog.

> :bulb: **Tip**
>
> You can use -C instead of shortcut of `--copy --force`

* \-r
  * List all remote branch

> :notebook\_with\_decorative\_cover: **Note**
>
> If you use `-d` while have `-r` it will delete your remote.

* \-u
  * Setup branch name tracking information upstream is considered branch name upstream branch

> :notebook\_with\_decorative\_cover: **Note**
>
> * Branch name is default by current branch.
> * You can use `--set-upstream-to` instead of `-u`

* \--unset-upstream
  * Remove the upstream information for the branch name

> :notebook\_with\_decorative\_cover: **Note**
>
> Branch name is default by current branch.

* \-t&#x20;
  * This configuration will tell what branch you are current tracking

### Commands

* List all branch

```
git branch
```

* List all branches and remotes

```
git branch -a
```

* Create new branch

```
git branch <branchname>
```

> :notebook\_with\_decorative\_cover: **Note**
>
> `<branchname>` is your new branch name that you want to created.

* Delete branch

```
git branch -d <branchname>
```

> :notebook\_with\_decorative\_cover: **Note**
>
> `<branchname>` is your branch that you want to delete

* Rename branch

```
git branch -m <old-branch> <new-branch>
```

> :notebook\_with\_decorative\_cover: **Note**
>
> `<old-branch>` is your current branch name
>
> `<new-branch>` is your new name that you want to change.

* Copy branch

```
git branch -c <old-branch> <new-branch>
```

> :notebook\_with\_decorative\_cover: **Note**
>
> `<old-branch>` is your current branch name
>
> `<new-branch>` is your new name that you want to change.
