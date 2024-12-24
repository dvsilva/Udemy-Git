# Project README

This README file contains a list of all commands

## Commands

| Command | Description |
|---------|-------------|
| `git config --global user.name "user name"` | Set global username |
| `git config --global user.email "user.email@domain.com"` | Set global email |
| `git config --global init.defaultBranch master` | Set default branch name |
| `git config --list` | List all configurations |
| `git init` | Initialize a new Git repository |
| `git status` | Show the working tree status |
| `git add <file>` | Add file contents to the index |
| `git rm --cached <file>` | Unstage a file |
| `git commit -m "<message>"` | Record changes to the repository |
| `git diff` | Show changes between commits, commit and working tree, etc |
| `git log` | Show commit logs |
| `git commit --amend -m "<message>"` | Amend the most recent commit |
| `git config --global core.editor "code --wait"` | Set VS Code as the default editor |
| `git checkout <hash>` | Switch branches or restore working tree files |
| `git clean -f` | Remove untracked files from the working tree |
| `git reset --hard` | Reset the index and working tree |
| `git clone <url>` | Clone a repository into a new directory |
| `git remote -v` | List remote repositories |
| `git remote add origin <url>` | Add a remote repository |
| `git push` | Update remote refs along with associated objects |
| `git pull` | Fetch from and integrate with another repository or a local branch |
| `git branch` | List, create, or delete branches |
| `git checkout -b <branch>` | Create and switch to a new branch |
| `git switch <branch>` | Switch branches |
| `git merge <branch>` | Join two or more development histories together |
| `git tag <tag>` | Create, list, delete or verify a tag object signed with GPG |
| `git stash` | Stash the changes in a dirty working directory away |
| `git stash apply` | Apply the changes recorded in a stash to the working directory |
| `git stash pop` | Apply and then drop the latest stash |
| `git revert <commit>` | Revert some existing commits |
| `git reset --mixed HEAD~1` | Reset the current HEAD to the specified state |
| `git push --force` | Forcefully push changes to a remote repository |
| `git rebase <branch>` | Reapply commits on top of another base tip |
| `git fetch` | Download objects and refs from another repository |
| `git bisect` | Use binary search to find the commit that introduced a bug |
| `git config --global alias.<alias> <command>` | Create a Git command alias |
| `git branch | grep <pattern>` | Filter branches by pattern |
| `git log --oneline | grep <pattern>` | Filter commits by pattern |

## Notes

All commands are located in the `notes` folder. Please refer to the individual files for detailed explanations and usage examples.
