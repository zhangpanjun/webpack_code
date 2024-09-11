# webpack_code
基于webpack5，一些最基础的配置，在不使用webpack_devServer，直接使用npx webpack进行项目打包后查看更改效果demo;对比webpack_code_devserver项目，感受devserver的魅力
# node版本
当前使用版本是 18.15.0
# 命令
安装依赖 yarn
打包 npx webpack
# 注意！！
index.html中有main.js的资源引入，开启配置htmlplugin后这一行将无用，webpack会自动将打包后的js文件引入。不开启则先打包后手动引入后才可看到效果哟！
# 关于devserver的配置项及原理文档描述，请参考自己的博客 (觉得有所帮助记得点赞收藏哟~)
地址：https://blog.csdn.net/zhangpanjun/article/details/141196083
