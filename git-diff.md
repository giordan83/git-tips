### Git diff command

```
#
#Compare working copy to index
#
git diff
```

```
#
# Compare working copy with HEAD
#
git diff head
```

```
#
# Compare a specific file to index
#
git diff [filename]
```

```
#
# Show insertion and deletion stats for each file with +-
#
git diff --stat
```

```
#
# git diff [commit] [filename]
#
Compare current [filename] to the same in a specific [commit] (via commit hash etc)
```

```
#
# Compare the most recent commits of two branches
#
git diff [branch]..[other-branch]
```

```
#
# Compare two files on different branches
#
git diff [branch]:[filename] [other-branch]:filename
```

```
#
# Compare any two files
#
git diff --no-index [filename] [filename]
```
