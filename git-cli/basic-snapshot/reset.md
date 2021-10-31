---
description: Reset current HEAD to the specified state
---

# reset

### Synopsis

```bash
git reset
```

### Options

* \-q
  * Only report errors

> :bulb: **Tip**
>
> Can override by configuration variable `reset.quite` option `--quite` or `--no-quite`

### Commands

* Reset working directory to commit

```bash
git reset <mode> <commit>
```

> :notebook\_with\_decorative\_cover: **Note**
>
> `<mode>` of this command have 5 value include
>
> * `--soft` Does not touch the index file or the working tree at all, But reset the `HEAD` to `<commit>`
> * `--mixed` Reset the index but not the working tree
> * `--hard` Resets the index and working tree. Any changed to tracked files in the working tree are discarded.
> * `--merge` Resets the index and updates the files in the working tree that are different between `<commit>` and `HEAD`
> * `--keep` Resets index entries and updates files in the working tree that are different between `<commit>` and `HEAD`
>
> \<commit> is SHA commit code of git log

> :pencil: **Example**
>
> ```bash
> git reset --hard
> ```

* Remove current commit to another commit

```bash
git reset --hard <commit>
```

> :notebook\_with\_decorative\_cover: **Note**
>
> `<commit>` is SHA commit code of git log

> :pencil: **Example**
>
> ```
> git restore --hard 5c79a36
> ```
