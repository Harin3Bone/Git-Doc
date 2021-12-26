---
description: Show commit logs
---

# log

### Synopsis

```
git log
```

### Options

* \--no-decorate
  * Printout your commit log without decorate anything

> :notebook\_with\_decorative\_cover: **Note**
>
> `--no-decorate` it is use by **default**&#x20;

* \--decorate \<options>
  * Printout the ref names of any commit that are shown.

> :notebook\_with\_decorative\_cover: **Note**
>
> `--decorate` have 4 options include
>
> 1. short = the ref name prefixes will not print
> 2. full = show the full ref name (including prefix)
> 3. auto = show ref name but show in short not full of ref name
> 4. no = like `--no-decorate`
>
> `--decorate` is use `auto` by **default**

* \--log-size
  * Show length of commit message in bytes
* \-n
  * Limit the number of commits output
* \--since=\<date>
  * Show commits recent than specific date.

> ****:notebook\_with\_decorative\_cover: **Note**
>
> `<date>` is a day you want to specify (Format: YYYYMMdd)

* \--after=\<date>
  * Show commits recent than specific date.

> :notebook\_with\_decorative\_cover: **Note**
>
> `<date>` is a day you want to specify (Format: YYYYMMdd)

* \--author=\<pattern>
  * Show commit of author match your pattern

> :notebook\_with\_decorative\_cover: **Note**
>
> `<pattern>` is regex of author you want to find

* \--merges
  * Print only `merge` commit
* \--dense
  * Only the selected commits are shown, plus some to have a meaningful history
* \--sparse
  * All commits in the simplified history are shown
* \--all
  * Show log of all branches and remotes and stash

### Commands

* Show default log current branch

```
git log
```

* Show log all branches and remotes and stash

```
git log --all
```

* Show log in oneline

```
git log --oneline 
```

* Show log with graph&#x20;

```
git log --graph --decorate
```

> ****:bulb: **Tip**
>
> You can combine all commands from above into 1 line like this
>
> ```
> git log --oneline --graph --decorate --all
> ```
>
> And i recommended to do this because it easier to track your history

* Show log commit by number

```
git log -n <number>
```

> :notebook\_with\_decorative\_cover: **Note**
>
> `<number>` is number assign to display commit you want to show

* Show log with specific date

```
git log --since=<date> --after=<date>
```

> :notebook\_with\_decorative\_cover: **Note**
>
> `<date>` is a day you want to specify (Format: YYYYMMdd)
