---
description: Update remote refs along with associated objects.
---

# push

### Synopsis

```bash
git push
```

### Options

* \--all
  * Push all branches
* \-f
  * Force push to remote
* \-u \<remote> \<branch>
  * For every branch never create on remote before. You need to add branch to upstream server.

### Commands

*   Push new branch

    ```bash
    git push -u <remote> <branch>
    ```

    > :notebook\_with\_decorative\_cover: **Note**
    >
    > `<remote>` is your remote name that you have been add.
    >
    > `<branch>` is your branch name you want to push.
*   Push tracked branch

    ```bash
    git push
    ```
