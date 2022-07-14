# bucky-forecasts

Weekly output from https://github.com/mattkinsey/bucky

County level output will only be included for the most recent week (and old weeks will have it removed from the git history). This is due to the overall size limits GH places on repos.

## Update 2022-07-14
Due to the repo size limits on github all forecasts prior to 2022 have been moved to https://github.com/mattkinsey/bucky-forecasts-archive

### to remove the old county level data from the repo:
```
git filter-repo --path */county/ --invert-paths
git remote add origin git@github.com:mattkinsey/bucky-forecasts.git
git push --force --set-upstream origin master
```
