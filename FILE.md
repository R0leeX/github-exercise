
git init
vim FILE.md
git add FILE.md
git commit -m "0. commit"

git add FILE.md
git commit -m "1. commit"

git add FILE.md
git commit -m "2. commit"

git log -3
git branch bug-fix 579e70e42b850a231a5818e4442b86362fad8e52
git checkout bug-fix
git add FILE.md
git commit -m "3. commit"

git add FILE.md
git commit -m "4. commit"

git add FILE.md
git commit -m "5. commit"

git add FILE.md
git commit -m "6. commit"

git log -3
git branch bug-fix-experimental 5ffe9633d01e397ca73f6c86991553334fd459a7
git checkout bug-fix-experimental
git add FILE.md
git commit -m "7. commit"

git add FILE.md
git commit -m "8. commit"

git add FILE.md
git commit -m "9. commit"

git checkout master
git add FILE.md
git commit -m "10. commit"

git checkout bug-fix
git add FILE.md
git commit -m "11. commit"
git merge bug-fix-experimental         // CONFLICT
git status
vim FILE.md
git add FILE.md
git commit

git add FILE.md
git commit -m "12. commit"

git checkout master
git merge bug-fix       //CONFLICT
git status
vim FILE.md
git add FILE.md
git commit