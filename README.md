hello world
echo "hello world" >> README.md
git config --global user.name dilaksh06
git config --global user.email kamalathasandilakshan@gmail.com
git config --global -l
git init
git status
git add README.md
git log
git commit -m "first commit"
git remote add test https://github.com/dilaksh06/test
git remote

git branch -m master
git branch -M main
git push -u test main
git status
git pull test