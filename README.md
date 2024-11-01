# Git Commands Cheat Sheet

## 1. git init
Initializes a new Git repository in the current directory.
```bash
git init
```

---

## 2. git clone
Clones a repository from a remote source.
```bash
git clone <repository-url>
```

---

## 3. git status
Displays the state of the working directory and staging area.
```bash
git status
```

---

## 4. git add
Stages changes for the next commit.
```bash
git add <file>     # Stages a specific file
git add .          # Stages all files in the current directory
```

---

## 5. git commit
Records changes to the repository with a message.
```bash
git commit -m "Commit message here"
```

---

## 6. git branch
Lists all branches, creates a new branch, or deletes a branch.
```bash
git branch               # List branches
git branch <name>        # Create a new branch
git branch -d <name>     # Delete a branch
```

---

## 7. git checkout
Switches branches or restores working tree files.
```bash
git checkout <branch-name>
git checkout -b <new-branch-name>  # Create and switch to a new branch
```

---

## 8. git merge
Merges changes from one branch into the current branch.
```bash
git merge <branch-name>
```

---

## 9. git pull
Fetches changes from a remote repository and merges them into the current branch.
```bash
git pull <remote> <branch>
```

---

## 10. git push
Pushes commits from the local repository to a remote repository.
```bash
git push <remote> <branch>
```

---

## 11. git log
Shows the commit history.
```bash
git log
```

---

## 12. git diff
Shows the differences between files in the working directory, staging area, and commits.
```bash
git diff           # Changes in the working directory
git diff --staged  # Changes staged for the next commit
```

---

## 13. git remote
Manages remote repository connections.
```bash
git remote add <name> <url>
git remote -v        # List remote connections
```

---

## 14. git fetch
Downloads objects and refs from another repository.
```bash
git fetch <remote>
```

---

## 15. git rebase
Applies commits from one branch on top of another.
```bash
git rebase <branch>
```

---

## 16. git stash
Temporarily saves changes to a stash.
```bash
git stash
git stash apply     # Apply the most recent stash
```

---

## 17. git tag
Tags specific points in history as important.
```bash
git tag <tag-name>
```

---

