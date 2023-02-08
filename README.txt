2023-2-8
learn to use git

cd file              #进入项目文件夹
git init             #初始化，在项目文件夹中，空白处右键选择git bash here后，在终端输入
git status           #管理--检测当前文件夹下的文件状态。出现的红色文件（Untracked files）。我们的目的是生成版本，如何生成版本呢
git add test.txt     #git管理test.txt文件
git status           #原本红色文件有3个（README.txt  learn-git.py test.txt），现在test.txt为绿色，剩下2个为红色            
get add .            #让git管理当前文件夹下所有未管理的文件（即git管理当前文件夹下所有文件）
git commit -m 'v1'   #生成版本，单引号内写描述信息
git status           




