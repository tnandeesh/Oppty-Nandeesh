Basic Git Commands

Git is your code time machine. It tracks every change, enables team collaboration without
conflicts, and lets you undo mistakes. These commands help manage source code versions
like a professional developer.

1. git init
Initializes a new Git repository in the current directory.
Example: git init

2. git clone
Copies a remote repository to the local machine.
Example: git clone https://github.com/user/repo.git

3. git status
Displays the state of the working directory and staging area.
Example: git status

4. git add
Adds changes to the staging area.
Example: git add file.txt

5. git commit
Records changes to the repository.
Example: git commit -m "Initial commit"

6. git config
Configures user settings, such as name and email.
Example: git config --global user.name "Your Name"

7. git log
Shows the commit history.
Example: git log

8. git show
Displays detailed information about a specific commit.
Example: git show <commit-hash>

9. git diff
Shows changes between commits, the working directory, and the staging area.
Example: git diff

10. git reset
Unstages changes or resets commits.
Example: git reset HEAD file.txt

Branching and Merging

11. git branch
Lists branches or creates a new branch.
Example: git branch feature-branch

12. git checkout
Switches between branches or restores files.
Example: git checkout feature-branch

13. git switch
Switches branches (modern alternative to git checkout).
Example: git switch feature-branch

14. git merge
Combines changes from one branch into another.
Example: git merge feature-branch

15. git rebase
Moves or combines commits from one branch onto another.
Example: git rebase main

16. git cherry-pick
Applies specific commits from one branch to another.
Example: git cherry-pick <commit-hash>

Remote Repositories

17. git remote
Manages remote repository connections.
Example: git remote add origin https://github.com/user/repo.git

18. git push
Sends changes to a remote repository.
Example: git push origin main

19. git pull
Fetches and merges changes from a remote repository.
Example: git pull origin main

20. git fetch
Downloads changes from a remote repository without merging.
Example: git fetch origin

21. git remote -v
Lists the URLs of remote repositories.
Example: git remote -v

Stashing and Cleaning

22. git stash
Temporarily saves changes not yet committed.
Example: git stash

23. git stash pop
Applies stashed changes and removes them from the stash list.
Example: git stash pop

24. git stash list
Lists all stashes.
Example: git stash list

25. git clean
Removes untracked files from the working directory.
Example: git clean -f

Tagging

26. git tag
Creates a tag for a specific commit.
Example: git tag -a v1.0 -m "Version 1.0"

27. git tag -d
Deletes a tag.
Example: git tag -d v1.0

28. git push --tags
Pushes tags to a remote repository.
Example: git push origin --tags

Advanced Commands

29. git bisect
Finds the commit that introduced a bug.
Example: git bisect start

30. git blame
Shows which commit and author modified each line of a file.
Example: git blame file.txt

31. git reflog
Shows a log of changes to the tip of branches.
Example: git reflog

32. git submodule
Manages external repositories as submodules.
Example: git submodule add https://github.com/user/repo.git

33. git archive
Creates an archive of the repository files.
Example: git archive --format=zip HEAD > archive.zip

34. git gc
Cleans up unnecessary files and optimizes the repository.
Example: git gc

GitHub-Specific Commands

35. gh auth login
Logs into GitHub via the command line.
Example: gh auth login

36. gh repo clone
Clones a GitHub repository.
Example: gh repo clone user/repo

37. gh issue list
Lists issues in a GitHub repository.
Example: gh issue list

38. gh pr create
Creates a pull request on GitHub.
Example: gh pr create --title "New Feature" --body "Description of the feature"

39. gh repo create
Creates a new GitHub repository.
Example: gh repo create my-repo
