# 草方块 Wiki
<i><p id="hitokoto">:D 获取中...</p>
<script src="https://cdn.jsdelivr.net/npm/bluebird@3/js/browser/bluebird.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/whatwg-fetch@2.0.3/fetch.min.js"></script>
<script>
  fetch('https://v1.hitokoto.cn')
    .then(function (res){
      return res.json();
    })
    .then(function (data) {
      var hitokoto = document.getElementById('hitokoto');
      hitokoto.innerText = data.hitokoto; 
    })
    .catch(function (err) {
      console.error(err);
    })
</script></i>

## 总序
Hello there.I'm Grassblock.

这里是我的百科，在这里包含了窝的介绍以及一些常见问题。

_本文档也能够在gitbook上找到，[戳这儿](https://iamgrassbolck.gitbook.io/mydoc/)_

**此wiki仍在不断更新中**

<link rel="stylesheet" href="APlayer.min.css">
<div id="aplayer"></div>
<script src="APlayer.min.js"></script>


欢迎来自 [Telegram](#Telegram) 的盆友们！

欢迎来自 [Minecraft 群组](#mc) 的朋友们！

你可以通过这些方式找到我：
[Email](mailto:grass_block@obagg.com)
[Telegram](tg://resolve?domain=gblock_cn)
[Blog](https://grassblock.wodemo.net)

**目录**

[TOC]

## SSR相关
**本页主题主要针对Android版本**
SSR，Shadowsocks r的简称 是一个科学上网的软件
### 下载
GitHub : [Shadowsocks RR](https://github.com/shadowsocksrr/shadowsocksr-android) [Maying](https://github.com/huio/Maying)
 [ShadowsocksRb](https://github.com/shadowsocksRb/shadowsocksRb-android)

### 开始使用

首先，找到提供节点的网站，频道等等
[这里是一个例子](https://lncn.org)
可以通过 Google 搜索到

之后 导入节点 （一般以ssr:// 开头）
打开 > 点击头部标题栏 > + 号 > 从剪切板导入
如果是 ssr 订阅 （一般看起来像个网站）
添加订阅 把原有的删掉（左滑） 点击确认并更新

### 安全性
_如果您非常注重安全，请阅读这里_

#### 对于使用共享节点
如果节点提供方定时（比如1h）删除一次网络日志（当然，大多数的都会这样做），那么相对比较安全，只要自己注意些（比如使用无痕窗口）就好

#### 对于自建节点
_主要是为了防止自己买的vps boom_
找到`功能设置 > 路由`，选择绕过局域网和中国大陆地址 ok！这样做可以尽可能防止某些墙内网站知晓你在科学上网。

如果您不共享，那么可能会减少boom的可能性 （x


**不要浏览一些奇奇怪怪的网站**

### 如何搭建
1. 找到合适的提供商 （eg: Azure）
2. 挑选服务器，进入后台
3. 运行SSR脚本 OK！
（相关教程可以通过 Google 搜索找到）

### 当无法连接墙外时
首先要测速 若无ping值则需要：

- 检查并更新订阅

- 检查节点端口

- 检查 SSR 中的路由配置

- 若以上设置都做了仍无作用，则需要检查你的网络

------- 本节完-------

## Telegram相关

### 下载

<span id="Telegram">Telegram</span> for Android  [Apkmirror](https://www.apkmirror.com) [AppCenter](https://rink.hockeyapp.net/apps/f972660267c948d2b5d04761f1c1a8f3)

TelegramX  for Android 
[Apkmirror ](https)

其它版本请至 [官网](www.telegram.org)

### 中文化
初来Telegram，对英语不熟悉？那么请阅读这一节！

_新版本已资瓷通过链接安装，请务必更新到最新版本_

（经典）简体中文：[➡点这里⬅，它会自动跳转到tg，直接点击确定即可](tg://setlanguage?lang=classic-zh-cn)

（聪聪）简体中文：[➡点这里⬅，它会自动跳转到tg，直接点击确定即可](tg://setlanguage?lang=zhcncc)


更多版本可以关注这个频道： @Tele_zh_tw，里面还有各种导航，Enjoy！;-)

### 新手必要设置
1. 两步验证：这样可以进一步防止盗号，虚拟号码被收回等情况
> 开启方法：侧边栏设置 > 隐私与安全 > 两步验证
2. 邀请权限：防止被拉入不必要的群组
> 开启方法：侧边栏设置 > 隐私与安全 > 邀请权限控制 > “我的联系人”或者“不允许任何人”

<span style='color:#0080ff;'>设置里还有更多好玩的，快去探索8！</span>

### 好玩实用的群组&机器人&频道推荐
**<span style='color:#ff0000;'>排名不分先后，如果想添加收录，请[Email 我](mailto:grass_block@obagg.com)</span>**

相关文章 ： [Telegram: 一份更完整的群组推荐，包含社群 / 频道 / 机器人 - Leonn 的博客](https://blog.liyuans.com/archives/telegram-recommendation.html)

<span style='background-color:#ffc000;'>快速跳转： [群组](#001) [频道](#002) [机器人](#003)</span>

<h4 id="001">群组</h4>

@Javaer Java交流群

@beijing_cn 北京同城交流

@minecraft2333 ~~沙雕~~mc交流群

@google_drive 谷歌·云端硬盘交流（主要是交流怎样获得&用无限空间）~~（其实就是交流怎样钻空子）~~

@NetEaseMusic 网易云吹水

@wordpress_zh Wordpress中文交流

@coder_ot 码农们的吹（喝）水（茶）区

@umr2333 某~~沙雕~~月更阿婆主的吹水

@googlecn 谷歌粉们的家

@tiebatelegram 这个群我不知道怎么说好了………

@tgzhcn 汇聚 Telegram 中文圈大师、大佬、大腕、大亨、精英、翘楚、领军、巨贾、首脑、状元、达人、奇葩、圣手、股肱、佼佼者、后起之秀...

窝：~~这啥玩意儿~~

@tgroupsforzh 发现更多好玩群组~~其实一点儿都不好玩儿~~

<h4 id="002">频道</h4>

@Minecraft_daily MC中文资讯

@gdurl Google drive 资源集合

@Getfreecloud 某节点提供频道

@umr233333 分享各种沙雕玩意儿

@Matcha_talk_time 什么都有分享的日常频道

@shitpost 国外的搞笑图片合集

@TinySnow4Yi 一个不正经的敏感向男孩子的大学进行时~~其实奏是沙雕~~

@freesssssssssssssr 免费梯子网站收集

@JacobEMK 各个软件更新的公告板

@Digitalimage 诉说图片中的故事

@AndroidThemes TG官方主题频道

https://t.me/joinchat/AAAAAEv-15EZnhd7PpNRgw
各种各样的壁纸

@mdqwsn 一些汉化软件

@NineTo5Google 英文科技资讯

@qinghua_box 土味情话（误


<h4 id="003">机器人</h4>
@botfather 万恶之源

@alert_bot 提醒bot 可以作为Telegram X 用户对于 Telegram 中新版特性的替换方案

@MinecraftBot 在Telegram快速管理mc账户

@ssrtoolbot 在 Telegram 上获取ssr节点

@GmailBot 收发 Gmail

@group_captcha_bot 入群新成员验证，可以有效应对清真等用户。   关于Telegram 清真 的信息，请至[这里](https://m.zh.wikipedia.org/Telegram)查看 

@CNOstraTestBot 让群友帮助检举消息

@typcn_soliloquize_bot 不仅仅是数据分析，还多了一些好玩的东西

@werewolfbot 在 Telegram 上玩狼人杀

@GoogleSearchUnofficialBot 谷歌搜索，不过每天有次数限制（相对于所有用户的总和而言），晚上有可能就被和谐了

@xtaorss_bot 一个简单的RSS阅读器 ，貌似连输出格式都不提供

@ehForwarderBot 帮助你收发各类社交软件的消息，貌似也资瓷某绿色图标软件

@AntiServiceMessageBot 清除服务消息（eg：入群消息）

@kamigo_bot line上的卡米狗来到Telegram了！

@HarukaAyaBot 一个功能强大的群组管理机器人

@NyanChanBot 一个不知道怎么说好的机器人
> 把它拉入群组，然后输入`/抱` 你就看到了

@IFTTT 一个强大的机器人，可以帮你连接几百种服务到 Telegram。
> 需要配合官网食用 [点我跳转](https://ifftt.com)

@noautopinbot **对于把群组设置为频道讨论群的大绒布球可能有用** 帮助你自动取消置顶频道消息并还原为原来的置顶消息
> 需要设为群组管理员，并开启 "删除消息" 和 "置顶消息" 的权限

@FengFAQBot 一个强大的关键词回复，比隔壁的好一些 >3<支持按钮的功能很赞
> 为发挥它的最大功能，请将它拉入群中并设置管理员，喵~~


### 如何写一个 （真正可用的） Telegram bot
关于如何创建bot，请去 @botfather
Here are the main steps.
1. 下载任意高级终端 和 python 编辑器~~废话~~
2. 终端上输入 `install python-telegram-bot` 等待完成
3. 按照GitHub等平台上的教程或者自己码~~废话＊2~~
4. 放在终端上运行，完成！

### Telegram 第三方客户端推荐
1. Plus

2. Graph Messager

3. Unigram

4. nekogram


##  [Minecraft](https://minecraft.net) 相关

> <span style='color:#AAB8B8;' id="mc">Minecraft</span> 是一款风靡全球的高自由度沙盒游戏，由瑞典Mojang AB和4J Studios开发。于2009年5月13日发行。 Minecraft有PC版、PE版、PlayStation版、XBox版Windows 10版和树莓派版五个版本，较为流行的是PC（电脑）版和PE（携带）版。
### 下载
**请支持正版，本站提供的链接仅供学习交流**

 1. Apkpure 评论区 是个不错的地方 更新也很及时（关键都是dalao）
 2. 一些 Telegram 频道也提供这些服务 比如：  @Minecraft_coolapk
 3. 一些博客也提供了下载
比如：[llashleyll 的博客](https://llashleyll.wodemo.net)
想玩 Java版？ 请下载[启动器](https://m.baidu.com/from=fooView/s?pn=10&usm=2&word=mc启动器)
### 开始游戏
下载安装完毕后请查看游戏内"帮助"。
[Read More](https://minecraft-zh.gamepedia.com/Minecraft_Wiki)

### 与朋友们一起玩
快速跳转 ： [局域网](#005) [服务器](#006)
<h4 id="005">局域网联机</h4>
理论上说，如果你和你的基友在同一WiFi下，在 “ 好友 ” 项中就可以找到了
然鹅，这有时不起作用的说。你可以尝试以下方法：
- 检查 你 和 基友 的网络连接
- 任意一方开启“WLAN热点”，然后连接到介个热点
（窝好像在说废话）
- ~~玩别的游戏~~


<h4 id="006">服务器</h4>


## 如何搭建（创建）自己的博客

## 文档托管平台推荐
1 Medium
官网：medium.com
特色：
2 notion
3 hackmd (目前在用)
4 Google 文档 （谷歌家的）
5 Telegraph 
6 Gitbook
7 Blogspot
8 Evernote (印象笔记)

## 优雅地使用hackmd
Hackmd是一个方便的Markdown协作笔记平台(需要挂梯)。

它本身无需注册帐号即可免费使用，但为了获得更好的使用体验，仍请阁下 [注册帐号](https://hackmd.io/sign)
下面介绍几个功能，让它变得更好用
### _汇入_

### 自定义链接
### 模式
### 更多
请阅读官方文档 []()
## 关于我
[可以先阅读下这篇文章](https://gblockcn.blogspot.com/2019/11/Introduction.html)
