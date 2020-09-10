### 一，概述

​	ArRtspTool是anyRTC开源的一款将rtsp流转为rtc的工具，这样rtsp的流可以不需要外网服务或IP地址，即可实现网页/H5无插件观看，小程序，APP等各种方式查看视频流。

​	支持常见的Linux、Windows、树莓派、英伟达TX系列等等。

### 二，编译

​		下载代码到本地：Git clone https://github.com/anyRTC-UseCase/ArRtspTool.git

​		以树莓派为例：

```
***# cd ArRtspTool
***# cp Makefile.pi Makefile
***# make && make install
***# chmod +x run.sh
***# ./run.sh start ArRtspTool rtsp.conf 

```

​		停止程序

```
***# ./run.sh stop ArRtspTool
```



### 三，如何配置

```
[rtsp]
url=你的Rtsp流的Url

[rtc]
app_id=rtc的AppId，
chan_id=频道ID,可设置任意值，web或App通过此ID可以观看rtsp的流
```

​	AppId的获取可以登录[anyRTC](https://console.anyrtc.io/signin)官网获取

### 四，常见问题

详见[常见问题](https://docs.anyrtc.io/platforms/docs/platforms/FAQ/faq)。

**anyRTC创业扶持计划**

- 30万免费分钟数，助力初创企业快速发展。

> [anyRTC](https://www.anyrtc.io)初创企业扶持计划，只要通过企业审核，联系客服加入[anyRTC](https://www.anyrtc.io)创业扶持计划，即可享受30万免费分钟数。获得分钟数可降低在实时音视频技术服务所产生的成本费用，零成本快速启动项目。

- 专属技术指导支持

> [anyRTC](https://www.anyrtc.io)为初创企业提供一对一专属客服，为客户提供专业、认真的服务，及时解答您的疑惑。并为客户提供专属技术指导，更快上手，轻松上线！

### 五，联系我们

联系电话：021-65650071

QQ咨询群：580477436

ArCall技术交流群：597181019

咨询邮箱：[hi@dync.cc](mailto:hi@dync.cc)

技术问题：[开发者论坛](https://bbs.anyrtc.io/)

获取更多帮助前往：[www.anyrtc.io](http://www.anyrtc.io/)