---
description: Remove untracked files from the working tree
---

# clean

### Synopsis

```
git clean
```

### Options

* \-d
  * Normally when no `<path>` is specified, git clean will not recurse into untracked directories to avoid removing too much.

> :notebook\_with\_decorative\_cover: **Note**
>
> With exceptions for nested git directories mentioned under `--force` will be removed

* \-n
  * Don't actually remove anything, just show what would be done
* \-q
  * Only report errors, But not the files that are successfully removed
* \-f
  * If the Git configuration variable `clean.requireForce` is not set to false, git clean will refuse to delete files or directories&#x20;
* \-i
  * Show what would be done and clean files interactively.
* \-x
  * Don't use the standard ignore rules, But still use the ignore rules given with -e options from the command line.

### Commands

* Force clean untracked file from directories

```
git clean -f
```
