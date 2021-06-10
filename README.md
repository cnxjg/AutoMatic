# 阿里云盘小白羊版

#### 项目说明

这是我个人基于阿里云盘网页版开发的PC客户端，已经实现了阿里云盘官方客户端的基本功能

<br />

> 6月10日已更新v1.6.10修正因阿里云盘API升级导致的无法加载文件列表BUG，请下载新版升级（win版，mac版都已经上传）

  <br />
  
Windows：[v1.6.10 https://wwe.lanzoui.com/b01npsg8h](https://wwe.lanzoui.com/b01npsg8h)

MacOS：[v1.6.10 https://wwe.lanzoui.com/b01nqc4gd](https://wwe.lanzoui.com/b01nqc4gd)

<br />

已经发布在小众软件发现频道，大爱小众[meta.appinn.net](meta.appinn.net)

<br />

``````
2021年6月10日 已完成功能：
1.支持 扫码登录/Cookie登录
2.支持 阿里云盘基本功能(列出文件/重命名/移动/回收站/收藏夹)
3.支持 在线预览全格式原画视频（非转码）,在线预览图片、文本
4.支持 批量下载文件/文件夹，多文件同时下载，支持断点续传，可以稳定满速下载
5.支持 批量上传文件/文件夹，多文件同时上传，支持断点续传
6.支持 保存别人通过秒传链接分享的文件，支持导入115秒传链接的文件
7.支持 Windows / MacOS 双系统

开发中功能：
文件洗码工具
``````

<br />

![ui](https://files.xiami.com/musician-avatar/07d8ec1a38a5462c3afbfac41413b8af/a7a5f9bd75333768990a48931fd4f6d3-846x558.gif)


<br />

截图看不了的话自己点：[截图视频](https://files.xiami.com/musician-avatar/07d8ec1a38a5462c3afbfac41413b8af/a7a5f9bd75333768990a48931fd4f6d3-846x558.gif)
 
 <br />
  
``````
功能规划：
6. 文件加密/洗码工具
7. 离线下载功能
``````

<br />

``````
秒传链接：
1. 保存别人分享的阿里云盘秒传链接，到自己的网盘内
2. 保存别人分享的115秒传链接(靠运气)到自己的网盘内
``````

<br />

``````
文件加密、洗码工具（单独提供的小程序）
1.可以对文件快速洗码(1秒内)，给文件生成新的sha1码，然后再上传到网盘（视频洗码后不影响在线预览）
2.可以对文件快速完整加密，加密后的文件无法预览，保护隐私（视频无法预览和截图，图片/文本/Doc/Pdf等文件无法在线预览）
3.可以对加密后的文件，快速解密恢复为原始文件
``````

<br />

``````
离线下载：
1.可以自己一键配置离线服务器、使用公共离线服务器。实现电驴、磁力链接的下载
2.可以下载后自动上传到自己的网盘内
``````
<br />


#### 常见问题
1.Mac系统下载后提示：已损坏，您应该将它移到废纸篓？

答：这是因为苹果系统要求程序被证书签名，一年688元，我没有买。请参照此链接方式二操作即可
https://blog.csdn.net/H_Zaiii/article/details/105730557

2.版本更新时我以前的下载/上传数据没有了？

答：所有数据都保存在`阿里云盘小白羊版\data\user.db`里，所以更新版本时直接用新版本覆盖旧版本就行了数据仍在


