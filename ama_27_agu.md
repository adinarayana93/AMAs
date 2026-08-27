# AMA - 27 Aug

## 1. What is the use of the `ls` command?

`ls` is used to list files and directories in the current directory.

## 2. What is the `rsync` command used for in the CLI?

`rsync` is used to copy and synchronize files and directories between locations.

## 3. What is the use of `git reset`?

`git reset` moves the branch pointer back to a previous commit. With --soft, the changes remain staged; with --mixed (default), they become unstaged but stay in the working directory; with --hard, all changes are discarded.

## 4. What is the use of the `cd` command?

`cd` is used to change the current working directory.

## 5. How can you find the audio driver using the CLI?

Use:

```bash
lspci -k | grep -i -A 3 audio
```

## 6. Which command is used to check running processes in the system?

Use:

```bash
ps -ef
```

## 7. How can you remove a .git file from a directory after git init?
Use:

```bash
rm -rf .git
```


## 8. What is composition in Python?

Composition is an OOP design principle where a class contains objects of other classes as attributes, modeling a "has-a" relationship (vs. inheritance's "is-a" relationship).

## 9. How can you delete a database?

In PostgreSQL, use:

```sql
DROP DATABASE database_name;
```

## 10. What is the difference between a class and an object?

- Class: A blueprint for creating objects.
- Object: An actual instance created from a class.

## 11. What is the use of `git rebase`?

`git rebase` replays your commits on top of another branch's tip, producing a linear history instead of a branching one.

## 12. What are the rules for declaring variables?

- A variable name can contain letters, digits, and `_`.
- It cannot start with a digit.
- It cannot contain spaces or special characters.
- It cannot be a Python keyword.
- Variable names are case-sensitive.

## 13. What is DIP?

DIP (Dependency Inversion Principle) says that high-level code should depend on abstractions, not directly on low-level implementations.
