# 基于webpack+react多页面探索

## 目录结构说明

```

│ web 
        ├─mock<—————测试数据
        ├─dist<—————编译后的文件
        ├─view<—————生成的html文件
        └─src 源文件
           ├─app.js<—————全局样式,全局方法
           ├─template.html<—————html模板文件
           ├─common<—————公共资源
           └─view<—————页面资源，每个页面都有独立的img,css,js
			├─index
			└─about
```

## 开发环境

安装Node和NPM，新版本Node已经继承NPM   
安装Webpack ``npm install webpack -g``  [http://webpack.github.io/](http://webpack.github.io/)  

    以下操作都需要进入web目录

## 安装npm插件

``npm install``

## 相关命令

- ``npm run dev`` 开发模式,访问``127.0.0.1:3000/dist/index``
- ``npm run build`` 将文件编译,压缩,打包
