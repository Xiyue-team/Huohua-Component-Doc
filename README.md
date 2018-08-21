# HuohuaComponentDoc

火花素材框架文档使用说明

## Contents

- [HuohuComponentDoc](#huohucomponentdoc)
	- [Contents](#contents)
	- [Features](#features)
	- [dependents](#dependents)
	- [install](#install)
	- [How to use](#how-to-use)
		- [developer](#developer)
		- [Compile](#compile)

## Features

- 文档项目基于 [Rosid](https://github.com/electerious/Rosid), a web server with just-in-time pre-processing. JS (with Babel, UglifyJS), SASS (with cssnano, Autoprefixer) and Nunjucks can be used right out of the box.

## dependents

doc dependents on …

- [Node.js](https://nodejs.org/en/) (v8.5.0 or newer)
- [yarn](https://yarnpkg.com/en/)



## install

使用 [yarn](https://yarnpkg.com/en/) 安装所有依赖.

```sh
yarn install
```

## How to use

### developer

使用以下命令启动. 使用浏览器访问, 代码改变可实时刷新保存刷新.

```sh
yarn start
```

### Compile

执行以下命令，编译生成打包文件目录 `dist` , 上传到服务器目录即可访问.

```sh
yarn run compile
```
