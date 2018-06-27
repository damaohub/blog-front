# 博客[koa2_site](https://github.com/damaohub/koa2-site)的前端项目  
### gulp + sass  
![version](https://img.shields.io/badge/version-%20v1.1.0%20-green.svg)
![npm version](https://img.shields.io/badge/npm-%20v5.6.0%20-blue.svg)

目录结构：

├─assets  --编译前静态资源  
│ &nbsp;├─js  
│ &nbsp;│  &nbsp;└─vendor  
│ &nbsp;└─sass  
│ &nbsp;  &nbsp; &nbsp; &nbsp;└─vendor  
├─pages  --编译前页面  
│ &nbsp;└─partion  
├─public  --编译后静态资源 
└─views  --编译后页面  

## gulp
使用 `gulp` 进行代码编译，如何进行编译请参见下面的gulp章节。

关于如何使用 gulp 请参考 [http://gulpjs.com/](http://gulpjs.com/)

可用的 gulp 命令如下：

- `gulp` 进入开发模式，同时打开 `watch` 和 `server`任务
- `gulp build` 编译压缩代码

# Sass
node-sass安装需要依赖，在国内网络不好安装，必要时需要使用淘宝镜像cnpm，windows上亲测可用。
# Thanks

[gulp](http://gulpjs.com/)
