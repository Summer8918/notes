git 保存用户名和密码，避免每次push时都输入密码：
git config credential.helper store
之后当git push输入依次用户名和密码就会被记录，对于之后的新git文件都执行上述命令之后，不用输入用户名和密码就能push。


## online Markdown Editor
https://dillinger.io/

调试core dump
使core文件生成在当前文件夹：
sudo bash -c 'echo core.%e.%p > /proc/sys/kernel/core_pattern'
