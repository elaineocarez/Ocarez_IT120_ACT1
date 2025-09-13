
ADMIN PC@DESKTOP-ETH8KGU MINGW64 ~
$ cd Desktop

ADMIN PC@DESKTOP-ETH8KGU MINGW64 ~/Desktop
$ mkdir Ocarez_IT120_ACT1

ADMIN PC@DESKTOP-ETH8KGU MINGW64 ~/Desktop
$ cd Ocarez_IT120_ACT1

ADMIN PC@DESKTOP-ETH8KGU MINGW64 ~/Desktop/Ocarez_IT120_ACT1
$ git init
Initialized empty Git repository in C:/Users/ADMIN PC/Desktop/Ocarez_IT120_ACT1/
.git/

ADMIN PC@DESKTOP-ETH8KGU MINGW64 ~/Desktop/Ocarez_IT120_ACT1 (master)
$ git remote add origin https://github.com/elaineocarez/Ocarez_IT120_ACT1.git

ADMIN PC@DESKTOP-ETH8KGU MINGW64 ~/Desktop/Ocarez_IT120_ACT1 (master)
$ touch Profile.txt Education.txt Background.txt Readme.txt Test.py

ADMIN PC@DESKTOP-ETH8KGU MINGW64 ~/Desktop/Ocarez_IT120_ACT1 (master)
$

 git add .

ADMIN PC@DESKTOP-ETH8KGU MINGW64 ~/Desktop/Ocarez_IT120_ACT1 (master)
$ git commit -m "Initial commit with all files"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'ADMIN PC@DESKTOP-ETH8KGU.(none)')

ADMIN PC@DESKTOP-ETH8KGU MINGW64 ~/Desktop/Ocarez_IT120_ACT1 (master)
$ git config --global user.name "elaineocarez"

ADMIN PC@DESKTOP-ETH8KGU MINGW64 ~/Desktop/Ocarez_IT120_ACT1 (master)
$ git config --global user.email "elaine.ocarez@gmail.com"

ADMIN PC@DESKTOP-ETH8KGU MINGW64 ~/Desktop/Ocarez_IT120_ACT1 (master)
$ git config --list
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=schannel
core.autocrlf=true
core.fscache=true
core.symlinks=false
pull.rebase=false
credential.helper=manager
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
user.name=elaineocarez
user.email=elaine.ocarez@gmail.com
core.repositoryformatversion=0
core.filemode=false
core.bare=false
core.logallrefupdates=true
core.symlinks=false
core.ignorecase=true
remote.origin.url=https://github.com/elaineocarez/Ocarez_IT120_ACT1.git
remote.origin.fetch=+refs/heads/*:refs/remotes/origin/*

ADMIN PC@DESKTOP-ETH8KGU MINGW64 ~/Desktop/Ocarez_IT120_ACT1 (master)
$ git commit -m "Initial commit with all files"
[master (root-commit) b797abf] Initial commit with all files
 5 files changed, 39 insertions(+)
 create mode 100644 Background.txt
 create mode 100644 Education.txt
 create mode 100644 Profile.txt
 create mode 100644 Readme.txt
 create mode 100644 Test.py

ADMIN PC@DESKTOP-ETH8KGU MINGW64 ~/Desktop/Ocarez_IT120_ACT1 (master)
$ git remote -v
origin  https://github.com/elaineocarez/Ocarez_IT120_ACT1.git (fetch)
origin  https://github.com/elaineocarez/Ocarez_IT120_ACT1.git (push)

ADMIN PC@DESKTOP-ETH8KGU MINGW64 ~/Desktop/Ocarez_IT120_ACT1 (master)
$ git push origin master
info: please complete authentication in your browser...
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 12 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (7/7), 948 bytes | 948.00 KiB/s, done.
Total 7 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/elaineocarez/Ocarez_IT120_ACT1.git
 * [new branch]      master -> master

ADMIN PC@DESKTOP-ETH8KGU MINGW64 ~/Desktop/Ocarez_IT120_ACT1 (master)
$ git branch -M master

ADMIN PC@DESKTOP-ETH8KGU MINGW64 ~/Desktop/Ocarez_IT120_ACT1 (master)
$ git push -u origin master
branch 'master' set up to track 'origin/master'.
Everything up-to-date

ADMIN PC@DESKTOP-ETH8KGU MINGW64 ~/Desktop/Ocarez_IT120_ACT1 (master)
$ git checkout -b Ocarez_B1
Switched to a new branch 'Ocarez_B1'

ADMIN PC@DESKTOP-ETH8KGU MINGW64 ~/Desktop/Ocarez_IT120_ACT1 (Ocarez_B1)
$ git branch
* Ocarez_B1
  master

ADMIN PC@DESKTOP-ETH8KGU MINGW64 ~/Desktop/Ocarez_IT120_ACT1 (Ocarez_B1)
$ git add Profile.txt

ADMIN PC@DESKTOP-ETH8KGU MINGW64 ~/Desktop/Ocarez_IT120_ACT1 (Ocarez_B1)
$ git commit -m "Amend: added Birth of Place, Religion, Father's Occupation, Mother's Name, Occupation,Father's Name"
[Ocarez_B1 9797d22] Amend: added Birth of Place, Religion, Father's Occupation, Mother's Name, Occupation,Father's Name
 1 file changed, 8 insertions(+), 1 deletion(-)

ADMIN PC@DESKTOP-ETH8KGU MINGW64 ~/Desktop/Ocarez_IT120_ACT1 (Ocarez_B1)
$ git push origin Ocarez_B1
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 507 bytes | 507.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'Ocarez_B1' on GitHub by visiting:
remote:      https://github.com/elaineocarez/Ocarez_IT120_ACT1/pull/new/Ocarez_B1
remote:
To https://github.com/elaineocarez/Ocarez_IT120_ACT1.git
 * [new branch]      Ocarez_B1 -> Ocarez_B1

ADMIN PC@DESKTOP-ETH8KGU MINGW64 ~/Desktop/Ocarez_IT120_ACT1 (Ocarez_B1)
$ git checkout master
Switched to branch 'master'
Your branch is up to date with 'origin/master'.

ADMIN PC@DESKTOP-ETH8KGU MINGW64 ~/Desktop/Ocarez_IT120_ACT1 (master)
$ git checkout -b Ocarez_B2
Switched to a new branch 'Ocarez_B2'

ADMIN PC@DESKTOP-ETH8KGU MINGW64 ~/Desktop/Ocarez_IT120_ACT1 (Ocarez_B2)
$ git add Education.txt

ADMIN PC@DESKTOP-ETH8KGU MINGW64 ~/Desktop/Ocarez_IT120_ACT1 (Ocarez_B2)
$ git commit -m "Amend: updated Education.txt"
[Ocarez_B2 ac8a242] Amend: updated Education.txt
 1 file changed, 5 insertions(+), 1 deletion(-)

ADMIN PC@DESKTOP-ETH8KGU MINGW64 ~/Desktop/Ocarez_IT120_ACT1 (Ocarez_B2)
$ git push origin Ocarez_B2
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 461 bytes | 461.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'Ocarez_B2' on GitHub by visiting:
remote:      https://github.com/elaineocarez/Ocarez_IT120_ACT1/pull/new/Ocarez_B2
remote:
To https://github.com/elaineocarez/Ocarez_IT120_ACT1.git
 * [new branch]      Ocarez_B2 -> Ocarez_B2

