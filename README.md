# roy
git config --global user.name "hahaha"

git config --global user.email "ha@haha.com"

git config -l

ls -ltr .ssh

vim .ssh/known_hosts 

ssh-keygen -t rsa -C 'github-roy'

ls .ssh/

more .ssh/id_rsa.pub 

cd development/

git --version

git clone git@github.com:symbiane/roy.git
------------------------------

ls -ltr ~/.ssh/known_hosts
more ~/.ssh/known_hosts

rm -f asset/pii.png //删除文件

rm -rf asset    ///删除目录
------------------------------

git commit -m '不需要了' asset 

git push    ///推送到git仓

git commit -m '修改的描述' README.md     //提交单个文件
------------------------------

<code>
git add --all     ///添加多个
git commit -m 'hhhh'
git push 
</code>

------------------------------

git status, git diff README.md
------------------------------

//搭建github pages: 
package.json:
"name": "gxxxxx",
"homepage": "https://iovoz.github.io/gxxxxx/",
"scripts": 下面加
    "predeploy": "yarn build",
    "deploy": "gh-pages -d build"
//然后: yarn add gh-pages --dev 添加到开发环境
//然后: yarn deploy
//然后: git add package.json , git add yarn.lock , git commit -m 'homepage and deploy', git push

------------------------------
//合并master到aaaaa：
git checkout aaaaa, 
git merge origin master, 
git status, 
git diff, 
git push

------------------------------
//删除分支
git branch -d gh-pages,
git push origin --delete gh-pages

------------------------------



ls -ltr .ssh本地
ls -ltr .ssh
