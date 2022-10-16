## git init <dir> 把目录 dir 变成git可以管理的仓库, dir 缺省则是当前目录
    - 不要乱改动 .git 文件
## git add <file> 把文件 file 添加到暂存区中 
    - 所有版本控制系统，只能跟踪*文本文件*的改动
## git commit 将 git add 的内容保存到项目历史中
    - -m + <string> 添加提交注释
## git diff <file> 查看文件 file 的未提交修改的差异

## git log 查看修改历史
    - git log -pretty=oneline 简化显示信息
## git reset
    - --hard HEAD^ 回退到上一版本
    - --hard HEAD^^ 回退到上上一版本
    - --hard 版本号 跳转到某个版本

## git reflog  显示所有版本

!! 对文件做修改必须add commit

## git checkout -- <file> 丢弃工作区的修改（未提交到暂存区的）
    - 等同于 git restore <file>

