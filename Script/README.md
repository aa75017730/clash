# 一些 Stash 的覆写文件及使用说明
```
```
## 关于 Stash
Stash 是一款 iOS 平台基于规则的多协议代理客户端，完全兼容 clash premium 配置，支持 Rule Set 规则、按需连接、SSID Policy Group、MitM、HTTP 改写等新特性。

* App Store 链接：https://apps.apple.com/app/stash/id1596063349
* 官方 Twitter：https://twitter.com/StashNetwork
* Telegram 群组：https://t.me/stashnetworks
* Telegram 频道：https://t.me/RnNc2RaV8x0wMzQ0
* 官方github库：https://github.com/STASH-NETWORKS-LIMITED/stash-example  
* Stash简介：https://stash.wiki
* Stash配置样例：https://stash.wiki/features/example-config
```
```

## Stash节点编写规则

|节点类型|Stash参考规则|Clash参考规则|
|---|---|---|
|*配置汇总*|*[配置汇总](https://stash.wiki/proxy-protocols/proxy-types)*|https://github.com/aa75017730/clash/blob/main/All%20Configuration%20Options.yaml|
|*SS*|*[SS节点编写范例](https://github.com/STASH-NETWORKS-LIMITED/stash-example/blob/main/config.yaml#L206)*|https://github.com/aa75017730/clash/blob/main/All%20Configuration%20Options.yaml#L157|
|*SSR*|*[SSR节点编写范例](https://github.com/STASH-NETWORKS-LIMITED/stash-example/blob/main/config.yaml#L379)*|https://github.com/aa75017730/clash/blob/main/All%20Configuration%20Options.yaml#L342|
|*Vmess*|*[Vmess节点编写范例](https://github.com/STASH-NETWORKS-LIMITED/stash-example/blob/main/config.yaml#L249)*|https://github.com/aa75017730/clash/blob/main/All%20Configuration%20Options.yaml#L193|
|*Socks5*|*[Socks5节点编写范例](https://github.com/STASH-NETWORKS-LIMITED/stash-example/blob/main/config.yaml#L317)*|https://github.com/aa75017730/clash/blob/main/All%20Configuration%20Options.yaml#L261|
|*Http*|*[Http节点编写范例](https://github.com/STASH-NETWORKS-LIMITED/stash-example/blob/main/config.yaml#L328)*|https://github.com/aa75017730/clash/blob/main/All%20Configuration%20Options.yaml#L272|
|*Trojan*|*[Trojan节点编写范例](https://github.com/STASH-NETWORKS-LIMITED/stash-example/blob/main/config.yaml#L350)*|https://github.com/aa75017730/clash/blob/main/All%20Configuration%20Options.yaml#L295|
|*Vless*|*[Vless节点编写范例](https://github.com/STASH-NETWORKS-LIMITED/stash-example/blob/main/config.yaml#L399)*||
|*Snell*|*[Snell节点编写范例](https://github.com/STASH-NETWORKS-LIMITED/stash-example/blob/main/config.yaml#L338)*|https://github.com/aa75017730/clash/blob/main/All%20Configuration%20Options.yaml#L283|
|*Hysteria*|*[Hysteria节点编写范例](https://github.com/STASH-NETWORKS-LIMITED/stash-example/blob/main/config.yaml#L363)*||
```
```
### 覆写文件的安装及使用
* `首页`-`覆写`-`安装覆写`进行安装，需开启`重写`、`覆写`、`MitM`功能
### 参考库
* https://github.com/jnlaoshu/MySelf  
* https://github.com/Infatuation-Fei/rule  
* https://github.com/Coldvvater/Clash
```
```
### 覆写列表
|**状态**|**名称**|**订阅链接**|**介绍**|
|---|---|---|---|
| 🟢 |__Tiktok-JP.stoverride__|[选中,右键复制链接地址或点击查看代码](https://raw.githubusercontent.com/aa75017730/clash/main/Rewrite/TikTokUnlock/Tiktok-JP.stoverride)|TikTok解锁-日本|
| 🟢 |__1Blocker.stoverride__|[选中,右键复制链接地址或点击查看代码](https://raw.githubusercontent.com/aa75017730/clash/main/Script/1Blocker.stoverride)|1Blocker解锁|
| 🟢 |__ADRulesLite.stoverride__|[选中,右键复制链接地址或点击查看代码](https://raw.githubusercontent.com/aa75017730/clash/main/Script/ADRulesLite.stoverride)|去广告规则，分流去广告|
| 🟢 |__BackgroundEraserProCrack1.stoverride__|[选中,右键复制链接地址或点击查看代码](https://raw.githubusercontent.com/aa75017730/clash/main/Script/BackgroundEraserProCrack1.stoverride)|傲软抠图解锁会员(支持新版1.5.1)|
| 🟢 |__MaKaLongWanTu.stoverride__|[选中,右键复制链接地址或点击查看代码](https://raw.githubusercontent.com/aa75017730/clash/main/Script/MaKaLongWanTu.stoverride)|解锁马卡龙玩图订阅|
| 🟢 |__Google.stoverride__|[选中,右键复制链接地址或点击查看代码](https://raw.githubusercontent.com/aa75017730/clash/main/Script/Google.stoverride)|Google CN 重定向|
| 🔴 |__InShot.stoverride__|---|InShot解锁订阅|
| 🟢 |__Kuwo.stoverride__|[选中,右键复制链接地址或点击查看代码](https://raw.githubusercontent.com/aa75017730/clash/main/Script/Kuwo.stoverride)|酷我解锁VIP、换肤、无损下载及听书(部分失效)|
| 🟢 |__MaKaLongWanTu.stoverride__|[选中,右键复制链接地址或点击查看代码](https://raw.githubusercontent.com/aa75017730/clash/main/Script/MaKaLongWanTu.stoverride)|解锁马卡龙玩图订阅 > 支持商店最新5.3.4(2022.01.24)|
| 🟢 |__MeiTuXiuXiu.stoverride__|[选中,右键复制链接地址或点击查看代码](https://raw.githubusercontent.com/aa75017730/clash/main/Script/MeiTuXiuXiu.stoverride)|美图秀秀(2022.01.17)|
| 🟢 |__MeiYanXiangJi (2).stoverride__|[选中,右键复制链接地址或点击查看代码](https://raw.githubusercontent.com/aa75017730/clash/main/Script/MeiYanXiangJi%20(2).stoverride)|美颜相机解锁紫钻|
| 🟢 |__PornHubPremiumCrack.stoverride__|[选中,右键复制链接地址或点击查看代码](https://raw.githubusercontent.com/aa75017730/clash/main/Script/PornHubPremiumCrack.stoverride)|解锁网页PornHub|
| 🟢 |__QiMaoXiaoShuo.stoverride__|[选中,右键复制链接地址或点击查看代码](https://raw.githubusercontent.com/aa75017730/clash/main/Script/QiMaoXiaoShuo.stoverride)|七猫小说VIP|
| 🔴 |__Spotify-proto.stoverride__|---|spotify部分解锁premium|
| 🟢 |__StartupAD.stoverride__|[选中,右键复制链接地址或点击查看代码](https://raw.githubusercontent.com/aa75017730/clash/main/Script/StartupAD.stoverride)|嘀嗒出行及京东APP开屏去广告，具体APP请直接进入链接查看|
| 🟢 |__VUEpro.stoverride__|[选中,右键复制链接地址或点击查看代码](https://raw.githubusercontent.com/aa75017730/clash/main/Script/VUEpro.stoverride)|VUE 解锁PRO会员，享用专业功能|
| 🟢 |__XMind.stoverride__|[选中,右键复制链接地址或点击查看代码](https://raw.githubusercontent.com/aa75017730/clash/main/Script/XMind.stoverride)|XMind解锁Pro|
| 🟢 |__Zhihu.stoverride__|[选中,右键复制链接地址或点击查看代码](https://raw.githubusercontent.com/aa75017730/clash/main/Script/Zhihu.stoverride)|知乎去广告及阅读体验增强,适配知乎8.3.0(8020)|
| 🟢 |__camscanner.stoverride__|[选中,右键复制链接地址或点击查看代码](https://raw.githubusercontent.com/aa75017730/clash/main/Script/camscanner.stoverride)|扫描全能王 pro|
| 🟢 |__jdjf_price.stoverride__|[选中,右键复制链接地址或点击查看代码](https://raw.githubusercontent.com/aa75017730/clash/main/Script/jdjf_price.stoverride)|京东比价|
| 🔴 |__kwyy.stoverride__|---|解锁酷我音乐会员听书|
| 🔴 |__kwyyxz.stoverride__|---|解锁酷我音乐会员下载|
| 🟢 |__qzz.stoverride__|[选中,右键复制链接地址或点击查看代码](https://raw.githubusercontent.com/aa75017730/clash/main/Script/qzz.stoverride)|趣制作2.1.1解锁Pro|
| 🟢 |__weixinNOAD.stoverride__|[选中,右键复制链接地址或点击查看代码](https://raw.githubusercontent.com/aa75017730/clash/main/Script/weixinNOAD.stoverride)|微信去广告|
| 🟢 |__weixingzhNOAD.stoverride__|[选中,右键复制链接地址或点击查看代码](https://raw.githubusercontent.com/aa75017730/clash/main/Script/weixingzhNOAD.stoverride)|微信公众号去广告|
| 🟢 |__Boxjs.stoverride__|[选中,右键复制链接地址或点击查看代码](https://raw.githubusercontent.com/aa75017730/clash/main/Script/Boxjs.stoverride)|Boxjs商店版|
| 🟢 |__Sub-Store.stoverride__|[选中,右键复制链接地址或点击查看代码](https://raw.githubusercontent.com/aa75017730/clash/main/Script/Sub-Store.stoverride)|Sub-Store高级订阅管理工具|
| 🟢 |__TestFlight.stoverride__|[选中,右键复制链接地址或点击查看代码](https://raw.githubusercontent.com/aa75017730/clash/main/Script/TestFlight.stoverride)|TestFlight区域限制解除|
| 🟢 |__WpsOffice.stoverride__|[选中,右键复制链接地址或点击查看代码](https://raw.githubusercontent.com/aa75017730/clash/main/Script/WpsOffice.stoverride)|WPS Office解锁超级会员部分功能|
| 🟢 |__BaiDu.stoverride__|[选中,右键复制链接地址或点击查看代码](https://raw.githubusercontent.com/aa75017730/clash/main/Script/BaiDu.stoverride)|百度搜索防跳转|
| 🟢 |__jd_tb_price.stoverride__|[选中,右键复制链接地址或点击查看代码](https://raw.githubusercontent.com/aa75017730/clash/main/Script/jd_tb_price.stoverride)|京东比价|
| 🟢 |__JDPrice.stoverride__|[选中,右键复制链接地址或点击查看代码](https://raw.githubusercontent.com/jnlaoshu/MySelf/main/Stash/Script/JDPrice.stoverride)|京东历史价格|
| 🟢 |__Youdao.stoverride__|[选中,右键复制链接地址或点击查看代码](https://raw.githubusercontent.com/aa75017730/clash/main/Script/Youdao.stoverride)|有道云笔记解锁VIP高级功能|
| 🟢 |__Notability.stoverride__|[选中,右键复制链接地址或点击查看代码](https://raw.githubusercontent.com/aa75017730/clash/main/Script/Notability.stoverride)|Notability解锁订阅|

```
```
# 鸣谢
### 排名不分先后
* [blackmatrix7](https://github.com/blackmatrix7)
* [yqc007](https://github.com/yqc007)
* [I-am-R-E](https://github.com/I-am-R-E)
* [ddgksf2013](https://github.com/ddgksf2013)
* [app2smile](https://github.com/app2smile)
* [NobyDa](https://github.com/NobyDa)
* [githubdulong](https://github.com/githubdulong)
* [yjqiang](https://github.com/yjqiang)
* [app2smile](https://github.com/app2smile)
* [STASH-NETWORKS-LIMITED](https://github.com/STASH-NETWORKS-LIMITED)
* [jnlaoshu](https://github.com/jnlaoshu)
* [Infatuation-Fei](https://github.com/Infatuation-Fei)
* [Coldvvater](https://github.com/Coldvvater)
```
```
# 大字报
__开源JS脚本仅供学习交流🍟，欢迎stars🌟，禁止focks🈲️，否则你将被禁止🚫！禁止商业用途🈲️，否则后果自负👻！__
