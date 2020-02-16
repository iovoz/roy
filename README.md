# roy
git config --global user.name "symbiane"

git config --global user.email "symbiane@sina.com"

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

//搭建github pages
git checkout -b gh-pages, 
git push origin gh-pages
