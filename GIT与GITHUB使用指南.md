###  GITHUB使用指南

#### 准备工作：
1. 下载并安装git
2.  注册github账号
3. 将git 与 github 连接起来：
+ 在git中执行 如下语句获取 id_rsa.pub：
  ```ssh-keygen -t rsa -C "youremail@example.com"``` 
+ 找到密钥文件 id_rsa.pub ,复制文件内容，在github的setting里SSH keys菜单增加该密钥

#### 开始连接并工作：
1. 确定git与github已经连接：
   ```git init```
   ```git remote add origin https://github.com/dorsonzhang/python_study_note```
   ```git pull origin master```
2. 本地文件推送到github上面：
   文件夹内增加一个文件 index.html
   ```git add index.html```
   ```git commit -m '增加索引文件index.html'```
   ```git push origin master```
