# git 的使用

+ 使用思想，首先去github 克隆 一个项目到本地 为工作区  

  ```shell
  git clone (url) https://github.com/lqrDream/blog.git
  ```

  

+ 必须为本地库设置一个 用户和邮箱

  ```shell
  git config --global user.name "mvpbang" 
  git config --global user.email "123456789@qq.com"
  ```

  

+ 首先需要在本地完成一次本地库的上传

  ```shell
  git status 查看 文件状态 
  git add 添加上传文件   git add  * 添加所有文件
  git commit -m  "文件描述"  
  ```

  

+ 将本地文件库 上穿到 github 

  ```shell
  git push  
  ```

  

# 将本地项目上传到新的github库

+ 首先初始化文件

  ```shell
  git init	
  ```

  

+ 设置上传的文件 库 

  ```shell
  git remote add origin https://github.com/lqrDream/test.git
  ```

  

+ 提交到库

  ```shell
  git push origin master
  git push --set-upstream origin master 设置使记住相应的别名 和分支,  可以直接 git push 
  ```

  