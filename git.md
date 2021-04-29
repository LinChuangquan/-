# git #

## 分布式版本控制系统 ##

### 安装配置 ###

```
brew install git

//创建ssh key、配置git
git config --global user.name "LinChuangquan"
git config --global user.email "602717343@qq.com"
ssh-keygen -t rsa -C "602717343@qq.com"
添加ssh密钥进账号
//链接验证
ssh -T git@github.com

```

![image-20210429203620991](/Users/zhenjiewu/Library/Application Support/typora-user-images/image-20210429203620991.png)



### ![image-20210429221644622](/Users/zhenjiewu/Library/Application Support/typora-user-images/image-20210429221644622.png)新建项目 ###

**简单的案例**

```
git clone https://github.com/LinChuangquan/note.git
cd /Users/jamesruio/Desktop/LearnGit
//文件添加到仓库（.代表提交所有文件）
git add .
//把文件提交到仓库
git commit -m "First Commit"
//上传到github 
git push
```

![image-20210429222739114](/Users/zhenjiewu/Library/Application Support/typora-user-images/image-20210429222739114.png)



## 仓库创建 ##

### 本地仓库创建 ###

``` 
git init
```

### 克隆远程仓库 ###

```
git clone [url]
```







