## Github  Coding 同步测试


```

# 初始化仓库
git init
# 更新README文件
git add -A

# 提交更新，并注释信息
git commit -m 'Github  Coding同步测试'

# 查看当前远端仓库
git remote -v

# 添加一个名为 origin 的远端

git remote add origin git@github.com:ProZoom/Test.git

# 连接远程github项目
git remote set-url --add --push origin git@github.com:ProZoom/Test.git

# 连接远程coding项目
git remote set-url --add --push origin git@git.coding.net:ProZoom/Test.git

# 将本地项目更新到github项目上去
git push -u origin master

```
