    # github 在本地仓库上传命令
    echo "# md" >> README.md  创建文件命令
    git init 建立本地仓库
    git add README.md 添加文件，添加所有当前目录 git add . 一个点
    git commit -m "first commit" 添加文件详细描述
    git remote add origin https://github.com/xxx/md.git 添加到远程仓库地址
    git push -u origin master 添加
	
	
	# 安装create-react-app，建议使用cnpm 
    npm install -g create-react-app      

    # 使用命令创建应用，myapp为项目名称
    create-react-app myapp  
                 
    # 进入目录
    cd myapp                                        

    # 生成项目后，隐藏了所有的webpack相关的配置文件，执行以下命令
    npm run eject