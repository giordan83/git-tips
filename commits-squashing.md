### How to squash commits in a GitHub pull request

```
git checkout branch_with_changes
git rebase -i origin/master

#
# squash for all of your commits, except the first one. Edit commit message
#

git push origin branch_with_changes -f
```
