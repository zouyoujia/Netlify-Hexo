title: 配置域名
date: 2017-6-30
---
# 如果你使用自己的域名
### 先在 Netlify 绑定域名
请打开 [Netlify 控制面板](https://app.netlify.com)，进入你的网站设置界面，点击绿色 Set up domain 

把域名输入进去，点击*白色 USE ANOTHER DNS*，Netlify 那里就设置好了。

### 再在域名控制台解析域名
进入[域名控制台](https://console.qcloud.com/domain/mydomain)，将 @ CNAME 到 www.netlify.com.

像这样

![Screenshot_2017-07-02-23-41-18-540.png](https://ooo.0o0.ooo/2017/07/02/595914d9d438a.png)

# 如果只是使用 Netlify 提供的二级域名
那就更改一下站点名称就好了