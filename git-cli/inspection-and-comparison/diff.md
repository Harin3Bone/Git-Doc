---
description: Show changes between commits, commit and working tree
---

# diff

### Synopsis

```
git diff
```

### Options

* \-p
  * Generate patch

> :notebook\_with\_decorative\_cover: **Note**
>
> `-p` is the **default** of this command

* \-s
  * Suppress diff output. Useful for commands like `git show`&#x20;
* \--output=\<file>
  * Output specific file

> :notebook\_with\_decorative\_cover: **Note**
>
> `file` is your file name you want to diff

* \--raw
  * Generate the diff in raw format
* \--patch-with-raw
  * Synonym for `-p --raw`
* \--name-only
  * Show only name of changed files
* \--name-status
  * Show only names and status of changed files
* \-a
  * Treat all files as text
* \-b
  * Ignore changes in amount of whitespace. This ignores whitespace at line end, and considers all other sequence of one or more whitespace characters to be equivalent.
* \--quite
  * Disable all output of the program.
* \--no-prefix
  * Do not show any source or destination prefix.

### Commands

* Diff all files of current state and latest commit

```
git diff
```

* Diff specific file of current state and latest commit

```
git diff <object>
```

> :notebook\_with\_decorative\_cover: **Note**
>
> `object` is you file name
