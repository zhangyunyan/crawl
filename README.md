## 连接服务器
xshell
terminal(mac)
git-bash(win)

```
ssh root@120.26.201.153
y
201613Node
```

## ftp
ftp://172.18.1.139/software/
xshell
xftp


## 1.升级操作系统 
```
apt-get update
```

## 2.安装npm
```
apt-get install npm
y
```

## 3. 安装 n
```
npm install n -g   
n stable    安装稳定版本
n 7.5.0
```

## 4.安装 git
```
apt-get install git
```

## 5.把当前项目变成一个git仓库
```
git init
git add -A
git commit -m"初始化提交"
git remote add origin https://github.com/zhufengnodejs/201613crawl.git
git push -u origin master
```
## 6.到服务器上克隆项目并安装依赖
```
git clone https://github.com/zhufengnodejs/201613crawl.git
npm install 
```

## 7. 安装 mongodb
```
apt-get install mongodb
```
## 8.设置环境变量
```
 export DEBUG=crawl:*
```

## 9.启动服务
```
cd tasks
node main.js
cd ..
node sever.js
```