# jollychic-iview

[![LICENSE MIT](https://img.shields.io/npm/l/express.svg)](https://www.npmjs.com/package/jollychic-iview)
[![iView](https://img.shields.io/npm/v/jollychic-iview.svg?style=flat-square)](https://www.npmjs.org/package/jollychic-iview)
[![NPM downloads](http://img.shields.io/npm/dm/jollychic-iview.svg?style=flat-square)](https://npmjs.org/package/jollychic-iview)
[![NPM downloads](https://img.shields.io/npm/dt/jollychic-iview.svg?style=flat-square)](https://npmjs.org/package/jollychic-iview)

### 安装
> npm install jollychic-iview@1.0.7

### 简介
jollychic-iview的代码基于iview@2.12.0,在上面修改了部分源码,仅限内部使用.

### 修改内容
- 1.修改menu.vue组件,updateOpenKeys方法,将names赋值变更.

``` javascript
	//let names = [...this.openedNames];
	let names = this.openedNames;
```

- 2.在1.0.7中修改table.vue组件,修复 Table 在 2.12.0 版本，设置 show-header="false" 报错的 bug.

> npm install jollychic-iview@1.1.2   同步iview@2.14.3  
> npm install jollychic-iview@1.2.1   同步iview@2.13.1
### 使用
- 同官方保持一致
- 引入

``` javascript
	import Vue from 'vue';
	import iView from 'jollychic-iview';
	Vue.use(iView);
```

------
### 以下是官方[iview](https://github.com/iview/iview) 的命令
###### 查看API文档请去 [iview](https://github.com/iview/iview) 官网 

###### 查看iview版本
> npm ls iview

###### 安装iview指定版本的命令
> npm install iview@2.12.0

###### iview本身是依赖vue@^2.5.2
