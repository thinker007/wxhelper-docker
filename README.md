# wechat-service

## 免责声明
本仓库发布的内容，仅用于学习研究，请勿用于非法用途和商业用途！如因此产生任何法律纠纷，均与作者无关！  
使用此项目可能会造成封号等后果。请自行承担风险。仅用于学习研究，请勿于非法用途。

## 项目介绍
本项目是[wxhelper](https://github.com/ttttupup/wxhelper)的docker一键部署版本，自动完成微信的安装并注入。

关于wxhelper的具体使用方法可以参考[wxhelper](https://github.com/ttttupup/wxhelper)的README或对应分支的文档。


## 项目使用

运行镜像

```
docker run -d --rm -p 8080:8080 -p 19088:19088 --name wxhelper-docker hxrbunny/wxhelper-docker:latest
```
浏览器访问 http://127.0.0.1:8080/vnc.html 扫码登录


## 特别注意
- 只支持AMD64架构，不支持ARM

## 特别感谢
感谢下列项目,记得给大佬们点🌟  
https://github.com/ttttupup/wxhelper  
https://github.com/furacas/DllInjector  
https://github.com/tom-snow/wechat-windows-versions
