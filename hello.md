## 绑定本地仓库到Github
首先在github创建一个和本地项目同名称的空仓库,最好不用生成初始化的md文件

然后在本地终端进入该仓库,并使用`git init`命令初始化为git仓库

`git remote add origin 仓库地址`
绑定远程仓库

`git remote -v`
查看当前git仓库绑定的远程仓库

`git remote remove origin`
如果绑定错误,可以用该命令移除绑定

==此时绑定完成,可以提交本地仓库到GitHub==