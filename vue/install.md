# VUE 安装 *install*  #

<br>

## 直接导入 ##

**下载并使用`<script>`导入, VUE被注册为全局组件**

* 最新版

```html
<script src="https://cdn.jsdelivr.net/npm/vue/dist/vue.js"></script>
```

* 指定版本
  
```html
<script src="https://cdn.jsdelivr.net/npm/vue@2.6.12"></script>
```

> **vue.js和vue.min.js**  
> vue.js: 开发版本, 包含完整的警告和调试模式  
> vue.min.js: 生产版本, 删除了警告，33.30KB min+gzip

<br>

## NPM ##

大型项目推荐使用NPM构建, 以配合[webpack](https://webpack.js.org/)或[Browserify](http://browserify.org/)等打包工具, 以及更好的项目构建管理。

* 最新版

```shell
$ npm install vue
```

<br>

## **命令行工具(CLI)**

*推荐

命令行工具(CLI)是官方提供的项目构建工具，使用该工具可以快速构建工程。  

安装CLI

```shell
$ npm install -g @vue/cli 
```

新建VUE工程

```shell
$ vue create hello-world
```

更多[VUE CLI](https://cli.vuejs.org/)