# week1ProjectPS
Week 1 Assignment
## 1.Github
i.

```
Microsoft Windows [Version 10.0.19042.985]
(c) Microsoft Corporation. All rights reserved.
```
```
C:\Users\User>F:
```
```
F:\>cd psProject
```
```
F:\psProject>mkdir week1ProjectPS
```
```
F:\psProject>cd week1ProjectPS
```
```
F:\psProject\week1ProjectPS>git init
Initialized empty Git repository in F:/psProject/week1ProjectPS/.git/
```
```
F:\psProject\week1ProjectPS>code helloWorld.cpp
```
```
F:\psProject\week1ProjectPS>code .gitignore
```
```
F:\psProject\week1ProjectPS>git add -A
```
```
F:\psProject\week1ProjectPS>git commit -m "Initial Commit"
[master (root-commit) b738e35] Initial Commit
2 files changed, 8 insertions(+)
create mode 100644 .gitignore
create mode 100644 helloWorld.cpp
```
```
F:\psProject\week1ProjectPS>git status
On branch master
nothing to commit, working tree clean
```
ii.

```
F:\psProject\week1ProjectPS>git remote add origin
https://github.com/souravmondaldev/week1ProjectPS.git
```
```
F:\psProject\week1ProjectPS>git branch -M main
```
```
F:\psProject\week1ProjectPS>git push -u origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (4/4), 366 bytes | 366.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/souravmondaldev/week1ProjectPS.git
* [new branch] main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.
```

iii.

```
F:\psProject\week1ProjectPS>git branch Feature
```
```
F:\psProject\week1ProjectPS>git branch Dev
```
```
F:\psProject\week1ProjectPS>git branch QA
```
```
F:\psProject\week1ProjectPS>git branch
Dev
Feature
QA
* main
```
```
F:\psProject\week1ProjectPS>git push origin Feature
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'Feature' on GitHub by visiting:
remote:
https://github.com/souravmondaldev/week1ProjectPS/pull/new/Feature
remote:
To https://github.com/souravmondaldev/week1ProjectPS.git
* [new branch] Feature -> Feature
```
```
F:\psProject\week1ProjectPS>git push origin Dev
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'Dev' on GitHub by visiting:
remote: https://github.com/souravmondaldev/week1ProjectPS/pull/new/Dev
remote:
To https://github.com/souravmondaldev/week1ProjectPS.git
* [new branch] Dev -> Dev
```
```
F:\psProject\week1ProjectPS>git push origin QA
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'QA' on GitHub by visiting:
remote: https://github.com/souravmondaldev/week1ProjectPS/pull/new/QA
remote:
To https://github.com/souravmondaldev/week1ProjectPS.git
* [new branch] QA -> QA
F:\psProject\week1ProjectPS>git push origin -u Feature
Everything up-to-date
Branch 'Feature' set up to track remote branch 'Feature' from 'origin'.
```
```
F:\psProject\week1ProjectPS>git push origin -u Dev
Everything up-to-date
Branch 'Dev' set up to track remote branch 'Dev' from 'origin'.
```
```
F:\psProject\week1ProjectPS>git push origin -u QA
```

```
Everything up-to-date
Branch 'QA' set up to track remote branch 'QA' from 'origin'.
```
Iv

## . SEE THE PDF INSIDE REPO 

v.

```
F:\psProject\week1ProjectPS>git status
On branch main
Your branch is up to date with 'origin/main'.
```
```
nothing to commit, working tree clean
```
```
F:\psProject\week1ProjectPS>code helloWorld.py
```
```
F:\psProject\week1ProjectPS>git add -A
```
```
F:\psProject\week1ProjectPS>git commit -m "Second Commit"
[main 9fb19b4] Second Commit
1 file changed, 1 insertion(+)
create mode 100644 helloWorld.py
```
```
F:\psProject\week1ProjectPS>mkdir newFolder
```
```
F:\psProject\week1ProjectPS>mkdir newFolder
```
```
F:\psProject\week1ProjectPS>code helloWorld.cpp
```
```
F:\psProject\week1ProjectPS>git add -A
```
```
F:\psProject\week1ProjectPS>git commit -m "Third Commit"
[main b3e6f66] Third Commit
1 file changed, 1 insertion(+), 1 deletion(-)
```
vi.

```
F:\psProject\week1ProjectPS>git checkout Feature
Switched to branch 'Feature'
```

