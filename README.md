# 格子
格子是提供日常信息的web项目和桌面项目。每种信息都显示在一个格子中。类似igoogle。 
web项目的后端使用nodejs，以及web框架express。当显示的信息需要第三方来提供时，优先使用jsonp接口，否则用node来调用端口。前端使用bootstrap3来控制网站风格以及响应式；使用[seajs](http://seajs.org/docs/)来加载资源；用jquery来进行基本的DOM操作，用[lo-dash](http://lodash.com/)来拓展js的帮助方法；以及其他一些jquery的组件。      
桌面项目准备使用[node-webkit](https://github.com/rogerwang/node-webkit)，用[nodebob](https://github.com/geo8bit/nodebob)来构建。

## 启动web项目
* 安装[nodejs](http://nodejs.org/)
* 下载本项目
* 安装依赖 
 * cd webapp 
 * npm install
* 运行 
 * cd webapp 
 * node app
 * 在浏览器中访问 http://127.0.0.1:8001/

## 已完成的模块
* 天气预报web
功能：显示今天的天气，以及最近六天的天气趋势。
效果图:    
![今天天气](http://img.hb.aicdn.com/480c245ffe6175d0722c3228a7b3ad062f9756119b12-01lm42_fw580)    
![天气趋势](http://img.hb.aicdn.com/d432480f00b19adb062f0186a6d4b80481800e27acd8-8l2AJk_fw580)    
若如上图片不能打开，请点击 [今天天气](http://img.hb.aicdn.com/480c245ffe6175d0722c3228a7b3ad062f9756119b12-01lm42_fw580)和 [天气趋势](http://img.hb.aicdn.com/d432480f00b19adb062f0186a6d4b80481800e27acd8-8l2AJk_fw580)查看







