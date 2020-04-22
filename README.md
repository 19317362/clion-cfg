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



I think the canonical way in Ubuntu is:

    create a new file under /etc/profile.d/

    sudo vi /etc/profile.d/SCRIPT_NAME.sh

    add there:

    export PATH="YOUR_PATH_WITHOUT_TRAILING_SLASH:$PATH"

    and give it execute permission

    sudo chmod a+x /etc/profile.d/SCRIPT_NAME.sh

