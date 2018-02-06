# Git基础命令指南

| 命令                         | 说明                         |
| -------------------------- | -------------------------- |
| git init                   | 初始化仓库目录                    |
| git add README.md          | 添加文件或文件夹到仓库                |
| git commit -m "添加自描述文件"    | 提交修改到仓库，-m后面的参数是日志信息       |
| git status                 | 查看仓库状态                     |
| git diff                   | 查看文件修改                     |
| git diff HEAD -- README.md | 对比当前文件与主干文件的修改             |
| git log                    | 显示提交日志                     |
| git log --pretty=oneline   | 日志使用一行显示                   |
| git reset --hard HEAD^     | 回退到上一个版本                   |
| git reset --hard HEAD^     | 回退到上上一个版本                  |
| git reset --hard HEAD~100  | 回退到上100个版本                 |
| git reset --hard 96d0067   | 回退到96d0067（commit_id）开头的版本 |
| git reflog                 | 查看历史操作命令                   |
| git checkout -- README.md  | 回滚文件到最后一次add或commit的版本     |
| git rm                     | 从版本库中删除文件，删除后需要commit      |
|                            |                            |
|                            |                            |

