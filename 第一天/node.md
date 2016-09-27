框架和库

MVC MVVM
MVC:model数据 view视图 controller控制器
MVVM:model view viewModel双向数据绑定
命名空间的缺点：调用过长，不能完全避免名字不冲突
seajs(cmd) requirejs(amd) commonjs

安装angularjs
npm node package manager  我们安装node 就会提供一个包管理器
安装软件时名字不能叫同名的

npm install angularjs

可以通过webstorm自带的命令行进行安装，安装后会产生node_modules文件夹





模块化
声明模块
 var app=angular.module('zfModule',[]);
 app.run('$rootScope',function(){})
 app.controller('ctrl',[function('$scope','$rootScope'){})
在标签上增加ng-controller指定控制器的作用范围













