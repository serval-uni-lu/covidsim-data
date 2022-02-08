# Covidsimulator data
This repository hold the *dvc* files related to the data consummed by the covidsim source code.

### Pulling data
To retrieve the data once the repository is cloned use `dvc pull`

### Pushing data
To version data after it has been changed use 
```
dvc add $FILE_PATH
git commit $FILE_PATH.dvc -m "associated message"
dvc push
git push
```

