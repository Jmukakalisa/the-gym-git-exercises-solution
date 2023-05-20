# GIT EXERCISES

This is a readme file where you can find all details of this project

'''bash
andelarwanda@Andelas-MacBook-Pro git-exercise % git init
Initialized empty Git repository in /Users/andelarwanda/Desktop/git-exercise/.git/
andelarwanda@Andelas-MacBook-Pro git-exercise % git status
On branch main

No commits yet

nothing to commit (create/copy files and use "git add" to track)
andelarwanda@Andelas-MacBook-Pro git-exercise % git branch -M master
andelarwanda@Andelas-MacBook-Pro git-exercise % git status
On branch master

No commits yet

nothing to commit (create/copy files and use "git add" to track)
andelarwanda@Andelas-MacBook-Pro git-exercise % git branch -M main  
andelarwanda@Andelas-MacBook-Pro git-exercise % git add readme.md
andelarwanda@Andelas-MacBook-Pro git-exercise % git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   readme.md

andelarwanda@Andelas-MacBook-Pro git-exercise % git commit -m "ch(): initial project commit"
[main (root-commit) cf746a2] ch(): initial project commit
 1 file changed, 3 insertions(+)
 create mode 100644 readme.md
andelarwanda@Andelas-MacBook-Pro git-exercise % git remote add origin https://github.com/Jmukakalisa/the-gym-git-exercises-solution.git
andelarwanda@Andelas-MacBook-Pro git-exercise % git push
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

andelarwanda@Andelas-MacBook-Pro git-exercise % git push --set-upstream origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 307 bytes | 307.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Jmukakalisa/the-gym-git-exercises-solution.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
andelarwanda@Andelas-MacBook-Pro git-exercise % git checkout -b develop
Switched to a new branch 'develop'
andelarwanda@Andelas-MacBook-Pro git-exercise % git status
On branch develop
nothing to commit, working tree clean
andelarwanda@Andelas-MacBook-Pro git-exercise % git push 
fatal: The current branch develop has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin develop

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

andelarwanda@Andelas-MacBook-Pro git-exercise % git push --set-upstream origin develop
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'develop' on GitHub by visiting:
remote:      https://github.com/Jmukakalisa/the-gym-git-exercises-solution/pull/new/develop
remote: 
To https://github.com/Jmukakalisa/the-gym-git-exercises-solution.git
 * [new branch]      develop -> develop
branch 'develop' set up to track 'origin/develop'.
andelarwanda@Andelas-MacBook-Pro git-exercise % git checkout -b test
Switched to a new branch 'test'
andelarwanda@Andelas-MacBook-Pro git-exercise % git push origin test
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'test' on GitHub by visiting:
remote:      https://github.com/Jmukakalisa/the-gym-git-exercises-solution/pull/new/test
remote: 
To https://github.com/Jmukakalisa/the-gym-git-exercises-solution.git
 * [new branch]      test -> test
andelarwanda@Andelas-MacBook-Pro git-exercise % git checkout develop
Switched to branch 'develop'
Your branch is up to date with 'origin/develop'.
andelarwanda@Andelas-MacBook-Pro git-exercise % git branch -D test
Deleted branch test (was cf746a2).
andelarwanda@Andelas-MacBook-Pro git-exercise % git push origin --delete test
To https://github.com/Jmukakalisa/the-gym-git-exercises-solution.git
 - [deleted]         test
andelarwanda@Andelas-MacBook-Pro git-exercise % 
'''