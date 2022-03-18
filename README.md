# Default Git command
Ce dépot est à titre personnel et ouvert à tout ce qui débute sur Git
Le but principal :
- Faciliter la prise en main de l'outil Git
- Avoir une base de commande pour documentation

## 👍 Notice
The **[ ]** show the type of content to add

## 🎄 Shortcuts
- [Default Git command](#-default-git-command)
  - [Notice](#-notice)
  - [Git init](#-git-init)
  - [Git clone](#-git-clone)
  - [Git add](#-git-add)
  - [Git commit](#-git-commit)
  - [Git diff](#-git-diff)
  - [Git reset](#-git-reset)
  - [Git status](#-git-status)
  - [Git rm](#-git-rm)
  - [Git log](#-git-log)
  - [Git show](#-git-show)
  - [Git tag](#-git-tag)
  - [Git branch](#-git-branch)
  - [Git checkout](#-git-checkout)
  - [🔃 Git merge](#arrows_clockwise-git-merge)
  - [Git remote](#-git-remote)
  - [⬆️ Git push](#arrow_up-git-push)
  - [⬇️ Git pull](#arrow_down-git-pull)
  - [💾 Git stash](#floppy_disk-git-stash)
 

## 👍 Git init

| Command     | Description |
| ----------- | ----------- |
| **git init [repository name]**| Start a new repository.|

## Git clone

| Command     | Description |
| ----------- | ----------- |
| **git clone [url]** | Obtain a repository from an existing URL.|

## Git add

| Command     | Description |
| ----------- | ----------- |
| **git add [file]**  | Adds a file to the staging area.|
| ***git add* \***    | Adds one or more file to the staging area.|

## Git commit

| Command     | Description |
| ----------- | ----------- |
| **git commit -m “[ Type in the commit message]”** | Records or snapshots the file permanently in the version history.|
| **git commit -a**   | Commits any files you’ve added with the git add command and also commits any files you’ve changed since then.|

## Git diff 

| Command     | Description |
| ----------- | ----------- |
| **git diff**          | Shows the file differences which are not yet staged.|
| **git diff --staged** | Shows the differences between the files in the staging area and the latest version present.|
| **git diff [first branch] [second branch]** | Shows the differences between the two branches mentioned.|

## Git reset

| Command     | Description |
| ----------- | ----------- |
| **git reset [file]**          | Unstages the file, but it preserves the file contents.|
| **git reset [commit]**        | Undoes all the commits after the specified commit and preserves the changes locally.|
| **git reset --hard [commit]** | Discards all history and goes back to the specified commit.|

## Git status

| Command     | Description |
| ----------- | ----------- |
| **git status** | Lists all the files that have to be committed.|

## Git rm

| Command     | Description |
| ----------- | ----------- |
| **git rm [file]** | Deletes the file from your working directory and stages the deletion.|

## Git log

| Command     | Description |
| ----------- | ----------- |
| **git log** | List the version history for the current branch.|
| **git log --follow [file]** | Lists version history for a file, including the renaming of files also.|

## Git show

| Command     | Description |
| ----------- | ----------- |
| **git show [commit]** | Shows the metadata and content changes of the specified commit.|

## Git tag

| Command     | Description |
| ----------- | ----------- |
| **git tag [commitID]** | Give tags to the specified commit.|

## Git branch

| Command     | Description |
| ----------- | ----------- |
| **git branch** | Lists all the local branches in the current repository.|
| **git branch [branch name]** | Creates a new branch.|
| **git branch -d [branch name]** | Deletes the feature branch.|

## Git checkout

| Command     | Description |
| ----------- | ----------- |
| **git checkout [branch name]**    | Switch from one branch to another.|
| **git checkout -b [branch name]** | Creates a new branch and also switches to it.|

## :arrows_clockwise: Git merge

| Command     | Description |
| ----------- | ----------- |
| **git merge [branch name]** | Merges the specified branch’s history into the current branch.|

## Git remote

| Command     | Description |
| ----------- | ----------- |
| **git remote add [variable name] [Remote Server Link]** | Connect your local repository to the remote server.|

## :arrow_up: Git push

| Command     | Description |
| ----------- | ----------- |
| **git push [variable name] master**         | Sends the committed changes of master branch to your remote repository.|
| **git push [variable name] [branch]**       | Sends the branch commits to your remote repository.|
| **git push –all [variable name]**           | Pushes all branches to your remote repository.|
| **git push [variable name] :[branch name]** | Deletes a branch on your remote repository.|

## :arrow_down: Git pull

| Command     | Description |
| ----------- | ----------- |
| **git pull [Repository Link]** | Fetches and merges changes on the remote server to your working directory.|


## :floppy_disk: Git stash

| Command     | Description |
| ----------- | ----------- |
| **git stash save** | Temporarily stores all the modified tracked files.|
| **git stash pop**  | Restores the most recently stashed files.         |
| **git stash lis**  | Lists all stashed changesets.                     |
| **git stash dro**  | Discards the most recently stashed changeset.     |

