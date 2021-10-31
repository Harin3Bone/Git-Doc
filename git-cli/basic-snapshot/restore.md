---
description: Restore working tree files
---

# restore

### Synopsis

```bash
git restore
```

### Options

* \-S
  * Specify the restore location. If neither option is specified.

> ****:notebook\_with\_decorative\_cover:** Note**
>
> By default the working tree is restored.

* \-m
  * When restoring files on the working tree from the index, recreate the conflicted merge in the unmerged paths.

> ****:notebook\_with\_decorative\_cover:** Note**
>
> `-m` is default value of this command

* \--conflict=\<style>
  * Same as `-m` but changes the way to presented

> ****:bulb:** Tip**
>
> Can override by configuration variable `merge.conflictStyle`

### Commands

* Restore all files

```bash
git restore .
```

* Restore specific file

```
git restore <files>
```

> :notebook\_with\_decorative\_cover: **Note**
>
> `<files>` is a specific file path.

> :pencil: **Example**
>
> ```
> git restore .Dockerfile
> ```
