# roy


Git error: RPC failed; curl 56 LibreSSL SSL_read: SSL_ERROR_SYSCALL, errno 54
//git config --global user.name 'YOUR_GITHUB_LOGIN_USERNAME'
//git config --global user.password 'YOUR_GITHUB__TOKEN'

error: RPC failed; curl 56 LibreSSL SSL_read: SSL_ERROR_SYSCALL, errno 60
https 和 http 的缓存
//git config --global http.postBuffer 1048576000
//git config --global https.postBuffer 1048576000

LibreSSL SSL_read: SSL_ERROR_SYSCALL, errno 60
//git config --global --add remote.origin.proxy ""

LibreSSL SSL_connect: SSL_ERROR_SYSCALL in connection to github.com:443 
//git config --global http.sslBackend "openssl"
----------------
//git config --global --add remote.origin.proxy ""
//git config --global --unset http.proxy
//git config --global --unset https.proxy



//git config --global --list    

//run-app -Dgrails.server.port.http=9090

//-Djava.net.preferIPv4Stack=true



cd ~/ 
git clone https://github.com/nvm-sh/nvm.git .nvm
cd ~/.nvm
git checkout v0.38.0
. ./nvm.sh


Now add these lines to your ~/.bashrc, ~/.profile, or ~/.zshrc 

export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"  # This loads nvm
[ -s "$NVM_DIR/bash_completion" ] && \. "$NVM_DIR/bash_completion"  # This loads nvm bash_completion


nvm ls-remote
nvm install 14.16.1
nvm run node 14.16.1


## command not found: compdef
inside .zshrc, commented out this line: 
#[ -s "$NVM_DIR/bash_completion" ] && \. "$NVM_DIR/bash_completion"  # This loads nvm bash_completion


‘
“
//git config --global user.name "hahaha"

//git config --global user.email "ha@haha.com"

//git config -l

//ls -ltr .ssh

//vim .ssh/known_hosts 

//ssh-keygen -t rsa -C 'github-roy'

//ls .ssh/

//more .ssh/id_rsa.pub 

//cd development/

//git --version

------------------------------

//ls -ltr ~/.ssh/known_hosts

//more ~/.ssh/known_hosts

//rm -f asset/pii.png //删除文件

//rm -rf asset    ///删除目录

------------------------------

//git commit -m '不需要了' asset 

//git push    ///推送到git仓

//git commit -m '修改的描述' README.md     //提交单个文件

------------------------------

//git add --all     ///添加多个

//git commit -m 'hhhh'

//git push 

------------------------------

//git status, 

//git diff README.md

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

//git checkout aaaaa, 

//git merge origin master, 

//git status, 

//git diff, 

//git push

------------------------------
//删除分支

//git branch -d gh-pages,

//git push origin --delete gh-pages

------------------------------

https://1cm.hk.chinamobile.com/user/addresslookup.html?term=le+pre

//ls -ltr .ssh本地

//ls -ltr .ssh
