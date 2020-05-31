# Cherry Pick

## The steps to follow are:

1- `gco master`

2- create branch. E.g.: `fix-bug-etc`

3- `git log` (to know what the commit hash is)

4- keep in mind that if this enters a release it is time to move to the release branch. So `git checkout rc2020-05-10`

5- `git cherry-pick <commit-hash>`

6- `git push origin rc2020-05-10`
