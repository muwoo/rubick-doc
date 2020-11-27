# 环境准备
## 下载 rubick
[rubick download v0.0.2](https://gitlab.91jkys.com/web/rubick/blob/feat-devtools/build/rubick-0.0.2.pkg)

## 配置代理
下载 chrome SwitchyOmega 插件，转发网页请求到 rubick 客户端 [SwitchyOmega](https://chrome.google.com/webstore/detail/proxy-switchyomega/padekgcemlokbadohgkifijomclgjgif)
下载完成后配置如下：
![](http://static.91jkys.com/activity/img/9847fa0cc1d2433a94ec9577451830aa.png)

开启SwitchyOmega后，在浏览器浏览页面，软件就会开始抓包。

## 安装证书

### mac
点击开启网络抓包后，点击 `证书` 按钮下载证书。

![](http://static.91jkys.com/activity/img/ebab0382ef3d40439443714ada01283f.png)
双击rootCA.crt 进行安装
Mac：安装后在KeyChain app中找到证书AnyProxy, 修改简介为信任。

![](http://static.91jkys.com/activity/img/4ebce555b1634efeac065648ae54783b.png)

### ios
ios 扫码后，点击下载 `cert` 证书

![](http://static.91jkys.com/activity/img/7cfb3959d051479f9e11f1ac7b98ddb1.png)
证书下载完成后，在 "设置 -> 通用 -> 描述文件与设备管理" 里面信任证书：
<img src='https://zos.alipayobjects.com/rmsportal/BrugmMelGVysLDOIBblj.png' width='250' />

最后再配置一下局域网的代理

<img src='http://static.91jkys.com/activity/img/3a3c5fcc19804b4e8dbd3096fa62ff5b.jpg' width='250' />


