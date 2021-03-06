---
description: Add file contents from index to staged.
---

# add

### Synopsis

```bash
git add <file>
```

### Options

* \-n
  * Not add files, just show if they exists or will be ignored.
* \-f
  * Force adding files, Otherwise ignored files.
* \-a
  * Add all of files from index to staged

> ****:notebook\_with\_decorative\_cover:** Note**
>
> Actually you can use `.` instead of `-a`

### Commands

* Add all files

```bash
git add .
```

* Add specific file

```
git add <files>
```

> :notebook\_with\_decorative\_cover: **Note**
>
> `<files>` is a specific file path.

> :pencil: **Example**
>
> `git add .env`
