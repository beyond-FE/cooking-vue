<<<<<<< HEAD
## 基于cooking生成的Vuejs脚手架

### step 1 安装cooking命令行工具
=======
##基于cooking生成的Vuejs脚手架

###step 1 安装cooking命令行工具
>>>>>>> 354da0bd487aa12c3146f2d575cafb2e0823830a

```
npm install cooking-cli -g
```


<<<<<<< HEAD
### step 2

```
npm install
=======
###step 2

```
npm install 
>>>>>>> 354da0bd487aa12c3146f2d575cafb2e0823830a
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


### 开发目录说明

src --开发目录

​	+components 自定义组件

​	+pages 页面存放，文件夹名对应页面名字

​	+assets 静态资源文件，如公用的样式和字体文件以及图片

<<<<<<< HEAD
=======
举个栗子：
>>>>>>> 354da0bd487aa12c3146f2d575cafb2e0823830a

```
pages
  + index
  	index.js   //页面初始化
  	app.vue    //页面逻辑，包括tempalte,script,style
<<<<<<< HEAD

```

#### 更新说明

1. 弃用vue-resource，改用axios请求接口
2. 增加【pre-commit】，未通过eslint检测不允许提交代码
=======
```
>>>>>>> 354da0bd487aa12c3146f2d575cafb2e0823830a
