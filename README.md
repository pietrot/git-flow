# GIT-FLOW

## TAGGING RELEASES

```
$ git checkout -b "release-vX.X.X"
... do work
$ git checkout orgin master
$ git merge --squash release-vX.X.X
$ git commit -m "Release vX.X.X"
$ git tag -a vX.X.X -m "Version X.X.X"
$ git push origin vX.X.X
```
