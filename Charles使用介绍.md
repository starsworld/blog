
Charles是一款抓包工具。它的原理：配置Charles为本机HTTP代理服务器，所有的HTTP请求都将通过Charles转发，这样就可以查看、修改所有经过它的http请求了。  
下载地址：[Charles官网](https://www.charlesproxy.com/)  
注意问题：谷歌浏览器、微信开发者工具默认可能不会使用系统代理，需要手动配置系统代理后，才能实现拦截请求。  
Registered Name: https://zhile.io  
License Key: 48891cf209c6d32bf4  
Charles功能很强大，重点关注两项：代理转发与截取移动端网络请求。  
###代理转发
![代理设置](https://github.com/starsworld/blog/blob/master/image/1.jpeg) 
![转发设置](https://github.com/starsworld/blog/blob/master/image/2.jpeg)
主要是使用了Map Remote功能
##注意问题
https服务器上不允许发送http请求，需要适配