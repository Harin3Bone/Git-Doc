---
description: Setting repository or global options.
---

# config

### Synopsis

```bash
git config
```

### Options

* \--global
  * Scope all `global` variables set in `~/.giitconfig`
* \--local
  * Scope all `local` variables set in `.git/config` in local repository.
* \--system
  * Scope all `system` variables set in `.git/config` in system.
* \--list
  * List all variables set in config file, along with their value.

### Command

* List all configuration variables

```bash
git config --list
```

* List configuration variables by scope in group

```bash
git config <scope> --list
```

> :notebook\_with\_decorative\_cover: **Note**
>
> `<scope>` are have 3 variable include `--system`, `--global` and `--local`
