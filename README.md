git init
code README.md
    add something to the file and save

git status
git add -A
git status
git commit -m "initial commit"

git checkout -b "index.html_and_index.js"
    ^Creates a new branch
    !Never push to the master

code index.html

git add -A
git commit -m "Created my files"

git checkout master
    ^switch back to master branch

git merge index.html_and_index.js
    ^merge the following branch with our master
