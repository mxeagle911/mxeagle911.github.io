# VUE 安装 #

## 直接导入 ##

**下载并使用`<script>`导入, VUE被注册为全局组件**

* 最新版

```
<script src="https://cdn.jsdelivr.net/npm/vue/dist/vue.js"></script>
```

* 指定版本
  
```
<script src="https://cdn.jsdelivr.net/npm/vue@2.6.12"></script>
```

> **vue.js和vue.min.js**  
> vue.js: 开发版本, 包含完整的警告和调试模式  
> vue.min.js: 生产版本, 删除了警告，33.30KB min+gzip

## **NPM** ##

大型项目推荐使用NPM构建, 以配合[webpack](https://webpack.js.org/)或[Browserify](http://browserify.org/)等打包工具, 以及更好的项目构建管理。

* 最新版

```
$ npm install vue
```

## **命令行工具(CLI)**

命令行工具(CLI)是官方提供的项目构建工具，使用该工具可以快速构建工程。  
更多[VUE CLI](https://cli.vuejs.org/)

Warning: 使用CLI需要对node.js有一定了解