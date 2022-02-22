## :octocat: < Git Commands />


### Creating Projects

| Command | Description |
| ------- | ----------- |
| `git init` | Initialize a local Git repository |
| `git clone [url]` | Create a local copy of a remote repository |

### Basic Snapshotting

| Command | Description |
| ------- | ----------- |
| `git status` | Check status |
| `git add [file-name.txt]` | Add a file to the staging area |
| `git add .` | Add all new and changed files to the staging area |
| `git commit -m "[commit message]"` | Commit changes |
| `git commit -am "[commit message]"` |Add changed files and commit |
| `git rm -r [file-name.txt]` | Remove a file (or folder) |
| `git commit --ammend` | Ammend the last commit |

### Branching & Merging

| Command | Description |
| ------- | ----------- |
| `git branch` | List branches (the asterisk denotes the current branch) |
| `git branch -a` | List all branches (local and remote) |
| `git branch [branch name]` | Create a new branch |
| `git branch -d [branch name]` | Delete a branch |
| `git show-branch --all` | List all branches local |
| `git push origin --delete [branch name]` | Delete a remote branch |
| `git checkout -b [branch name]` | Create a new branch and switch to it |
| `git checkout -b [branch name] origin/[branch name]` | Clone a remote branch and switch to it |
| `git checkout [branch name]` | Switch to a branch |
| `git checkout -` | Switch to the branch last checked out |
| `git checkout -- [file-name.txt]` | Discard changes to a file |
| `git merge [branch name]` | Merge a branch into the active branch |
| `git merge [source branch] [target branch]` | Merge a branch into a target branch |
| `git stash` | Stash changes in a dirty working directory |
| `git stash clear` | Remove all stashed entries |

### Sharing & Updating Projects

| Command | Description |
| ------- | ----------- |
| `git push origin [branch name]` | Push a branch to your remote repository |
| `git push origin --delete [branch name]` | Delete a remote branch |
| `git pull` | Update local repository to the newest commit |
| `git pull origin [branch name]` | Pull changes from remote repository |
| `git remote add origin ssh://git@github.com/[username]/[repository-name].git` | Add a remote repository |
| `fork` | Copy a external repository |
| `git remote -v` | list remote connections |
| `git remote set-url [branch name] [url]` | Change the url |

### Inspection & Comparison

| Command | Description |
| ------- | ----------- |
| `git log` | View changes | 
| `git log --summary` | View changes (detailed) |
| `git log -all --graph --decorate --oneline` | View changes (Max-detailed) |
| `git diff [source branch] [target branch]` | Preview changes before merging

## :link: Find me!
- Linkedin: https://www.linkedin.com/in/italo-santos-dev/
- Instagram: https://www.instagram.com/italosantsz/
- Github: https://github.com/dev-italosantos
