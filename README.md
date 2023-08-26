# dlink
[本项目](https://dlink.pp.ua)来源[原项目](https://github.com/youshandefeiyang/sub-web-modify)CSS样式。
## 效果预览：
![avatar](https://raw.githubusercontent.com/youshandefeiyang/webcdn/main/sub-web-modify.GIF)
### 使用方法：
建议使用Docker一键部署:
```
docker run -d --restart unless-stopped --privileged=true -p 8090:80 --name dlink hch813813/dlink
```
访问地址举例:
```
http://192.168.10.1:8090/?backend=https://api.v1.mk
```
