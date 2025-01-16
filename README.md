shis@BLUEPEARL MINGW64 ~/Downloads/DataScience Training/GITHUBSERIES
$ git init
Initialized empty Git repository in C:/Users/ashis/Downloads/DataScience Training/GITHUBSERIES/.git/
(base)
ashis@BLUEPEARL MINGW64 ~/Downloads/DataScience Training/GITHUBSERIES (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md.txt

nothing added to commit but untracked files present (use "git add" to track)
(base)
ashis@BLUEPEARL MINGW64 ~/Downloads/DataScience Training/GITHUBSERIES (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md

nothing added to commit but untracked files present (use "git add" to track)
(base)
ashis@BLUEPEARL MINGW64 ~/Downloads/DataScience Training/GITHUBSERIES (master)
$ git add .
(base)
ashis@BLUEPEARL MINGW64 ~/Downloads/DataScience Training/GITHUBSERIES (master)
$ git commit -m "First Commit"
[master (root-commit) 3d899ca] First Commit
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 README.md
(base)
ashis@BLUEPEARL MINGW64 ~/Downloads/DataScience Training/GITHUBSERIES (master)
$ git status
On branch master
nothing to commit, working tree clean
(base)
ashis@BLUEPEARL MINGW64 ~/Downloads/DataScience Training/GITHUBSERIES (master)
$ git branch
* master
(base)
ashis@BLUEPEARL MINGW64 ~/Downloads/DataScience Training/GITHUBSERIES (master)
$ git branch -M main
(base)
ashis@BLUEPEARL MINGW64 ~/Downloads/DataScience Training/GITHUBSERIES (main)
$ git branch
* main
(base)
ashis@BLUEPEARL MINGW64 ~/Downloads/DataScience Training/GITHUBSERIES (main)
$ git remote add origin https://github.com/ashissahu/GITTUTORIALS.git
(base)
ashis@BLUEPEARL MINGW64 ~/Downloads/DataScience Training/GITHUBSERIES (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 215 bytes | 215.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/ashissahu/GITTUTORIALS.git
 * [new branch]      main -> main
(base)
ashis@BLUEPEARL MINGW64 ~/Downloads/DataScience Training/GITHUBSERIES (main)
$
