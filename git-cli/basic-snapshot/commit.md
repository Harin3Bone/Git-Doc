---
description: Record changes to the repository
---

# commit

### Synopsis

```bash
git commit -m <message>
```

### Options

* \-a
  * Automatically stage all files in index that you have been modified or deleted. Except new file that you never tracked before.
* \-C
  * Take an existing commit object and reuse the log message
* \-c&#x20;
  * like `-C` but the editor is invoked, so that the user can further edit the commit message.
* \--short
  * Display the output in short format.
* \--branch
  * Show the branch and tracking info even in the short-format.
* \--long&#x20;
  * Display the output in long format.
*   \--author=\<author>

    * Override commit author.

    > :notebook\_with\_decorative\_cover: **Note**
    >
    > Default value is your authenticate username.
*   \--date=\<date>

    * Override commit date

    > :notebook\_with\_decorative\_cover: **Note**
    >
    > Default value is current date
* \-m \<message>
  * Add commit message to you commit
* \-q
  * Suppress commit summary message.

### Commands

```bash
git commit -m "Initial commit"
```

> :notebook\_with\_decorative\_cover: **Note**
>
> `<message>` is your commit message.
