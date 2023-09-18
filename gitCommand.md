# Git Commands

1. **Initializing a Repository:**
   - `git init`: Initializes a new Git repository in the current directory.

2. **Cloning a Repository:**
   - `git clone <repository_url>`: Creates a copy of a remote Git repository on your local machine.

3. **Basic Snapshotting:**
   - `git add <file>`: Stages a file for commit.
   - `git add .` or `git add --all`: Stages all changes for commit.
   - `git reset <file>`: Unstages a file.

4. **Committing Changes:**
   - `git commit -m "Commit message"`: Records staged changes into the repository with a descriptive message.

5. **Viewing Commit History:**
   - `git log`: Displays a log of all commits in the current branch.
   - `git log --oneline`: Displays a concise one-line log.
   - `git log --graph`: Shows a graphical representation of commit history.

6. **Branches:**
   - `git branch`: Lists all local branches.
   - `git branch <branch_name>`: Creates a new branch.
   - `git checkout <branch_name>`: Switches to a different branch.
   - `git merge <branch_name>`: Merges changes from one branch into the current branch.

7. **Remote Repositories:**
   - `git remote -v`: Lists all remote repositories.
   - `git remote add <remote_name> <repository_url>`: Adds a new remote repository.
   - `git pull <remote_name> <branch_name>`: Fetches and merges changes from a remote repository.
   - `git push <remote_name> <branch_name>`: Pushes local changes to a remote repository.

8. **Working with Tags:**
   - `git tag`: Lists all tags in the repository.
   - `git tag <tag_name>`: Creates a new annotated tag.
   - `git push --tags`: Pushes tags to a remote repository.

9. **Resolving Merge Conflicts:**
   - When a merge conflict occurs, you'll need to manually resolve it by editing the conflicted files and then:
     - `git add <conflicted_file>`: Stages the resolved file.
     - `git commit -m "Merge conflict resolution"`: Commits the resolved changes.

10. **Undoing Changes:**
    - `git reset <commit>`: Resets to a specific commit, discarding all changes after it.
    - `git checkout -- <file>`: Discards changes in a specific file.
    - `git revert <commit>`: Creates a new commit that undoes changes from a specific commit.

11. **Miscellaneous:**
    - `git status`: Displays the status of the working directory.
    - `git diff`: Shows the differences between the working directory and the last commit.
    - `git stash`: Temporarily saves changes that are not ready to be committed.
    - `git clean -n` and `git clean -f`: Lists and removes untracked files, respectively.

These are some of the most commonly used Git commands, but Git has a wide range of functionalities and options. You can use `git --help` or `git <command> --help` for more detailed information about each command and its options.
