# **使用说明：**  
## 首先说一下为什么用Golang重写，主要还是考虑后期做公共API，Golang更加稳定，效率也高一些，个人用还是优选PHP，因为现成的东西太多了
## 下载release中对应架构/平台的二进制执行文件，然后解压并赋予权限777，最后直接执行`./xxxxx`，建议搭配进程守护工具进行使用  
## **抖音：**
### 1，抖音手机客户端进入直播间后，点击右下角三个点，点击分享，点击复制链接，然后运行并访问：
```
http://你的IP:35455/douyin?url=https://v.douyin.com/xxxxxx(&quality=xxxx)
```
其中&quality参数默认origin原画，可以省略，也可以手动指定：uhd、origin、hd、sd、ld
### 2，抖音电脑端需要打开抖音网页版复制`(live.douyin.com/)xxxxxx`，只需要复制后面的xxxxx即可
```
http://你的IP:35455/douyin/xxxxx
```
## 更多平台后续会陆续添加
