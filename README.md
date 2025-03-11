
Osward@LAPTOP-OSWARD84C MINGW64 ~/Desktop/PLPBasicGitAssignment (master)
$ git init
Reinitialized existing Git repository in C:/Users/Osward/Desktop/PLPBasicGitAssi
gnment/.git/

Osward@LAPTOP-OSWARD84C MINGW64 ~/Desktop/PLPBasicGitAssignment (master)
$ git add .

Osward@LAPTOP-OSWARD84C MINGW64 ~/Desktop/PLPBasicGitAssignment (master)
$ git commit -m "first commit!"
[master (root-commit) 9069059] first commit!
 3 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Desktop/Hello.Git!.txt
 create mode 100644 Desktop/hello.txt.txt
 create mode 100644 Hello.txt.txt

Osward@LAPTOP-OSWARD84C MINGW64 ~/Desktop/PLPBasicGitAssignment (master)
$ git remote add origin https://github.com/Umuntu11/nothing-int.git
error: remote origin already exists.

Osward@LAPTOP-OSWARD84C MINGW64 ~/Desktop/PLPBasicGitAssignment (master)
$

Osward@LAPTOP-OSWARD84C MINGW64 ~/Desktop/PLPBasicGitAssignment (master)
$ git remote add origin https://github.com/Umuntu11/nothing-int.git
error: remote origin already exists.

Osward@LAPTOP-OSWARD84C MINGW64 ~/Desktop/PLPBasicGitAssignment (master)
$ git push -u origin master
fatal: unable to access 'https://github.com/Umuntu11/PLPBasicGitAssignment/': Op
enSSL SSL_connect: SSL_ERROR_SYSCALL in connection to github.com:443

Osward@LAPTOP-OSWARD84C MINGW64 ~/Desktop/PLPBasicGitAssignment (master)
$ git push -u origin master
info: please complete authentication in your browser...
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (4/4), 313 bytes | 52.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'master' on GitHub by visiting:
remote:      https://github.com/Umuntu11/PLPBasicGitAssignment/pull/new/master
remote:
To https://github.com/Umuntu11/PLPBasicGitAssignment
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.

Osward@LAPTOP-OSWARD84C MINGW64 ~/Desktop/PLPBasicGitAssignment (master)
$ git push -u origin master
branch 'master' set up to track 'origin/master'.
Everything up-to-date

Osward@LAPTOP-OSWARD84C MINGW64 ~/Desktop/PLPBasicGitAssignment (master)
 

