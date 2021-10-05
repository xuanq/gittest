this is first line
初始化一个目录
git init
创建一个版本
git add code.txt
git commit -m '版本1'
查看已有版本
git log
回退到某个版本
git reset --hard HAED~1 / 版本号 前几位就可以
查看操作记录
git reflog 
从下往上是从老往新，前面是版本号前几位
git status
查看状态
git checkout -- code.txt 回退工作区的改动

git diff HEAD^ HEAD -- code.txt
对比文件的不同

git chechout -b dev
