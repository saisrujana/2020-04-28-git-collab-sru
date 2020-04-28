
# 2020-04-28-git-collaboration-sru
Git collaboration workshop

- `git clone <URL>`:downloads the repo from the web to the local machine
   - make sure you don't nest this command in another repository
   - just like `git init` do only once per repo

## Branches
- `git branch <branchname>`: create new branch
- `git switch <branchname>`: move to  branch
   - `git checkout <branch_name>`: old way of moving to branch

- `git switch -c <branchname>`: create and move in 1 command
   - `git checkout -b <branchname>`
- `git branch -d <branchname>`: to delete the brach

#trying git stash for temporary commit
- `git stash`: to make temporary commit to avoid (add commit switch)
- `git stash list`: to see the stash
- `git stash apply`: to apply the stash
- `git stash clear`: to clear the stash
