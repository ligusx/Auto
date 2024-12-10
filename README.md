自动抓取合并互联网上的公开节点。
🚀 免费节点,🚀免费节点订阅,🚀v2ray免费节点,ssr免费节点订阅,clash免费节点订阅,免费梯子,免费翻墙,免费科学上网,免费ss/v2ray/trojan/clash节点,谷歌商店,翻墙梯子

## 公告
本项目fork [NoMoreWalls](https://github.com/peasoft/NoMoreWalls)
为防止失联，[peasoft](https://github.com/peasoft)建立了镜像：<https://peasoft.github.io/NWalls.html>

## 关于 Google Play 等服务在国内无法使用的解决方法

由于 Google 调整了服务器安排，将原有的国外服务器的**域名**调整到了国内专版，但是**服务器**还没跟上，导致 Google Play 等服务在国内连上的是**空域名**，直接不能用了。当前的解决办法有：

1. **正常更新本项目的 Clash 订阅**，我们将 `googleapis.cn` 强制走了代理，让 Google Play 继续使用国外服务器，部分网络架构（如本机运行 Clash For Android）下服务能够恢复正常。如果您使用的是本项目提供的规则片段，请在 `rules` 开头加上：
```yaml
  - DOMAIN-SUFFIX,googleapis.cn,🚀 选择代理
  - DOMAIN-SUFFIX,xn--ngstr-lra8j.com,DIRECT # Google Play 国外/国内 服务器
  - DOMAIN-SUFFIX,xn--ngstr-cn-8za9o.com,DIRECT # Google Play 纯国内 服务器，尚未完成部署
```
2. **如果方案 1 无效，且你的手机已 ROOT，请解除 GMS 锁区**，安装 Magisk 模块 [Unlock-cn-gms](https://github.com/fei-ke/unlock-cn-gms)（[zip 下载](https://github.com/fei-ke/unlock-cn-gms/releases/download/v3.4/unlock-cn-gms-v3.4.zip)），这不一定适合所有手机，请先关注您手机中相关锁区文件的位置。
3. **如果你的手机未 ROOT，请使用 Clash For Android 试一试**，有概率正常。项目没了，找备份！
4. 实在不行就等等吧，但愿 Google 能尽快修复此问题。

如果此问题有进展，我们会在此更新，请及时关注。

注意：最近加速链接出现大量失效（在我所在的网络下），如果无法更新订阅，请把所有链接从上到下每个试一遍！

我们新增了 `snippets` 文件夹来存放从 `list.yml` 中拆分出的配置片段，用于将本项目提供的一些配置整合到你自己的配置中。

此项目现已添加“反 996 许可证”，请各位使用者**不要违法违规要求别人加班，自觉遵守《中华人民共和国劳动法》及其它法律法规**！

## 使用方法

添加 Base64 订阅：
- [原始链接](https://raw.githubusercontent.com/ligusx/Auto/master/list.txt)
- [JsDelivr 反代（zzko.cn）](https://cdn.jsdelivr.us/gh/ligusx/Auto@master/list.txt)
- [JsDelivr Fastly CDN](https://fastly.jsdelivr.net/gh/ligusx/Auto@master/list.txt)
- [JsDelivr Cloudflare CDN](https://testingcf.jsdelivr.net/gh/ligusx/Auto@master/list.txt)
- [JsDelivr GCore CDN](https://gcore.jsdelivr.net/gh/ligusx/Auto@master/list.txt)
- [KKGithub](https://raw.kkgithub.com/ligusx/Auto/master/list.txt)
- [FastGit](https://raw.fgit.cf/ligusx/Auto/master/list.txt)

以下加速链接可能无效：
- [KGithub](https://raw.kgithub.com/ligusx/Auto/master/list.txt)

或添加 Clash 订阅：
- [原始链接](https://raw.githubusercontent.com/ligusx/Auto/master/list.yml)
- [JsDelivr 反代（zzko.cn）](https://cdn.jsdelivr.us/gh/ligusx/Auto@master/list.yml)
- [JsDelivr Fastly CDN](https://fastly.jsdelivr.net/gh/ligusx/Auto@master/list.yml)
- [JsDelivr Cloudflare CDN](https://testingcf.jsdelivr.net/gh/ligusx/Auto@master/list.yml)
- [JsDelivr GCore CDN](https://gcore.jsdelivr.net/gh/ligusx/Auto@master/list.yml)
- [KKGithub](https://raw.kkgithub.com/ligusx/Auto/master/list.yml)
- [FastGit](https://raw.fgit.cf/ligusx/Auto/master/list.yml)

以下加速链接可能无效：
- [KGithub](https://raw.kgithub.com/ligusx/Auto/master/list.yml)

## 免责声明

订阅节点仅作学习交流使用，用于查找资料，学习知识，不做任何违法行为。所有资源均来自互联网，仅供大家交流学习使用，出现违法问题概不负责。**做出违法行为需要承担法律责任，侥幸逃脱是不可能的**！为阻止违法行为，本项目随时可以停止运行！！！
