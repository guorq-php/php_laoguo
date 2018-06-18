# php_laoguo

## git 学习
  ## 一般情况下,使用一台新电脑需要配置基本信息,用于查看是谁提交的
  	 git config --global user.email '邮箱'
  	 git config --global user.name '名字'

  ## github 需要配置 sshkey 公私钥 , 用于授权,不是谁都能提交的
     用于对暗号,公钥配置到github账号上

     ssh-keygen -t rsa -C '邮箱地址' 生成公私钥  后面的提示直接敲回车就行
     cat ~/.ssh/id_rsa.pub 查看公钥

  ## git clone 远程仓库
  ## git add . 添加当前文件夹下的所有文件到暂存区
  ## git commit -m '提交当前暂存区里的文件到本地仓库'

  ## git push [origin master] 如果当前分支与远程的分支有关联,后面可以省略
  ## git pull [origin master] 有关联也可以省略

  ## git branch 查看本地仓库的所有分支
  ## git branch -c 分支名 从当前分支拷贝一份新的分支
  ## git checkout 分支名 切换到指定分支
