---
description: Fetch and integrate a data from remote to your local.
---

# pull

### Synopsis

```bash
git pull
```

### Options

* \-q
  * This is passed to both underlying `git fetch` to squelch reporting of during transfer. and underlying `git-merge` to squelch output during merging.
* \-v
  * Pass `--verbose` to `git fetch` and `git merge`

### Commands

* Pull with specific branch

```bash
git pull <branch>
```

> :notebook\_with\_decorative\_cover: **Note**
>
> `<branch>` is your branch you want to pull.

* Pull  current branch

```bash
git pull
```
