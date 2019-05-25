git --version

git config --global user.name "Fangqi Zhu"
git config --global user.email "fangqi.zhu@mavs.uta.edu"
git config --list     (Then press q to quit)
git help config       (Then press q to quit)
git config --help     (Then press q to quit)

start to track
git init
git add <file>
git add *.html

git rm --cached <file>
git status
git commit      press "i" (insert mode) ---> escape :wq
git push
git pull
git clone

git commit -m 'xxxxx'  (commit with a message)

touch .gitignore (build a git ignore folder so that if you don't want something be handled by git, just get them ignored)

Cmd + Shift + . (dot) (use to see the hidden files in mac os)

* branchs
git branch
git checkout <branch>
git checkout master
=======
Cmd + Shift + . (dot) (use to see the hidden files in mac os)

git remote

echo "# myappSample" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/FangqiZhu/myappSample.git
git push -u origin master


git remote add origin https://github.com/FangqiZhu/myappSample.git
git push -u origin master

generate token: 3f30e0a9e956f0480f33b9c0e4577d22e426ce6d

Link: https://help.github.com/en/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent#adding-your-ssh-key-to-the-ssh-agent

SHA256:SMNXdrbLi0M8zNY6If2R/jwTgXpdYRPfX5lCjbgk7xg fangqi.zhu@mavs.uta.edu
