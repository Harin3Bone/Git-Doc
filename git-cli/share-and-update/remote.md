---
description: Manage set of tracked repositories
---

# remote

### Synopsis

```bash
git remote
```

### Options

* \-v
  * Be a little more verbose and show remote url after name.

> ****:notebook\_with\_decorative\_cover:** Note**
>
> This must be placed between `remote` and subcommand.

### Commands

*   add

    Add a remote named `<name>` for the repository at `<url>`&#x20;

```bash
git remote add <name> <url>
```

> ****:notebook\_with\_decorative\_cover:** Note**
>
> `<name>` is remote name
>
> `<url>` is git repository url

*   rename

    Rename remote named from **old** to **new**

```bash
git remote rename <old> <new>
```

> ****:notebook\_with\_decorative\_cover:** Note**
>
> `<old>` your old remote name
>
> `<new>` your new remote name want to change

*   remove

    Remove your remote

```bash
git remote remove <name>
```

> ****:notebook\_with\_decorative\_cover:** Note**
>
> `<name>` your remote name that you want to remove

*   get-url

    Show Git url of remote name (Use for check git url of your remote)

```bash
git remote get-url <name>
```

> ****:notebook\_with\_decorative\_cover:** Note**
>
> `<name>` is your remote name that you want to check git url.

*   set-url

    Set new git url to you remote

```bash
git remote set-url <name> <new-url> <old-url>
```

> ****:notebook\_with\_decorative\_cover:** Note**
>
> `<name>` your remote name
>
> `<new-url>` your new url of remote
>
> `<old-url>` your old url of remote

*   prune

    Delete stale reference associated with `<name>`

```bash
git remote prune
```

