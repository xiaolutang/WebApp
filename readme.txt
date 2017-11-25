python webapp & git学习使用

git命令学习:
	1.git init 初始化版本库
	2.git add 文件名 添加文件
	3.git commit -m"对本次更改的描述"
	4.git status 查看当前有哪些文件被更改了（查看当前仓库的状态）
	5.git diff 对比文件的不同之处
	6.git log 查看提交的历史记录 （可以添加--pretty=oneline参数减少输出: git log --pretty=oneline）
	7.git reset --hard HEAD 版本回退  在Git中，用HEAD表示当前版本，也就是最新的提交3628164...882e1e0（注意我的提交ID和你的肯定不一样），上一个版本就是HEAD^，上上一个版本就是HEAD^^，当然往上100个版本写100个^比较容易数不过来，所以写成HEAD~100
	8.git reflog 记录每一次命令
	9.git checkout -- file 让某个文件回到最近一次git commit 或git add的状态下
	10.git rm file 删除文件
    11.get checkout -b devDemo 创建新的分支devDemo -b表示创建并切换
    12.git branch 查看当前分支
    13.git branch XXX 创建XXX分支
    14.git branch -d devDemo 删除devDemo分支

	git add 将文件添加到暂存区
	git commit 把所有暂存区的文字提交到当前分支

	/******************************************************/
	上次git学习到的位置: 创建与合并分支，该学习的章节分支管理策略
