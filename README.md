# เรียนรู้ Git จาก Nakorn Code

## Git Config

> git config --global user.name "Surachai Vis"
> git config --global user.email "mrj@rvc.ac.th"

## Status

> git status

## Staged Change

(Change on Working Directory) -> (Unstaged Changes) -> {Stage, Unstage} -> (Stage Change)

> git add <File>
> git reset <File>

## Commit

Keyword: Conventional Commit

[Conventional Commit] (https://www.conventionalcommits.org/en/v1.0.0/)

(Stage Changes) -> (Write Commit) -> (Commit)

> git commit -m "Message"

## Git remote

(Local Repository) <-> (Remote Repository)

### Step

- Create Repository on Git Provider
- Copy Repository URL

> git remote add <name> <url>
> git remote add origin https://github.com/mrj-101/learn-git.git

### Check

> git branch
> git remote
> git remote get-url --all origin

## Git Push

(local Repository) -> Push with (Upstream) -> (Remote Repository)

### First time

> git push -u origin main

\*\* -u (Upstream)

### Later time

> git push
