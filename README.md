# clion-cfg
my clion config for sync

1、安装bash-completion

apt-get install bash-completion

2、编辑~/.bashrc 文件

添加如下内容：

if [ -f /etc/bash_completion ]; then
. /etc/bash_completion
fi

3、使其生效

退出SSH，重新登录。

apt-get install build-e 然后TAB一下，自动补齐了吧。
