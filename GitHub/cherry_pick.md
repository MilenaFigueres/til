## Cherry Pick: means to choose a commit from one branch and apply it onto another.


# Steps

```gco master
create branch. E.g.: fix-bug-etc
git log (to know what the commit hash is)
keep in mind that if this enters a release it is time to move to the release branch. So git checkout rc2020-05-10
git cherry-pick <commit-hash>
git push origin rc2020-05-10```
