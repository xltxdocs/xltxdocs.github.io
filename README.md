# ○小李同学的附件表

> XLTX的附件表（请按快捷键 Ctrl+F 输入视频标题来搜索内容）

✓ **和每期视频保持同步更新**

✓ **你可以在这里找到一些因各种原因被视频网站下架的视频备份**

✓ **XLTX的主页：**

[B站（首发）](https://space.bilibili.com/3546668544821656) [抖音](https://www.douyin.com/user/MS4wLjABAAAASiyfbXSxfh4IoLCa53aomaojUJnagMMb9ROvzRdAxtzr6U4HD-2kweNO8IB3L7rF?from_tab_name=main) [YouTube](https://www.youtube.com/@玩电脑的小李同学)

**扫描二维码加入QQ群（群号：1028096082）**

<img src="https://picx.zhimg.com/80/v2-8d51c63a5c9e9629f5534e7561c4924a_1440w.jpeg" style="zoom:25%;" />



<font color='RedOrange'>**● 提示：如有失效链接，请务必通过私信反馈给我！！！**</font>

<font color='RedOrange'>**● 注意！请将附件先转存到自己网盘再下载！！！避免文件被和谐！！！**</font>

##### EP1-如何搭建网站？个人网站搭建指南

**Docsify**

● Docsify（官网）：https://docsify.js.org/#/

● Node.js（官网）：https://nodejs.org/zh-cn

● Node.js（提取码：xltx）：https://www.123684.com/s/vNJLjv-m3bDH

● Typora（官网）：https://typoraio.cn

● Typora（提取码：xltx）：https://www.123684.com/s/vNJLjv-13bDH

● 编辑好的README.md文件（提取码：xltx）：https://www.123684.com/s/vNJLjv-SAbDH

● Github：https://github.com/

○ 以下代码需要在命令提示符中输入，每输入一行按一次回车

\#查看node.js有没有正确安装

```
node -v
```

\#查看npm有没有正确安装

```
npm -v
```

\#本地部署Docsify

```
npm i docsify-cli -g
```

\#初始化Docsfy本地项目

```
docsify init ./docs
```

\#启用本地网页预览

```
docsify serve docs
```

\#README.md文件是Markdown文件，推荐使用Typora编辑

\#用记事本打开博客文件夹的index.html文件，按自己的需求填上，填完后保存

```
<!DOCTYPE html>
<html lang="语言（可以填写zh-CN）">
<head>
  <meta charset="UTF-8">
  <title>网站标题</title>
  <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1" />
  <meta name="description" content="Description">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, minimum-scale=1.0">
  <link rel="stylesheet" href="//cdn.jsdelivr.net/npm/docsify@4/lib/themes/vue.css">
</head>
<body>
  <div id="app"></div>
  <script>
    window.$docsify = {
      name: '',
      repo: ''
    }
  </script>
  <!-- Docsify v4 -->
  <script src="//cdn.jsdelivr.net/npm/docsify@4"></script>
</body>
</html>

```

\#注册/登入[GitHub](https://github.com/)

\#点击Create a new repository

\#仓库名输入：你的GitHub用户名.github.io

\#勾选 Add a README file

\#勾选 Public

\#点击 Create

\#点击 Add file

#点击 Upload files

\#点击 choose your files，上传 docs文件夹中的文件

\#点击 Commit changes

**Hexo**

● Hexo（官网）：https://hexo.io/zh-cn/

● Node.js（官网）：https://nodejs.org/zh-cn

● Node.js（提取码：xltx）：https://www.123684.com/s/vNJLjv-m3bDH

● Git（官网）：https://git-scm.com/?hl=zh-cn

● Git（提取码：xltx）：https://www.123912.com/s/vNJLjv-YHZDH

● Typora（官网）：https://typoraio.cn

● Typora（提取码：xltx）：https://www.123684.com/s/vNJLjv-13bDH

● Github：https://github.com/

○ 以下代码需要在命令提示符中输入，每输入一行按一次回车

\#查看node.js有没有正确安装

```
node -v
```

\#查看npm有没有正确安装

```
npm -v
```

\#查看git有没有正确安装

```
git -v
```

\#下载Hexo

```
install hexo-cli -g
```

\#注册/登入[GitHub](https://github.com/)

\#点击Create a new repository

\#仓库名输入：你的GitHub用户名.github.io

\#勾选 Add a README file

\#勾选 Public

\#点击 Create

○ 以下代码需要在Git Bash中输入，每输入一行按一次回车

\#生成SSH Keys

```
ssh-keygen -t rsa -C "你的邮箱地址"
```

\#敲4次Enter

\#进入C:\Users\你的用户名，在里面进入.ssh文件夹

\#用记事本打开里面的id_rsa.pub,全选复制里面的代码

\#注册/登入[GitHub](https://github.com/)

\#进入用户设置，找到SSH keys

\#新建SSH keys，名称随意，在下面粘贴代码，然后创建

\#查看是否成功添加

```
ssh -T git@github.com
```

\#敲1次Enter

\#输入yes

```
yes
```

\#本地生成博客内容

```
hexo init
```

\#安装

```
hexo install
```

\#生成博客内容

```
hexo g
```

\#本地部署博客

```
hexo s
```

\#Ctrl+C关闭

\#记事本打开_config.yml

\#拉到最下面将deploy后面的全删掉，粘贴这段：

```
  type: git
  repository: 
  branch: main
```

\#点击 Code，复制SSH链接，粘贴到 repository后面，保存退出

\#回到博客文件夹，打开Git Bash

\#安装自动部署发布工具

```
npm install hexo-deployer-git --save
```

\#生成博客内容

```
hexo g
```

\#配置邮箱和GitHub账号

```
git config --global user.email "你的邮箱"
git config --global user.name "你的GitHub账号"
```

\#上传博客内容

```
hexo d
```

\#用记事本打开博客文件夹的_config.yml文件，将#Site下面按自己的需求填上，填完后保存

```
## Site
title: 标题
subtitle: 副标题
description: 描述
keywords: 关键词
author: 站主
language: 语言（可以填写zh-CN）
timezone: 时区（可以填写Asia/Shanghai）
```

\#生成新的文章

```
hexo new 文章标题
```

\#文章是Markdown文件，在博客文件夹中的source/_posts中，推荐使用Typora编辑
