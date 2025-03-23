# 第一步：注册

首先进入 https://www.cloudns.net 在右上角把语言改成中文，并点击登记。没有账户可以注册一个。

进入后选择创建区域。

![](https://raw.githubusercontent.com/houzhongcheng/houzhongcheng_picture/main/picPixPin_2025-03-23_11-54-16.png)

选择免费区域。

![](https://raw.githubusercontent.com/houzhongcheng/houzhongcheng_picture/main/picPixPin_2025-03-23_11-55-29.png)

在免费区域页面输入想注册的域名。

![](https://raw.githubusercontent.com/houzhongcheng/houzhongcheng_picture/main/picPixPin_2025-03-23_12-00-02.png)

注册好后会进入管理页面。

![](https://raw.githubusercontent.com/houzhongcheng/houzhongcheng_picture/main/picPixPin_2025-03-23_12-02-10.png)

# 第二步：托管到cloudflare

打开cloudflare官网 https://dash.cloudflare.com 点击语言改成中文，然后登陆，没有账户可以注册一个。

然后选择新建域输入需要托管的域名（刚才注册的）。然后选择免费计划（free）

![](https://raw.githubusercontent.com/houzhongcheng/houzhongcheng_picture/main/picPixPin_2025-03-23_12-12-42.png)

点击下一步然后再次进入cloudns网站的管理界面把原有的记录删除。再把cloudflare提供的记录新建并保存到记录。

![](https://raw.githubusercontent.com/houzhongcheng/houzhongcheng_picture/main/picPixPin_2025-03-23_12-16-36.png)

等待一会就可以看到cloudflare网站上你托管的域名打上了对钩。

![](https://raw.githubusercontent.com/houzhongcheng/houzhongcheng_picture/main/picPixPin_2025-03-23_12-23-31.png)

这样就托管完成了。