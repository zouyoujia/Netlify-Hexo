本项目不同与 @Bitmoe 的 Hexo 便携版，本项目是上传了源码在云端进行编译渲染的，整个步骤在浏览器中完成，不需要在电脑上安装大量文件，节省配置时间并降低故障发生率。当使用本地版 Hexo 时发生任何问题或故障可以试试用本项目解决

本项目还支持自定义域名的 HTTPS 证书

如果是手机，先戳右下角的 Desktop Version

# 0x00
你得有一个 GitHub 账号，最好有一个[域名](https://dnspod.qcloud.com)，也可以使用 Netlify 提供的二级域名

# 0x01
(右上角)先戳 Star，再戳 Fork

# 0x02
打开 `_config.yml` 文件   
点击右上角的笔   
根据提示修改内容
完成后点击下方的 `Commit Changes`

# 0x03
打开 [Netlify 网站](https://app.netlify.com)   
使用 GitHub 账号登录

# 0x04
点击 `New Site From Git`   
选择 GitHub   
授权登录

# 0x05
选择刚刚 Fork 的 `Netlify-Hexo`    
在 Build command 中输入 `hexo g`   
在 Publish directory 中输入 `public`

# 0x06
点击 deploy 按钮，等待大约一分钟时间，点击上面那串灰色的网址，根据提示完成后续操作
