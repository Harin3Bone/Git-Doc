---
description: Clone a repository from web server into a new directory
---

# clone

### Synopsis

```bash
git clone
```

### Options

* \-q
  * Progress is not display standard error.
* \--progress
  * Progress status is reported on the standard
* \-o \<name>
  * Instead of using the remote name `origin` to keep track of the upstream repository, use `<name>` to override default value

> ****:notebook\_with\_decorative\_cover:** Note**
>
> `origin` is an default value of this command

* \-b \<name>
  * Instead of pointing the new created HEAD to the branch pointed to by the cloned repository's HEAD, point to `<name>` branch instead. In a non-bare repository, this is the branch that will be checked out.
* \-n
  * No checkout of HEAD is performed after the clone is complete.

### Commands

```bash
git clone <url>
```

> :notebook\_with\_decorative\_cover:** Note**
>
> `<url>` is your git repository link

> :pencil: **Example**
>
> ```
> git clone https://github.com/username/repository.git
> ```
