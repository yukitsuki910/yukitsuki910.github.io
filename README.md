$ git add index.html
$ git add --all
$ git commit -m "add index"
[master (root-commit) 80450b2] add index
 1 file changed, 10 insertions(+)
 create mode 100644 index.html
$ git commit -m "add all"
[master (root-commit) 80450b2] add all
 1 file changed, 10 insertions(+)
 create mode 100644 --all
 $ git remote add origin https://github.com/yukitsuki910/yukitsuki910.github.io.git

$ git push -u origin master
Counting objects: 3, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 327 bytes | 327.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.comyukitsuki91/yukitsuki91.github.io.git
 * [new branch]      master -> master
Branch master set up to track remote branch master from origin.
