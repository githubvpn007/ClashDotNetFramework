# ClashDotNetFramework
ClashDotNetFramework，ClashDotNetFramework教程，ClashDotNetFramework配置，ClashDotNetFramework配置说明、vpn代理



简介
----


Clash 是一个使用 Go 语言编写，基于规则的跨平台代理软件核心程序。  
ClashDotNetFramework 是基于.NET5的图形化 Clash 分支。  
支持的协议： Vmess, Shadowsocks, Snell , SOCKS5 , ShadowsocksR  
**特性**： 比Clash for Windows更为轻量，占用内存少。图形化网速显示。  




准备
----

**此教程针对手持 Clash 订阅链接的用户, 如果你还没有Clash订阅链接 [请看这里](https://github.com/githubvpn007/v2rayNvpn)**  



<br/>
<br/>


步骤
----



**1.下载安装**

[下载地址](https://github.com/ClashDotNetFramework/ClashDotNetFramework/releases)  
[7-zip解压软件下载](https://www.7-zip.org/)  

请根据自己的系统及需求来选择对应的文件进行下载。

![](https://i.postimg.cc/LsPPZ7JZ/1.png)  

exe: 安装包。下载后双击运行开始安装。  
7z: 压缩包（便携版）。下载后解压全部文件，然后双击运行主程序即可。  
x64: 64位系统。  
x86: 32位系统。  
arm: 使用arm架构芯片的机型专用。  
fonts: 字体文件。  

**注意**： 软件运行需要本机有.NET5依赖，如果首次启动的时候有如下提示，请点击“是”，然后安装对应的依赖包  

![](https://i.postimg.cc/tCmnvyPx/2.png)  


根据自己的系统类型进行选择：


![](https://i.postimg.cc/gj2r4B2s/3.png)  
![](https://i.postimg.cc/d0G70yf2/4.png)  


<br/>
<br/>




**2.语言设置**  

该软件原生支持简体中文，具体操作步骤如下：  

点击 **Settings** → **Display** → **Language**  

![](https://i.postimg.cc/B6gXTG4t/5.png)  
![](https://i.postimg.cc/gcgxrdgT/6.png)  


[如果出现如上图这种比较奇怪的中文字体，说明本机缺少部分字体库，可以回到官方下载页面下载对应的文字库，解压后双击运行，点击安装。然后重启一次ClashDotNetFramework客户端。](#1)  


![](https://i.postimg.cc/QCYCzkB3/7.png)  
![](https://i.postimg.cc/XYCq254R/8.png)  
![](https://i.postimg.cc/PqbxHkLK/9.png)  

然后字体就可以正常显示了：  

![](https://i.postimg.cc/Ss7zgM7S/10.png)  



<br/>
<br/>



**3.添加订阅**  

(1)首先复制好自己的Clash订阅链接。  [没有订阅地址看这里](https://github.com/githubvpn007/v2rayNvpn)  
然后点击 **主页** → **配置**，点击加号位置，然后在弹出的窗口中粘贴自己的Clash订阅链接并点击订阅。  

![](https://i.postimg.cc/XYRG38sN/11.png)   
![](https://i.postimg.cc/1tZq0HF7/12.png)  



(2)然后点击一下自己刚添加的这个订阅，显示为绿色高亮，才是选中状态。  

![](https://i.postimg.cc/c4J8c6KW/13.png)  



(3)然后在**主页**上点击**代理**，即可看到订阅中的节点。小闪电按钮可以快速检测可用性。

![](https://i.postimg.cc/ZK0CdggK/14.png)  

注意：Clash使用 HTTP HEAD 方法对测试网址（server_check_url）进行网页相应测试，以确认节点的可用性。数值在5000以内均为正常值，超出则显示为超时。数值大小和网速快慢没有什么关系。


<br/>
<br/>



**4.启动代理**  


(1)在上一步中选好节点，点击**设置**，然后勾选**系统代理**，即可科学上网。

![](https://i.postimg.cc/qvhh9YXZ/15.png)  


(2)代理启动以后，主页右侧的表格会有所波动。  


![](https://i.postimg.cc/hPwhbsW8/16.png)   


<br/>
<br/>


## 完成  



## 本项目不做VPN分享，如果您希望获得最佳的科学上网方案 [点击这里](https://github.com/githubvpn007/v2rayNvpn)  

<br/>

## 如果你想知道clash/ss/ssr/v2ray/trojan 的区别的话 [请点这里](https://github.com/githubvpn007/proxy)
















