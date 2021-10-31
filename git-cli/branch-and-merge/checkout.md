---
description: Switch branch or restore working tree files
---

# checkout

### Synopsis

```
git checkout
```

### Options

* \-q
  * Suppress feedback messages
* \-f&#x20;
  * When switching branch if the index or working tree are different from `HEAD` This option will throw away local changes
* \-b
  * Create new branch from current branch at this commit and change into new branch
* \-l
  * Create the new branch reflog

### Commands

* Switch branch

```
git checkout <branchname>
```

> :notebook\_with\_decorative\_cover: **Note**
>
> `<branchname>` your branch name you want to switch

* Switch to new branch and create it

```
git checkout -b <branchname>
```

> :notebook\_with\_decorative\_cover: **Note**
>
> `<branchname>`** **is your new branch name that you want to create
