# Git基础命令指南

| 命令                                | 说明                         |
| --------------------------------- | -------------------------- |
| `git init`                        | 初始化仓库目录                    |
| `git add README.md`               | 添加文件或文件夹到仓库                |
| `git commit -m "添加自描述文件"`         | 提交修改到仓库，-m后面的参数是日志信息       |
| `git commit --amend`              | 修改已经提交的注释或日志               |
| `git status`                      | 查看仓库状态                     |
| `git diff`                        | 显示暂存区和工作区的差异               |
| `git diff --cached <文件名>`         | 显示暂存区和上一个commit的差异         |
| `git diff HEAD`                   | 显示工作区与当前分支最新commit之间的差异    |
| `git diff HEAD -- <文件名>`          | 显示当前文件与主干文件的修改             |
| `git log`                         | 显示提交日志                     |
| `git log --pretty=oneline`        | 日志使用一行显示                   |
| `git log --graph`                 | 查看分支合并图                    |
| `git reset --hard HEAD^`          | 回退到上一个版本                   |
| `git reset --hard HEAD^`          | 回退到上上一个版本                  |
| `git reset --hard HEAD~100`       | 回退到上100个版本                 |
| `git reset --hard 96d0067`        | 回退到96d0067（commit_id）开头的版本 |
| `git reflog`                      | 查看历史操作命令                   |
| `git checkout -- README.md`       | 回滚文件到最后一次add或commit的版本     |
| `git branch`                      | 查看分支                       |
| `git branch <name>`               | 创建分支                       |
| `git branch -d <name>`            | 删除分支                       |
| `git checkout <name>`             | 切换分支                       |
| `git checkout -b <name>`          | 创建+切换分支                    |
| `git merge <name>`                | 合并某分支到当前分支                 |
| `git rm`                          | 从版本库中删除文件，删除后需要commit      |
| `git push`                        | 从本地仓库推送代码到远程仓库             |
| `git remot`                       | 列出所有远程主机                   |
| `git remote -v`                   | 列出所有远程主机，同时查看主机地址          |
| `git remote show <主机名>`           | 查看指定远程主机主机的详细信息            |
| `git remote add <主机名> <网址>`       | 添加远程主机                     |
| `git remote rm <主机名>`             | 删除远程主机                     |
| `git remote rename <原主机名> <新主机名>` | 远程主机重命名                    |
|                                   |                            |
|                                   |                            |
|                                   |                            |
|                                   |                            |
|                                   |                            |
|                                   |                            |
|                                   |                            |
|                                   |                            |
|                                   |                            |

