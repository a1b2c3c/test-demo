# Git使用步骤
## 1 安装git
## 2 注册gitHub账号
## 3 在代码中新增一个.gitignore文件,这个文件里面可以写不需要上传的文件列表
## 4 上传步骤
### 1 git init--初始化git
### 2 git add .--上传所有文件加.
### 3 如果第一次上传git,要输入你的git账号和名称
#### 1 git config --global user.email "264414848@qq.com"
#### 2 git config --global user.name "chen"
### 4 git commit -m 第一次上传文件  --这个时候会弹出登录窗口，输入用户名和密码(如果第一次上传的话)
### 5 git branch -M main
### 6 git remote add origin https://github.com/a1b2c3c/test-demo.git
### 7 git push -u origin main --推送到主线上
### 8 删除一个文件用git rm 文件名,然后用git add .
### 9 查看git的状态 git status
### 10 git log是查看git操作的日志，退出按Q键
