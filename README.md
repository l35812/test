echo "# test" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/l35812/test.git
git push -u origin master
dev