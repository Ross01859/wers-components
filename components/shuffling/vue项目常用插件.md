#
vue项目常用plugins

##
1、html - webpack - plugin
插件作用： 生成html文件， 并且引用相关的 assets 文件(如 css, js)
参考地址： 
http: //www.cnblogs.com/wonyun/p/6030090.html
https://segmentfault.com/a/1190000007294861

2、clean-webpack-plugin
插件作用：用于在building之前删除你以前build过的文件
参考地址：
http://www.cnblogs.com/oufeng/p/6819320.html

3、vue-style-loader
插件作用：编译vue的样式部分

4、url-loader
插件作用：将图片文件转换为base64编码并载入浏览器能够减少http请求数，但是增大了js或html文件的体积

5、less-loader
插件作用： less文件加载


6、postcss-loader
插件作用：给不同浏览器的样式加上前缀，如-webkit-
参考地址：
https://segmentfault.com/q/1010000009823010/a-1020000009844532


7、optimize-css-assets-webpack-plugin
插件作用：压缩提取出的css，并解决ExtractTextPlugin分离出的js重复问题(多个文件引入同一css文件)
参考地址：
https://segmentfault.com/a/1190000008779053


8、copy-webpack-plugin
插件作用：拷贝资源
参考地址：
https://blog.csdn.net/wbiokr/article/details/73011288
http://www.cnblogs.com/grimm/p/5772444.html

9、extract-text-webpack-plugin
插件作用：该插件的主要是为了抽离css样式,防止将样式打包在js中引起页面样式加载错乱的现象(提取样式插件)
参考地址：
http://www.cnblogs.com/EnSnail/p/6927211.html
