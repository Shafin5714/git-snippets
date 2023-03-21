## User identity

```
git config --global user.name "shafin"
git config --global user.email "shafin@mail.com"
```

## Show users

```
git config --list
git config user.name
```

## Local user

```
git config user.name "Your Name Here"
git config user.email your@email.example
git config user.name && git config user.email
```

## Initialize

```
git init
```

## Status

```
git status
```

## Stage all the files

```
git add -A

git add .                        (at the root of your project folder)
```

## Restore

```
git restore <filename>
```

### To only unstage a certain file and thereby undo a previous git add, you need to provide the --staged flag

```
$ git restore --staged index.html
```

## Check difference

```
git diff
```

## Commit

```
git commit -m "Initial commit"
```

## Switch Between Commits

```
git checkout 0d1d7fc32
```

## Show commit history

```
git log
git log --oneline
```

## Uncommit the last commit

```
git reset --soft HEAD^
```

## Creating new branch

```
git checkout -b ＜new-branch＞
```

## Switching Branches

```
git checkout ＜branchname＞
```

## Push and pull

```
git push
git pull
```

```
git push origin branchName
```

## Push code to specific branch

```
git push origin branchName
```

## Clone repository and rename

```
git clone repositorylink newfilename
```

## Delete cached branch
```
git branch --delete auth
```

## Reset
```
git reset --hard 02bf3eb
```


## Remove the last commit from the current branch, but the file changes will stay in your working tree.
```
git reset --soft HEAD~1
```