```
F:\psProject\week1ProjectPS>mkdir emptyFolder
```
```
F:\psProject\week1ProjectPS>code sayHi.py
```
```
F:\psProject\week1ProjectPS>git add -A
```
```
F:\psProject\week1ProjectPS>git status
On branch Feature
Changes to be committed:
(use "git restore --staged <file>..." to unstage)
new file: sayHi.py
```
```
F:\psProject\week1ProjectPS>git push
Everything up-to-date
```
```
F:\psProject\week1ProjectPS>git status
On branch Feature
Your branch is up to date with 'origin/Feature'.
```
```
Changes to be committed:
(use "git restore --staged <file>..." to unstage)
new file: sayHi.py
```
```
F:\psProject\week1ProjectPS>git commit -m "adding to feature"
[Feature 4a27226] adding to feature
1 file changed, 1 insertion(+)
create mode 100644 sayHi.py
```
```
F:\psProject\week1ProjectPS>git status
On branch Feature
Your branch is ahead of 'origin/Feature' by 1 commit.
(use "git push" to publish your local commits)
```
```
nothing to commit, working tree clean
```
```
F:\psProject\week1ProjectPS>git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 335 bytes | 335.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/souravmondaldev/week1ProjectPS.git
b738e35..4a27226 Feature -> Feature
```
Vii.viii ix x


x.

```
F:\psProject\week1ProjectPS>git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 2 commits.
(use "git push" to publish your local commits)
```
```
F:\psProject\week1ProjectPS>git pull
```

```
remote: Enumerating objects: 2, done.
remote: Counting objects: 100% (2/2), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 2 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (2/2), 1.21 KiB | 20.00 KiB/s, done.
From https://github.com/souravmondaldev/week1ProjectPS
b738e35..155b832 main -> origin/main
* [new branch] Delivery -> origin/Delivery
b738e35..25a7697 Dev -> origin/Dev
* [new branch] Master -> origin/Master
Merge made by the 'recursive' strategy.
sayHi.py | 1 +
1 file changed, 1 insertion(+)
create mode 100644 sayHi.py
```
## 3.

