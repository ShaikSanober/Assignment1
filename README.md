# Assignment1

Here are some common Git commands and their uses:

1. *git init*
   - Initializes a new Git repository.

2. *git clone "repository-url"*
   - Clones a repository from a remote URL to your local machine.

3. *git add "file"*  OR  *git add .*
   - Adds changes in a file to the staging area.

4. *git commit -m "Commit message"*
   - Commits changes in the staging area with a descriptive message.

5. *git status*
   - Shows the status of changes as untracked, modified, or staged.

6. *git log*
   - Displays a log of commits, including commit hashes, authors, and messages.

7.  *git pull -u origin main* OR *git pull -u "remote/origin" "branch"*
   - Fetches changes from a remote repository and merges them into the current branch 
     (-u)for tracking relationship, can use only once after that simply can use only *git pull*.

8. - *git push -u origin main* OR *git push -u "remote/origin" "branch"*
   - Pushes local changes to a remote repository.
     (-u)for tracking relationship, can use only once after that simply can use only *git push*.

9. *git remote add origin "url"* 
   - link your local repo to the remote repo.
   - use before pushing or pulling anything from remote to local system.

10. *git remote -v*
    - Shows information about remote repositories.   

11. *git branch*
   - Lists all branches in the repository.

12. *git branch "new-branch-name"*
   - To create a new branch.

13. *git branch -d "branch-name"*
   - To delete a branch.


14. *git checkout "branch-name"*
    - Switches to a different branch.

15. *git merge "branch-name"*
    - Merges changes from one branch into the current branch.


16. *git fetch*
    - Downloads objects and refs from another repository.

17. *git reset "file-name"*
    - Unstages changes in a file.

18. *git revert "commit-hash"*
    - Creates a new commit that undoes the changes made in a previous commit.

19. *git stash*
    - Temporarily saves changes that are not ready to be committed.

20. *git tag*
    - Lists tags in the repository.

21. *git config --global user.name "Your Name"*
    - Sets your username globally for Git.

22. *git config --global user.email "your.email@example.com"*
    - Sets your email globally for Git.

