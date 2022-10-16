#   基本命令
##  git init <dir> 把目录 dir 变成git可以管理的仓库, dir 缺省则是当前目录
    - 不要乱改动 .git 文件
##  git add <file> 把文件 file 添加到暂存区中 
    - 所有版本控制系统，只能跟踪*文本文件*的改动
##  git commit 将 git add 的内容保存到项目历史中
    - -m + <string> 添加提交注释
##  git diff <file> 查看文件 file 的未提交修改的差异

##  git log 查看修改历史
    - git log -pretty=oneline 简化显示信息
##  git reset
    - --hard HEAD^ 回退到上一版本
    - --hard HEAD^^ 回退到上上一版本
    - --hard 版本号 跳转到某个版本

##  git reflog  显示所有版本

!! 对文件做修改必须add commit

##  git checkout -- <file> 丢弃工作区的修改（未提交到暂存区的）
    - 等同于 git restore <file>

##  删除文件后，记得 commit

##  git clone 将远程的仓库所有文件、历史记录、分支克隆下来

##  git branch 显示本地处理的分支

#   远程仓库
##  本地提交到云端
    - 建立 ssh 秘钥
    - git remote add orgin https://github.com/eator/testgit.git 
    - git push -u orgin master  推送当前分支给远程


#   创建合并分支
##  git checkout -b <devname> 创建并切换分支
    - 相当于    git branch <devname>
                git checkout <devname>

    