```
F:\psProject\week1ProjectPS>git status
On branch main
Your branch is ahead of 'origin/main' by 3 commits.
(use "git push" to publish your local commits)
```
```
Untracked files:
(use "git add <file>..." to include in what will be committed)
txt1.txt
txt2.txt
```
```
nothing added to commit but untracked files present (use "git add" to
track)
```
```
F:\psProject\week1ProjectPS>git add txt1.txt
```
```
F:\psProject\week1ProjectPS>git status
On branch main
Your branch is ahead of 'origin/main' by 3 commits.
(use "git push" to publish your local commits)
```
```
Changes to be committed:
(use "git restore --staged <file>..." to unstage)
new file: txt1.txt
```
```
Untracked files:
(use "git add <file>..." to include in what will be committed)
txt2.txt
```
```
F:\psProject\week1ProjectPS>git ls-files -s
100644 3110669356d6b6639a52e71cd8f9d500e55b881b 0 .gitignore
100644 3ca941986eb6fa07248fd88a52fa6f6ceb44406f 0 helloWorld.cpp
100644 1dc45ac13680332bc368aa383fec751aed9e6220 0 helloWorld.py
100644 56f0d11580322627f6973148e457acb98cfba631 0 sayHi.py
100644 e69de29bb2d1d6434b8b29ae775ad8c2e48c5391 0 txt1.txt
```
```
F:\psProject\week1ProjectPS>git reset --hard
HEAD is now at 02844e4 Merge branch 'main' of
https://github.com/souravmondaldev/week1ProjectPS
```
```
F:\psProject\week1ProjectPS>git ls-files -s
100644 3110669356d6b6639a52e71cd8f9d500e55b881b 0 .gitignore
100644 3ca941986eb6fa07248fd88a52fa6f6ceb44406f 0 helloWorld.cpp
100644 1dc45ac13680332bc368aa383fec751aed9e6220 0 helloWorld.py
100644 56f0d11580322627f6973148e457acb98cfba631 0 sayHi.py
```
```
F:\psProject\week1ProjectPS>git add txt2.txt
```
```
F:\psProject\week1ProjectPS>git ls-files -s
100644 3110669356d6b6639a52e71cd8f9d500e55b881b 0 .gitignore
100644 3ca941986eb6fa07248fd88a52fa6f6ceb44406f 0 helloWorld.cpp
100644 1dc45ac13680332bc368aa383fec751aed9e6220 0 helloWorld.py
100644 56f0d11580322627f6973148e457acb98cfba631 0 sayHi.py
100644 e69de29bb2d1d6434b8b29ae775ad8c2e48c5391 0 txt2.txt
```
```
F:\psProject\week1ProjectPS>git reset --soft
```
```
F:\psProject\week1ProjectPS>git ls-files -s
100644 3110669356d6b6639a52e71cd8f9d500e55b881b 0 .gitignore
100644 3ca941986eb6fa07248fd88a52fa6f6ceb44406f 0 helloWorld.cpp
100644 1dc45ac13680332bc368aa383fec751aed9e6220 0 helloWorld.py
100644 56f0d11580322627f6973148e457acb98cfba631 0 sayHi.py
100644 e69de29bb2d1d6434b8b29ae775ad8c2e48c5391 0 txt2.txt
```
```
F:\psProject\week1ProjectPS>git status
On branch main
Your branch is ahead of 'origin/main' by 3 commits.
(use "git push" to publish your local commits)

Changes to be committed:
(use "git restore --staged <file>..." to unstage)
new file: txt2.txt
```
```
F:\psProject\week1ProjectPS>git stash
Saved working directory and index state WIP on main: 02844e4 Merge branch
'main' of https://github.com/souravmondaldev/week1ProjectPS
```
```
F:\psProject\week1ProjectPS>git rebase
Successfully rebased and updated refs/heads/main.
```
```
F:\psProject\week1ProjectPS>git log

Date: Sat May 29 10:31:39 2021 +

```
Third Commit
```
commit 26fd9f27c58373c3d255c93473c13db24c8e04b
Author: Sourav Mondal <souravmondal0341@gmail.com>
Date: Sat May 29 10:20:42 2021 +

```
Second Commit
```
commit 155b83288dba35ee6bbe0076017f08b06dcd7fdc (origin/main)
Merge: b738e35 4a
Author: Sourav Mondal <souravmondal0341@gmail.com>
Date: Sat May 29 10:44:06 2021 +

```
Merge pull request #1 from souravmondaldev/Feature
```
```
adding to feature
```
commit 4a27226bfdbf02a38a779ed01c5ad987f9b6ed8a (origin/Feature, Feature)
Author: Sourav Mondal <souravmondal0341@gmail.com>
Date: Sat May 29 10:40:40 2021 +

```
adding to feature
```
commit b738e3539bf2a9167bb686cdbe28345036ffe962 (origin/QA, origin/Master,
origin/Delivery, QA, Dev)
Author: Sourav Mondal <souravmondal0341@gmail.com>
Date: Sat May 29 10:02:00 2021 +

Initial Commit
F:\psProject\week1ProjectPS>git status
On branch main
Your branch is ahead of 'origin/main' by 2 commits.
(use "git push" to publish your local commits)

nothing to commit, working tree clean

F:\psProject\week1ProjectPS>git reflog
de6560f (HEAD -> main) HEAD@{0}: rebase (finish): returning to
refs/heads/main
de6560f (HEAD -> main) HEAD@{1}: rebase (pick): Third Commit
26fd9f2 HEAD@{2}: rebase (pick): Second Commit
155b832 (origin/main) HEAD@{3}: rebase (start): checkout
refs/remotes/origin/main
02844e4 HEAD@{4}: reset: moving to HEAD
02844e4 HEAD@{5}: reset: moving to HEAD
02844e4 HEAD@{6}: reset: moving to HEAD
02844e4 HEAD@{7}: pull: Merge made by the 'recursive' strategy.


b3e6f66 HEAD@{8}: checkout: moving from Feature to main
4a27226 (origin/Feature, Feature) HEAD@{9}: commit: adding to feature
b738e35 (origin/QA, origin/Master, origin/Delivery, QA, Dev) HEAD@{10}:
checkout: moving from main to Feature
b3e6f66 HEAD@{11}: commit: Third Commit
9fb19b4 HEAD@{12}: commit: Second Commit

b738e35 (origin/QA, origin/Master, origin/Delivery, QA, Dev) HEAD@{13}:
Branch: renamed refs/heads/master to refs/heads/main
b738e35 (origin/QA, origin/Master, origin/Delivery, QA, Dev) HEAD@{15}:
commit (initial): Initial Commit
```

