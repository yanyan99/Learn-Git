git init

添加文件
 >git add [filename]

 >git commit -m "commit"

 git status //查看状态

 git log //显示版本

 git log --pretty=oneline //只显示修改版本

 git reset --hard HEAD^ // ^表示回退上一个版本，^数目表示回退几次

 git reset --hard [具体版本号]//用于恢复版本

 git reflog //记录指令

 git branch [branch name] //创建新branch
 git switch -c [branch name]//创建并切换
 git checkout [branch name]//切换branch
 git switch [branch name]//切换分支
 git merge [branch name]//和主分支合并
 git branch -d [branch name]//删除分支
 
 create a new line