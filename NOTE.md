echo "# devmedia" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/ElizabeteFabri/devmedia.git
git push -u origin main
$ git push -u origin main
info: please complete authentication in your browser...
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 226 bytes | 226.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/ElizabeteFabri/devmedia.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.