### 老毛子Padavan固件Ngrok内网穿透远程控制路由器教程

[www.esnpc.com](https://www.esnpc.com/padavan-ngrok-router/)YeYo(博主)永久会员

老毛子 Padavan 固件？第一次听这个名字的时候有点蒙，了解一番居然还带点历史感，这里就不做太多介绍，只需记住 Padavan（啪嗒稳）就行了。Ngrok 有什么用？Ngrok 是一个反向代理，通过在公共的端点和本地运行的 Web 服务器之间建立一个安全的通道，简而言之就是将内网IP映射成对外可访问的域名，实现内网穿透。老毛子 Padavan 固件集成了 Ngrok 客户端，使用 Ngrok 的目的是用于远程监控和控制路由器。

首先，我们需要去：[https://www.ngrok.cc/](https://www.ngrok.cc/) 注册一个账户，注册成功后登录用户中心，点击隧道管理-开通隧道，选择1个适合你的服务器，这里我选择免费的立即购买，注意弹出的提醒信息，点确定。

[![](https://cubox.pro/c/filters:no_upscale()?imageUrl=https%3A%2F%2Fwww.esnpc.com%2Fwp-content%2Fuploads%2F2018%2F12%2FNgrok.png)](https://www.esnpc.com/wp-content/uploads/2018/12/Ngrok.png)

接下来，填写隧道信息，隧道协议选择http，隧道名称只是一个标识名称，无特殊意义，这里我填写 My Router；前置域名实际上就是系统分配给你二级域名的前缀，一旦注册是不可更改的，你可以填写一个你比较容易记住的名称（只能是纯字符、数字或二者的组合，不可有其它字符），这里我填写的是 MyRouter01；本地端口，一般默认即可；http验证用户名和http验证密码根据自己需要填写，这里我是留空的，代表不需要验证用户名和密码。以上都填好后，点击确定添加即可。

[![](https://cubox.pro/c/filters:no_upscale()?imageUrl=https%3A%2F%2Fwww.esnpc.com%2Fwp-content%2Fuploads%2F2018%2F12%2FNgrok-2.png)](https://www.esnpc.com/wp-content/uploads/2018/12/Ngrok-2.png)

打开隧道管理，右侧就会列出我们刚才添加的隧道，点击隧道 ID 会展开隧道基本信息，这里我们要记下隧道域名、服务器地址、服务器端口这三项，后面我们会用到。

[![](https://cubox.pro/c/filters:no_upscale()?imageUrl=https%3A%2F%2Fwww.esnpc.com%2Fwp-content%2Fuploads%2F2018%2F12%2FNgrok-3.png)](https://www.esnpc.com/wp-content/uploads/2018/12/Ngrok-3.png)

登录路由器 Padavan（啪嗒稳）管理界面，扩展功能-花生壳内网版-Ngrok 配置客户端。启用 Ngrok 内网穿透 开关开启；服务器地址填写我们从 Ngrok 获取的地址，不过别忘了前面要加上 server. 要不然远程登录的时候无法解析；服务器端口填写从 Ngrok 官网获取的端口4443；协议类型http；本地地址一般是你路由的默认的地址；本地端口80；分配域名填写从 Ngrok 官网获取的隧道域名，这里只需填写隧道域名即可，不需要填写完整系统分配的二级域名地址，否则远程登录的时候无法解析。填写检查无误后，保存以应用本页面设置。

[![](https://cubox.pro/c/filters:no_upscale()?imageUrl=https%3A%2F%2Fwww.esnpc.com%2Fwp-content%2Fuploads%2F2018%2F12%2FNgrok-4.png)](https://www.esnpc.com/wp-content/uploads/2018/12/Ngrok-4.png)

重启路由器，等待一会儿后，在浏览器地址栏中打开 MyRouter01.free.idcfengye.com 输入你的路由器用户名及登录密码，即可远程监控和控制啦！

另外，石头213编写的[啪嗒路由器APP](https://www.esnpc.com/padarouter-app/)，适配了 Padavan 老毛子固件，使用手机端啪嗒路由器APP，可随时随地远程进行监控和控制路由器，简直就是高端、大气、上档次！

[![](https://cubox.pro/c/filters:no_upscale()?imageUrl=https%3A%2F%2Fwww.esnpc.com%2Fwp-content%2Fuploads%2F2018%2F12%2FPadavan-App.jpg)](https://www.esnpc.com/wp-content/uploads/2018/12/Padavan-App.jpg)

**声明：**本站所有文章，如无特殊说明或标注，均为本站原创发布。任何个人或组织，在未征得本站同意时，禁止复制、盗用、采集、发布本站内容到任何网站、书籍等各类媒体平台。如若本站内容侵犯了原著者的合法权益，可联系我们进行处理。

[Ngrok](https://www.esnpc.com/tag/ngrok/)[Padavan](https://www.esnpc.com/tag/padavan/)[老毛子](https://www.esnpc.com/tag/%e8%80%81%e6%af%9b%e5%ad%90/)[路由器](https://www.esnpc.com/tag/%e8%b7%af%e7%94%b1%e5%99%a8/)

[查看原网页: www.esnpc.com](https://www.esnpc.com/padavan-ngrok-router/)
