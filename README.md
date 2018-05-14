# roy
  161  git config --global user.name "symbiane"
  162  git config --global user.email "symbiane@sina.com"
  163  git config -l
  165  ls -ltr .ssh
  166  vim .ssh/known_hosts 
  167  ssh-keygen -t rsa -C 'github-roy'
  169  ls .ssh/
  170  more .ssh/id_rsa.pub 
  171  cd development/
  173  git --version
  175  git clone git@github.com:symbiane/roy.git
  176  ls -ltr ~/.ssh/known_hosts 
  177  more ~/.ssh/known_hosts


rm -f asset/pii.png //删除文件
rm -rf asset    ///删除目录
git commit -m '不需要了' asset 

git push    ///推送到git仓


git commit -m '修改的描述' README.md     //提交单个文件
git add --all     ///添加多个
git status
git diff README.md