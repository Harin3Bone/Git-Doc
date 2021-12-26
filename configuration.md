---
description: This is my configuration of git
---

# Configuration

### Alias

*   Display log history by custom format

    * Setup

    ```bash
    git config --global alias.tree "log --graph --decorate --pretty='%C(yellow)%h %C(#D502FF)%d %C(cyan)%cs %C(#FF0202)<%an> %C(green)%s' --abbrev-commit --all"
    ```

    * Command

    ```bash
    git tree
    ```


*   Display all branches

    * Setup

    ```bash
    git config --global alias.branchs "branch -a"
    ```

    * Command

    ```bash
    git branchs
    ```
*   Show status

    * Setup

    ```bash
    git config --global alias.stat "status"
    ```

    * Command

    ```bash
    git stat
    ```
*   Add all index to staged

    * Setup

    ```bash
    git config --global alias.adds "add ."
    ```

    * Command

    ```bash
    git adds
    ```
*   Restore all staged to index

    * Setup

    ```bash
    git config --global alias.restores "restore ."
    ```

    * Command

    ```bash
    git restores
    ```
*   Stash all files (include tracked and untracked)

    * Setup

    ```bash
    git config --global alias.backup "!git stash --include-untracked --keep-index"
    ```

    * Command

    ```bash
    git backup -m <message>
    ```

    > :notebook\_with\_decorative\_cover: **Note**
    >
    > `<message>` is a stash message
*   Checkout and then create new branch

    * Setup

    ```bash
    git config --global alias.new "checkout -b"
    ```

    * Command

    ```bash
    git new <branch>
    ```

    > ****:notebook\_with\_decorative\_cover: **Note**
    >
    > `<branch>` is a new branch name.
*   Display all global configuration

    * Setup

    ```bash
    git config --global alias.setting "config --global --list"
    ```

    * Command

    ```bash
    git setting
    ```


*   Always merge with create commit

    * Setup

    ```
    git config --global alias.fusion "merge --no-ff --commit"
    ```

    * Command

    ```
    git fusion <branch> -m <message>
    ```

> :notebook\_with\_decorative\_cover: **Note**
>
> `<branch>` is a new branch name.
>
> `<message>` is a message

* Track all branch current commit
  * Setup
  * Command

### Status

* Change color

```
git config --global color.status.changed yellow
git config --global color.status.untracked magenta
git config --global color.status.added green
git config --global color.status.deleted red
git config --global color.status.unmerged magenta
git config --global color.status.branch cyan
git config --global color.status.header white
```

### Branch

* Change color

```
git config --global color.branch.current green
git config --global color.branch.local yellow
git config --global color.branch.remote cyan
```

