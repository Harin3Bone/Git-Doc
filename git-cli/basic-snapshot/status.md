---
description: Show the working tree status
---

# status

### Synopsis

```bash
git status
```

### Options

* \-s
  * Give output in the short format
* \-b&#x20;
  * Show the branch and tracking info even in  short-format
* \--show-stash
  * Show the number of entries currently you stashed away
*   \--long

    * Give the output in the long-format



    > :notebook\_with\_decorative\_cover:**Note**
    >
    > \--long is an default format of this command.
*   \-u \<mode>

    * Show untracked files
    *   The mode parameter have 3 value include

        * no - Never show untracked files
        * normal - Shows untracked files and directories
        * all - Also shows individual files un untracked directories



    > ****:notebook\_with\_decorative\_cover:** Note **
    >
    > normal is an default value of this command.

    > ****:bulb:** Tip **
    >
    > Can override by configuration variable `status.showUntrackedFiles`
*   \--ignored \<mode>

    * Show ignored files as well
    *   The mode parameter have 3 value include

        * no - Never show ignored files.
        * traditional - Shows ignored files and directories
        * matching - Shows ignored files and directories matching an ignore pattern.



    > ****:notebook\_with\_decorative\_cover:** Note**
    >
    > no is an default value of this command.

### Commands

```bash
git status
```

