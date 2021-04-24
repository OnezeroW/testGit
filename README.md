# testGit
git config --global user.email "jialin.wan@outlook.com"
git config --global user.name "OnezeroW"

git init
git add *
git commit -m "your own message"

git remote add origin git@github.com:yours/repo-name.git
git push -u origin master
git remote rm origin

git pull origin master