## 18. git config
Configures Git settings.
```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

---

## 19. git reset
Resets changes in the working directory or staging area.
```bash
git reset HEAD <file>   # Unstage a file
git reset --hard        # Discards all changes
```

---

## 20. git show
Shows details of a specific commit.
```bash
git show <commit-hash>
```

---

## 21. git cherry-pick
Applies the changes from a specific commit onto the current branch.
```bash
git cherry-pick <commit-hash>
```

---

## 22. git rm
Removes files from the working directory and the index.
```bash
git rm <file>
```

---

## 23. git mv
Moves or renames a file, directory, or symlink.
```bash
git mv <old-path> <new-path>
```

---

## 24. git blame
Shows what revision and author last modified each line of a file.
```bash
git blame <file>
```

---

## 25. git log --oneline
Displays a condensed commit history.
```bash
git log --oneline
```

---

## 26. git log --graph
Visualizes the branch structure in the commit history.
```bash
git log --graph
```

---

## 27. git shortlog
Summarizes commit history by author.
```bash
git shortlog
```

---

## 28. git describe
Describes the current commit using tags and commit distance.
```bash
git describe
```

---

## 29. git reflog
Displays the reference logs for the repository.
```bash
git reflog
```

---

## 30. git bisect
Helps find the commit that introduced a bug by binary search.
```bash
git bisect start
```

---

## 31. git grep
Searches for a string in the repository.
```bash
git grep "search-string"
```

---

## 32. git clean
Removes untracked files from the working directory.
```bash
git clean -f     # Force clean
```

---

## 33. git archive
Creates an archive file of a repository.
```bash
git archive -o <output.zip> <branch-name>
```

---

## 34. git submodule
Manages submodules within a repository.
```bash
git submodule add <url> <path>
```

---

## 35. git commit --amend
Amends the previous commit with new changes.
```bash
git commit --amend
```

---

## 36. git diff --name-only
Shows only the names of modified files.
```bash
git diff --name-only
```

---

## 37. git diff HEAD
Compares the working directory and staging area to the last commit.
```bash
git diff HEAD
```

---

## 38. git branch -m
Renames a branch.
```bash
git branch -m <new-branch-name>
```

---

## 39. git push --tags
Pushes tags to a remote repository.
```bash
git push --tags
```

---

## 40. git pull --rebase
Combines `git pull` and `git rebase` to keep commits in a linear history.
```bash
git pull --rebase <remote> <branch>
```

---

## 41. git whatchanged
Shows commit history along with file changes.
```bash
git whatchanged
```

---

## 42. git cherry
Finds commits in one branch and not another.
```bash
git cherry <upstream-branch> <topic-branch>
```

---

## 43. git rev-parse
Extracts various information about commits or branches.
```bash
git rev-parse HEAD
```

---

## 44. git revert
Reverts a previous commit by creating a new commit that undoes the changes.
```bash
git revert <commit-hash>
```

---

## 45. git gc
Runs garbage collection to optimize repository size.
```bash
git gc
```

---

## 46. git apply
Applies a patch to the working directory.
```bash
git apply <patch-file>
```

---

## 47. git format-patch
Generates a patch file from commits.
```bash
git format-patch <commit-range>
```

---

## 48. git instaweb
Instantly serves your repository via a web server.
```bash
git instaweb
```

---

## 49. git archive --format=tar
Creates a .tar archive of the repository.
```bash
git archive --format=tar HEAD
```

---

## 50. git archive --format=zip
Creates a .zip archive of the repository.
```bash
git archive --format=zip HEAD -o archive.zip
```

---

## 51. git tag -a
Creates an annotated tag.
```bash
git tag -a <tag-name> -m "Tag message"
```

---

## 52. git log -p
Shows the commit history with patch differences.
```bash
git log -p
```

---

## 53. git show-branch
Visualizes the branch history.
```bash
git show-branch
```

---

## 54. git blame -L
Shows who made changes in a specific line range in a file.
```bash
git blame -L <start>,<end> <file>
```

---

## 55. git checkout -- <file>
Restores a file to its last committed state.
```bash
git checkout -- <file>
```

---

## 56. git checkout HEAD~1
Checks out a previous commit.
```bash
git checkout HEAD~1
```

---

## 57. git clean -fd
Forces deletion of untracked files and directories.
```bash
git clean -fd
```

---

## 58. git config --list
Lists all configuration settings.
```bash
git config --list
```

---

## 59. git reflog expire
Expires older reflogs.
```bash
git reflog expire --expire=now --all
```

---

## 60. git ls-files
Lists files in the index.
```bash
git ls-files
```

---

## 61. git bisect run
Runs a specified script for each bisect step.
```bash
git bisect run <script>
```

---

## 62. git merge-base
Finds common ancestors between commits.
```bash
git merge-base <commit1> <commit2>
```

---

## 63. git hash-object
Computes the SHA1 hash of a given file.
```bash
git hash-object <file>
```

---

## 64. git push --all
Pushes all branches to a remote repository.
```bash
git push --all
```

---

## 65. git push --force
Forces a push that overwrites changes in the remote branch.
```bash
git push --force
```

---

## 66. git rm --cached
Removes files from the index but keeps them in the working directory.
```bash
git rm --cached <file>
```

---

## 67. git diff --cached
Shows differences between the staged changes and the last commit.
```bash
git diff --cached
```

---

## 68. git commit -v
Commits staged changes and includes diff in the commit message editor.
```bash
git commit -v
```

---

## 69. git fetch --prune
Removes branches that no longer exist on the remote.
```bash
git fetch --prune
```

---

## 70. git stash pop
Applies the top stash and removes it from the stash list.
```bash
git stash pop
```

---

## 71. git stash drop
Removes a specific stash entry.
```bash
git stash drop <stash@{N}>
```

---

## 72. git log --since
Shows commits made after a specified time.
```bash
git log --since="2 days ago"
```

---

## 73. git commit --no-edit
Commits changes without opening an editor.
```bash
git commit --no-edit
```

---

## 74. git grep -i
Case-insensitive search within files.
```bash
git grep -i "search-term"
```

---

## 75. git show :/<message>
Shows the commit with the specified message.
```bash
git show :/"commit message"
```

---

## 76. git diff HEAD^ HEAD
Compares the last two commits.
```bash
git diff HEAD^ HEAD
```

---

## 77. git fetch --depth
Limits the number of commits fetched.
```bash
git fetch --depth=1
```

---

## 78. git log --author
Shows commits from a specific author.
```bash
git log --author="Author Name"
```

---

## 79. git commit --allow-empty
Creates an empty commit.
```bash
git commit --allow-empty -m "Empty commit"
```

---

## 80. git log --pretty
Formats the output of the commit history.
```bash
git log --pretty=format:"%h - %an, %ar : %s"
```

---
