# <img align="left" alt="Git" width="45px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" style="padding-right:10px;" /> Git commands

This repository is intended for all those who are new to Git and who want to know the basics

The main goal :
- Facilitate the handling of the Git tool
- Have a command base for documentation

## 📝 Notice
The **[ ]** show the type of content to add

## ↪️ Shortcuts
- [Git commands](#-git-commands)
  - [📝 Notice](#-notice)
  - [🆕 Git init](#new-git-init)
  - [ ↔️ Git clone](#left_right_arrow-git-clone)
  - [➕ Git add](#heavy_plus_sign-git-add)
  - [💬 Git commit](#speech_balloon-git-commit)
  - [🔃 Git diff](#arrows_clockwise-git-diff)
  - [🔄 Git reset](#arrows_counterclockwise-git-reset)
  - [✅ Git status](#white_check_mark-git-status)
  - [❌ Git rm](#x-git-rm)
  - [📄 Git log](#page_facing_up-git-log)
  - [👁️ Git show](#eye-git-show)
  - [🔖 Git tag](#bookmark-git-tag)
  - [🔱 Git branch](#trident-git-branch)
  - [🌵 Git checkout](#cactus-git-checkout)
  - [🔀 Git merge](#twisted_rightwards_arrows-git-merge)
  - [🗄️ Git remote](#file_cabinet-git-remote)
  - [⬆️ Git push](#arrow_up-git-push)
  - [⬇️ Git pull](#arrow_down-git-pull)
  - [💾 Git stash](#floppy_disk-git-stash)
 

## :new: Git init

| Command     | Description |
| ----------- | ----------- |
| `git init [repository name]`| Start a new repository.|

## :left_right_arrow: Git clone

| Command     | Description |
| ----------- | ----------- |
| `git clone [url]` | Obtain a repository from an existing URL.|

## :heavy_plus_sign: Git add

| Command     | Description |
| ----------- | ----------- |
| `git add [file]`  | Adds a file to the staging area.|
| `git add*`    | Adds one or more file to the staging area.|

## :speech_balloon: Git commit

| Command     | Description |
| ----------- | ----------- |
| `git commit -m “[ Type in the commit message]”` | Records or snapshots the file permanently in the version history.|
| `git commit -a`   | Commits any files you’ve added with the git add command and also commits any files you’ve changed since then.|

## :arrows_clockwise: Git diff 

| Command     | Description |
| ----------- | ----------- |
| `git diff`         | Shows the file differences which are not yet staged.|
| `git diff --staged` | Shows the differences between the files in the staging area and the latest version present.|
| **git diff [first branch] [second branch]** | Shows the differences between the two branches mentioned.|

## :arrows_counterclockwise: Git reset
 
| Command     | Description |
| ----------- | ----------- |
| `git reset [file]`          | Unstages the file, but it preserves the file contents.|
| `git reset [commit]`        | Undoes all the commits after the specified commit and preserves the changes locally.|
| `git reset --hard [commit]` | Discards all history and goes back to the specified commit.|

## :white_check_mark: Git status

| Command     | Description |
| ----------- | ----------- |
| `git status` | Lists all the files that have to be committed.|

## :x: Git rm

| Command     | Description |
| ----------- | ----------- |
| `git rm [file]` | Deletes the file from your working directory and stages the deletion.|

## :page_facing_up: Git log

| Command     | Description |
| ----------- | ----------- |
| `git log` | List the version history for the current branch.|
| `git log --follow [file]` | Lists version history for a file, including the renaming of files also.|

## :eye: Git show

| Command     | Description |
| ----------- | ----------- |
| `git show [commit]` | Shows the metadata and content changes of the specified commit.|

## :bookmark: Git tag

| Command     | Description |
| ----------- | ----------- |
| `git tag [commitID]` | Give tags to the specified commit.|

## :trident: Git branch

| Command     | Description |
| ----------- | ----------- |
| `git branch` | Lists all the local branches in the current repository.|
| `git branch [branch name]` | Creates a new branch.|
| `git branch -d [branch name]` | Deletes the feature branch.|

## :cactus: Git checkout

| Command     | Description |
| ----------- | ----------- |
| `git checkout [branch name]`    | Switch from one branch to another.|
| `git checkout -b [branch name]` | Creates a new branch and also switches to it.|

## :twisted_rightwards_arrows: Git merge

| Command     | Description |
| ----------- | ----------- |
| `git merge [branch name]` | Merges the specified branch’s history into the current branch.|

## :file_cabinet: Git remote

| Command     | Description |
| ----------- | ----------- |
| `git remote add [variable name] [Remote Server Link]` | Connect your local repository to the remote server.|

## :arrow_up: Git push

| Command     | Description |
| ----------- | ----------- |
| `git push [variable name] master`         | Sends the committed changes of master branch to your remote repository.|
| `git push [variable name] [branch]`       | Sends the branch commits to your remote repository.|
| `git push –all [variable name]`           | Pushes all branches to your remote repository.|
| `git push [variable name] :[branch name]` | Deletes a branch on your remote repository.|

## :arrow_down: Git pull

| Command     | Description |
| ----------- | ----------- |
| `git pull [Repository Link]` | Fetches and merges changes on the remote server to your working directory.|


## :floppy_disk: Git stash

| Command     | Description |
| ----------- | ----------- |
| `git stash save` | Temporarily stores all the modified tracked files.|
| `git stash pop`  | Restores the most recently stashed files.         |
| `git stash list`  | Lists all stashed changesets.                     |
| `git stash drop`  | Discards the most recently stashed changeset.     |
