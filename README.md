git init
Initialised empty Git repository in /path-to-folder/wsd-online-deployment-i/.git/
git add .
git commit -m "first commit"
[master (root-commit) 1fa3205] first commit
// some details
3 files changed, 8 insertions(+)
create mode 100644 Dockerfile
create mode 100644 app.js
create mode 100644 deps.js
git branch -M main
git remote add origin git@github.com:wangguoan408/wsd-online-deployment-i.git
git push -u origin main
Counting objects: 5, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 483 bytes | 483.00 KiB/s, done.
Total 5 (delta 0), reused 0 (delta 0)
To github.com:wangguoan408/wsd-online-deployment-i.git

[new branch] main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.
