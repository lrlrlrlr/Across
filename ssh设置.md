买了一个raspberrypi, 放在家里用来控制modempool，。。。。（TODO）

想把他放在公网上， 但是出现了ping得通但是无法ssh的情况。 原来是port forawding有点问题， 于是直接使用dmz把它暴露在公网上。 
但是我的密码很短， 也不想改， 远程ssh的密码非常容易被暴力破解出来，于是我就需要ban了服务器的ssh密码登录，并且开启rsa密钥登录。


教程 ssh修改登录端口禁止密码登录并免密登录
https://www.jianshu.com/p/b294e9da09ad

本地生成rsakey后， 要把public key放在服务器的authorized_keys里面，先上传到服务器
$ cat id_rsa.pub >> ~/.ssh/authorized_keys

遇到问题： bash: /home/user/.ssh/authorized_keys: No such file or directory
https://askubuntu.com/questions/466549/bash-home-user-ssh-authorized-keys-no-such-file-or-directory

再修改好ssh设置
$vi /etc/ssh/sshd_config
