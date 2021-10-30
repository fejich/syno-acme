## 修改说明 - 2021.10.30


1）更改了脚本 acme.sh 的下载地址：
+ 更新到最新 3.0.1 版本
+ 使用了 https://ghproxy.com/ 避免国内直连 github 抽风问题

2）2021-08-01起 v3版本的 acme.sh 的默认证书颁发机构改为了 ZeroSSL

申请证书之前，需要先在 ZeroSSL官方网站：(https://zerossl.com/) 注册账号


### 关于ZeroSSL
ZeroSSL在2016年就已经推出，和Let’s Encrypt一样，证书有效期只有90天，支持泛域名SSL证书。和Let’s Encrypt不同的是，ZeroSSL API没有速率限制，不存在同一IP多次申请SSL证书被限制的问题,ZeroSSL还提供了WEB界面可在后台管理SSL证书,相比Let’s Encrypt功能更加丰富。

以下是原项目信息

↓↓↓↓↓↓
---

## syno-acme
通过acme协议更新群晖HTTPS泛域名证书的自动脚本

使用方法参见: [http://www.up4dev.com/2018/05/29/synology-ssl-wildcard-cert-update/](http://www.up4dev.com/2018/05/29/synology-ssl-wildcard-cert-update/)
