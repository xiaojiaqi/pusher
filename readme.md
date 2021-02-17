# 个人微信推送服务器的使用说明

​    微信是一款使用非常广泛的软件，但是微信是个封闭软件，所以想向自己的微信发消息是一个比较困难的事情，还好微信有自己的开发平台。所以利用开发平台，我开发了一个小软件，利用这个软件，你可以向自己的微信发送消息。 比如 你不想把自己的微信交给对方，但是又希望能收到他的消息，那么就可以利用它。再比如你想利用网站收集意见，然后将意见直接发到手机上 也可以使用它。好了，现在看看 该如何使用这个软件吧。



### 1. 软件准备

首先下载软件：

你可以从2个地方找到下载：

1. https://github.com/xiaojiaqi/pusher

2. http://pusher.k8seasy.com/pusher/last/

   软件目前有 windows 和linux 2个版本

   ​

### 2. 软件启动 

以linux 为例

![x01_13](https://raw.githubusercontent.com/xiaojiaqi/pusher/master/img/x01_13.png)

软件的启动非常简单，软件有2个参数

第一个是 -s  使用这个参数，那么你就不能从网页上对服务器进行管理，这种模式比较适合 你对外公开服务，让别人向你的微信发消息。这样别人不能随便改你的服务器。默认 这个功能是关闭的，你可以直接修改服务器的配置

第二个是 -p  使用这个参数。你可以随意改变服务器的端口，这样可以避免端口冲突。



运行服务器以后，用浏览器打开 你的服务器 你就可以看到服务了。

![x01_15](https://raw.githubusercontent.com/xiaojiaqi/pusher/master/img/x01_15.jpg)



### 3.服务器设定

服务器设定相对会比较复杂一些，但是只需要你有一个微信账号就可以完成了。

所谓一图胜千言， 你只要按照下面的图例去做就可以了。非常简单



注册地址：  https://mp.weixin.qq.com/debug/cgi-bin/sandbox?t=sandbox/login

这是腾讯的官方注册地址

![x1_01](https://raw.githubusercontent.com/xiaojiaqi/pusher/master/img/x1_01.png)
![x1_01](https://raw.githubusercontent.com/xiaojiaqi/pusher/master/img/x1_02.png)
![x1_01](https://raw.githubusercontent.com/xiaojiaqi/pusher/master/img/x1_04.png)
![x1_01](https://raw.githubusercontent.com/xiaojiaqi/pusher/master/img/x1_05.png)
![x1_01](https://raw.githubusercontent.com/xiaojiaqi/pusher/master/img/x1_06.png)
![x1_01](https://raw.githubusercontent.com/xiaojiaqi/pusher/master/img/x1_07.png)
![x1_01](https://raw.githubusercontent.com/xiaojiaqi/pusher/master/img/x1_08.png)
![x1_01](https://raw.githubusercontent.com/xiaojiaqi/pusher/master/img/x1_09.png)
![x1_01](https://raw.githubusercontent.com/xiaojiaqi/pusher/master/img/x1_10.png)

### 4. 测试

此时你打开网站，可以轻松给自己的微信发消息拉。速度很快的哦！

![x01_15](https://raw.githubusercontent.com/xiaojiaqi/pusher/master/img//x01_15.jpg)

微信上会得到通知

![x01_14](https://raw.githubusercontent.com/xiaojiaqi/pusher/master/img//x01_14.png)

### 5. 捐赠

  欢迎捐赠，让我们一起把它做得更好

![wechat](https://raw.githubusercontent.com/xiaojiaqi/pusher/master/img//wechat.jpg)

![alipay](https://raw.githubusercontent.com/xiaojiaqi/pusher/master/img//alipay.jpg)