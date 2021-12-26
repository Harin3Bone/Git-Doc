---
description: Show various types of objects
---

# show

### Synopsis

```
git show
```

### Options

* \--abbrev-commit
  * Showing full commit object name and prefix of that name
* \--pretty=\<format>
  * Pretty print format canbe `short`, `medum`, `full`, `fuller`, `reference`, `email`, `raw`&#x20;
* \--oneline
  * short hand of `--pretty=short --abbrev-commit`&#x20;

### Commands

* Show message and textual different all object

```
git show 
```

* Show message and textual different specific object

```
git show <object>
```

> :notebook\_with\_decorative\_cover: **Note**
>
> `object` is the names of objects to show (defaults to _HEAD_)

```
git show .gitignore
```

