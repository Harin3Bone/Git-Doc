---
description: Stash the current changes in working directory away
---

# stash

### Synopsis

```
git stash
```

### Options

* \-a
  * All ignored and untracked files are also stashed and then cleaned up with `git clean`

> :notebook\_with\_decorative\_cover: **Note**
>
> This option is only valid for `push` and `save` commands

* \--keep-index
  * All changes already added to the index are left intact.

:notebook\_with\_decorative\_cover: **Note**

This option is only valid for `push` and `save` commands

* \--include-untracked
  * All untracked files are also stashed and then clean up with `git clean`

### Commands

* List all stash

```
git stash list
```

* Show stash detail

```
git stash show <stash>
```

> :notebook\_with\_decorative\_cover: **Note**
>
> `<stash>` is an stash tag

> :pencil: **Example**
>
> ```
> git stash show 'stash@{0}'
> ```

* Delete stash

```
git stash drop <stash>
```

> :notebook\_with\_decorative\_cover: **Note**
>
> `<stash>` is an stash tag

> :pencil: **Example**
>
> ```
> git stash drop 'stash@{0}'
> ```

* Apply current working tree to stash

```
git stash apply <stash>
```

> :notebook\_with\_decorative\_cover: **Note**
>
> `<stash>` is an stash tag

> :pencil: **Example**
>
> ```
> git stash apply 'stash@{0}'
> ```

* Apply current working tree to stash and delete that stash

```
git stash pop <stash>
```

> :notebook\_with\_decorative\_cover: **Note**
>
> `<stash>` is an stash tag

> :pencil: **Example**
>
> ```
> git stash pop 'stash@{0}'
> ```

* Create stash only tracked files

```
git stash -m <message>
```

> :notebook\_with\_decorative\_cover: **Note**
>
> `<message>` is your message in stash

* Create stash all files

```
git stash --keep-index --include-untracked -m <message>
```

> :notebook\_with\_decorative\_cover: **Note**
>
> `<message>` is your message in stash

* Push your stash

```
git stash push
```
