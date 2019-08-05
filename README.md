# US Ignite Spatial Data Science Notebooks for Portland, OR


## Git workflow
Below is an brief outline of the git workflow for joint development between CARTO and US Ignite:

###Pull from `develop` and check out a new working branch
The `develop` branch will be the main branch which we merge our changes and share notebooks. When beginning work on any notebook, please pull from `develop` first:

```
git pull origin develop
```

Then checkout a new branch to work on during your work session:

```
git checkout -b dev-jd
```

You may call this branch anything you like, but using some combination of "develop" and your name will clearly indicate the user and state of the branch

# Merge changes or create a pull request
When your work is complete on your personal development branch (i.e. `dev-jd`) you can merge changes back to `develop` by changing branches back to `develop`:

```
git checkout develop
```




