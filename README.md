## About this repo(max_resume)

`max_resume` 是一个简历生成器，从json中读取数据，可部署到`github pages` 在线浏览，右侧边栏下载。https://maxlzz.github.io/max_resume/



## 环境安装

首先确保你的电脑已经安装了
Node.js：https://nodejs.org/en/，

然后在终端输入如下命令安装gulp和bower：

```js
$ npm install --global gulp
$ npm install -g bower
```

## 开发

 1.执行 `npm install` 安装依赖

 2.执行 `bower install`安装所需库

 3.填写你的个人信息于`resume.json`文件

 4.执行 `gulp server`来构建项目


##部署到github

1.clone this repo

2.修改`package.json`文件的SSH git remote orgin为你的SSH 地址（你需要创建一个新的仓库）

3.创建`gh-pages`分支

4.终端执行`gulp deploy` 稍等片刻即可部署完毕

5.到你的`github pages`站点访问（url后面加上`/max_resume/`即可访问）

## LICENSE

 (MIT License)

 Copyright (c) 2016  maxlzz
