### test-git
测试git相关操作

##### git创建本地分支并推送到远程仓库
  git checkout -b development
  git branch -a    // 查看本机和远程全部分支列表
  git push origin development:development

##### 例：git将本地development分支合并到远程beta环境【gie merge <branch-name>】
  git checkout beta
  git pull origin beta
  git merge development
  git commit -m ''
  git push origin beta
