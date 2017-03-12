

### GIT基本使用 
* 初始化一个本地仓库
	+ git init
* 查看本地仓库的状态
	+ git status
* 添加 本地暂存托管(被git记录下来跟踪)
	+ git add 文件名
	+ git add .  添加所有的
* 添加文件忽略清单
	+ 在本地仓库的根目录添加.gitignore文件
* 将本地的变化提交到仓库文件夹(提交到.git目录下)
	+ git commit -m '说明'
* 比较
	+ git diff
* 查看提交日志
	+ git log
* 回复到哪个版本
	+ git reset --hard commit提交记录前六位