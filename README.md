# learn_git

win10 git settings:

C:\Users\xxxxxx\.ssh\config  文件设置如下

    Host github.com
    ProxyCommand connect -S 127.0.0.1:1088 %h %p # -S为socks代理 127.0.0.1:1088为你的代理地址和端口
    HostName %h
    Port 22
    User git
    IdentityFile  ~/.ssh/id_rsa
    IdentitiesOnly yes
