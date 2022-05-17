# webpack笔记

安装: npm install webpack webpack-cli -D 安装开发依赖

卸载安装: npm uninstall webpack webpack-cli

在终端输入webpack打包的时候 , 会在当前目录的src文件下找到index.js这个文件 , 看看里面引用了什么文件

终端直接输入webpack 执行的是全局的webpack命令 , npx webpack 使用的是局部的

打包的方式: 

	1. webpack :  执行的是全局的webpack命令
	1. npx webpack : 执行的是局部的webpack命令(与1 版本可能不一样)
	1. npm run bulid : 在package.json 文件中的scripts中添加 "bulid":"webpack"  ,这里的webpack优先找到的是这个项目中的webpack 也就是局部的webpack