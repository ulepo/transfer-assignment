# How to use `git`
1. Initialize a repository with `git init`
2. Stage your files with `git add <filename> ` or `git add .` to stage every file change
3. Whenever you made a substantial change, put it into the history with `git commit -m "comment"`
4. See your history with `git log`
5. Move around (history and branches!) with `git checkout <commitID>` to move around history or `git checkout <branchname>` to move to the head of branchname (or git switch for jumping inbetween branches)
6. Create new branches with `git checkout -b <new-branch-name>` creates new branch from any current location (be it on HEAD or not..), and switches to it (`git switch -c <new-b-name>` )
7. To collaborate, first `git pull` others changes, then `git push` yours