
git init
vim FILE.md
git add FILE.md
git commit -m "0. commit"

git add FILE.md
git commit -m "1. commit"

git add FILE.md
git commit -m "2. commit"

git branch bug-fix 579e70e42b850a231a5818e4442b86362fad8e52
git checkout bug-fix
git add FILE.md
git commit -m "3. commit"

git add FILE.md
git commit -m "4. commit"
