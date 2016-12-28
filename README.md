##基于cooking生成的Vuejs脚手架

###step 1 安装cooking命令行工具

```
npm install cooking-cli -g
```


###step 2

```
npm install 
```

ps:推荐用cnpm

具体配置可参照cooking官方文档进行修改，文档地址：

http://cookingjs.github.io/zh-cn/index.html

基础配置是生成多页面，入口文件在app.json里面配置，build.js里面配置生成html，如无具体需求可以不用改动，参考地址：

[用 cooking 搭建一个多页面易配置的 Vue 2 项目（进阶篇）](https://zhuanlan.zhihu.com/p/22610408)

如果要生成单页的应用，可参考官方文档修改。

基本的两个命令：

开发运行：

```
cooking watch -p
```

打包：

```
cooking build -p
```