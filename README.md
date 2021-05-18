# hello-world

vscode git 使用教程

1. 在github上创建远程仓库 
   创建时选择 initialize the repository with a README, 初始化仓库
2. 在vscode上初始化本地仓
   本地电脑上创建空文件夹，初始化本地Git存储库的工作区文件夹
3. 在vscode上绑定远程仓
   按ctrl+shift+P 在弹出框中选择 git:add remote, 远程仓库名称填写origin 远程仓的URL为github创建远程仓的git地址
   相当于在终端输入： git remote add origin git地址
4. 在vscode上拉取远程仓内容  git pull origin main
5. 在vscode上新建文件并提交到本地仓   添加文件、并在源码管理器中选择☑，提交到本地仓
6. 在vscode上将本地仓更改推送到github远程仓
   git push -u origin master
   
.gitignore  不需要上传的文件
复制相对路径放到.gitignore文件下 例如： /main/test/chapter1









