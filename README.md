## Start Machine Learning Project

### Software and Account Requirements:

1. [Github Account](https://github.com/)
2. [Heroku Account](https://signup.heroku.com/)
3. [VS Code IDE](https://code.visualstudio.com/download)
4. [GIT CLI](https://git-scm.com/downloads)
5. [GIT Tutorial](https://git-scm.com/docs/gittutorial)

Creating conda environment:
```
conda create -p venv python==3.7 -y
```

To Activate Environment:
```
conda activate venv/
```

To add files to git:
```
git add .
```
or

```
git add <filename>
```

Note: To ignore file or folder from git we can write name of file/folder in .gitignore file.

To check the git status:

```
git status
```

To check all the version maintained by git:
```
git log
```

To create version/commit all changes by git:
```
git commit -m "message"
```

To send version/changes to github:

```
git push origin main
```

To check remote URL:

```
git remote -v
```