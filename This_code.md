Asus@DESKTOP-KO306E3 MINGW64 ~/Desktop
$ mkdir "Create_gitBash"

Asus@DESKTOP-KO306E3 MINGW64 ~/Desktop
$ touch This_code.md

Asus@DESKTOP-KO306E3 MINGW64 ~/Desktop
$ cd C^C

Asus@DESKTOP-KO306E3 MINGW64 ~/Desktop
$ cd Create_gitBash

Asus@DESKTOP-KO306E3 MINGW64 ~/Desktop/Create_gitBash
$ touch This_code.md

Asus@DESKTOP-KO306E3 MINGW64 ~/Desktop/Create_gitBash
$ touch Details.md

Asus@DESKTOP-KO306E3 MINGW64 ~/Desktop/Create_gitBash
$ git int
git: 'int' is not a git command. See 'git --help'.

The most similar command is
        init

Asus@DESKTOP-KO306E3 MINGW64 ~/Desktop/Create_gitBash
$ git init
Initialized empty Git repository in C:/Users/Asus/Desktop/Create_gitBash/.git/

Asus@DESKTOP-KO306E3 MINGW64 ~/Desktop/Create_gitBash (master)
$ git add ^C

Asus@DESKTOP-KO306E3 MINGW64 ~/Desktop/Create_gitBash (master)
$ git add This_code.md

Asus@DESKTOP-KO306E3 MINGW64 ~/Desktop/Create_gitBash (master)
$ git add Details.md

Asus@DESKTOP-KO306E3 MINGW64 ~/Desktop/Create_gitBash (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   Details.md
        new file:   This_code.md


Asus@DESKTOP-KO306E3 MINGW64 ~/Desktop/Create_gitBash (master)
$ git add .

Asus@DESKTOP-KO306E3 MINGW64 ~/Desktop/Create_gitBash (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   Details.md
        new file:   This_code.md


Asus@DESKTOP-KO306E3 MINGW64 ~/Desktop/Create_gitBash (master)
$ git commit
[master (root-commit) 8247471]  Initial commit
 2 files changed, 367 insertions(+)
 create mode 100644 Details.md
 create mode 100644 This_code.md

Asus@DESKTOP-KO306E3 MINGW64 ~/Desktop/Create_gitBash (master)
$ git status
On branch master
nothing to commit, working tree clean

Asus@DESKTOP-KO306E3 MINGW64 ~/Desktop/Create_gitBash (master)
$ ^C

Asus@DESKTOP-KO306E3 MINGW64 ~/Desktop/Create_gitBash (master)
$ git add .

Asus@DESKTOP-KO306E3 MINGW64 ~/Desktop/Create_gitBash (master)
$ git commit -m 'This_code"
> '
> [master d5ab861] This_code"
>  1 file changed, 79 insertions(+)

Asus@DESKTOP-KO306E3 MINGW64 ~/Desktop/Create_gitBash (master)
$ git merge login
merge: login - not something we can merge

Asus@DESKTOP-KO306E3 MINGW64 ~/Desktop/Create_gitBash (master)
$ git remote

Asus@DESKTOP-KO306E3 MINGW64 ~/Desktop/Create_gitBash (master)
$ git remote add origin https://github.com/Agastyarathee/Learn_GitBash.git

Asus@DESKTOP-KO306E3 MINGW64 ~/Desktop/Create_gitBash (master)
$ git remote
origin

Asus@DESKTOP-KO306E3 MINGW64 ~/Desktop/Create_gitBash (master)
$ git push -u origin master
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (7/7), 4.06 KiB | 1.02 MiB/s, done.
Total 7 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Agastyarathee/Learn_GitBash.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.

Asus@DESKTOP-KO306E3 MINGW64 ~/Desktop/Create_gitBash (master)
$