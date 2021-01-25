5、绑定本地仓库到Github
（1）在Github上创建一个同名仓库
（2）绑定远程仓库


//1.进入正确的文件夹路径
//2.将该文件夹初始化为git仓库
git init 
//注意：如果错误将另外一个文件夹初始化，则需要删除该文件夹下的隐藏文件 .git，然后再进行初始化
//3.使用 git remote -v 查看当前git仓库绑定远程仓库，如果显示空白则无绑定    
//4.绑定远程仓库
git remote add origin 仓库地址
//5.如果绑定错误，使用 git remote remove origin 移除绑定 