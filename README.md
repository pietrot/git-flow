# GIT-FLOW

## FEATURE BRANCH

```
$ git checkout -b "feature-abc"
$ git push -u origin feature-abc
... do work
$ git add --all
$ git commit -m "Fixed|Implemented|Refactored|Deprecated|Etc. ..."
$ git push origin feature-abc
```

## TAGGING RELEASES

```
$ git checkout -b "release-vX.X.X"
... merge feature braches into release.
$ git checkout orgin master
$ git merge --squash release-vX.X.X
$ git commit -m "Release vX.X.X"
$ git tag -a vX.X.X -m "Version X.X.X"
$ git push origin vX.X.X
```
