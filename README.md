<div align="center">
  <p style="font-size: 18px;">An open-source App Store discounts tracker built on GitHub Actions, supporting RSS, Telegram and DingTalk notifications</p>


English | [简体中文](https://github.com/eyelly-wu/appstore-discounts/blob/main/README_zh-CN.md)



[![github-stars](https://img.shields.io/github/stars/eyelly-wu/appstore-discounts?style=social "github-stars")](https://github.com/eyelly-wu/appstore-discounts/stargazers "github-stars")
[![last-commit](https://img.shields.io/github/last-commit/eyelly-wu/appstore-discounts/dev "last-commit")](https://github.com/eyelly-wu/appstore-discounts/commits/dev "last-commit")
[![github-issues](https://img.shields.io/github/issues-raw/eyelly-wu/appstore-discounts "github-issues")](https://github.com/eyelly-wu/appstore-discounts/issues "github-issues")


</div>
<details >
  <summary>Table of Contents</summary>

  [Vision](#vision)<br/>
  [Features](#features)<br/>
  [How to Subscribe](#how-to-subscribe)<br/>
  &emsp;&emsp;[RSS](#rss)<br/>
  &emsp;&emsp;[Telegram](#telegram)<br/>
  &emsp;&emsp;[DingTalk](#dingtalk)<br/>
  [Focus](#focus)<br/>
  [Operating Mechanism and Process](#operating-mechanism-and-process)<br/>
  [How to Contribute](#how-to-contribute)<br/>
  &emsp;&emsp;[1. Add  `Country or Region`  or  `App` ](#1-add--country-or-region--or--app)<br/>
  &emsp;&emsp;[2. Other](#2-other)<br/>
  [Star History](#star-history)<br/>
  [License](#license)<br/>

</details>


# Vision
Become the trusted savings assistant for  `App Store`  users, helping more people buy their favorite apps at discounted prices
# Features

* Support any  `App Store`  of any  `Country or Region`  (theoretically 🤔)
* Support tracking the price of  `App`  and  `In-App Purchases` 
* Support multiple ways to subscribe to discount information
   * RSS
   * Telegram
   * DingTalk
* Open source and free, anyone can contribute


# How to Subscribe

## RSS

|Code|Country or Region|RSS  Source|
|:-|:-|:-|
|cn|Mainland China|https://raw.githubusercontent.com/eyelly-wu/appstore-discounts/main/rss/cn.xml|
|hk|Hong Kong, China|https://raw.githubusercontent.com/eyelly-wu/appstore-discounts/main/rss/hk.xml|
|mo|Macao, China|https://raw.githubusercontent.com/eyelly-wu/appstore-discounts/main/rss/mo.xml|
|tw|Taiwan, China|https://raw.githubusercontent.com/eyelly-wu/appstore-discounts/main/rss/tw.xml|
|us|United States|https://raw.githubusercontent.com/eyelly-wu/appstore-discounts/main/rss/us.xml|
|tr|Türkiye|https://raw.githubusercontent.com/eyelly-wu/appstore-discounts/main/rss/tr.xml|

## Telegram
Click  [![telegram](https://img.shields.io/badge/Telegram-Channel-blue?style=flat&logo=telegram "telegram")](https://t.me/appstore_discounts "telegram-channel")  to Subscribe
## DingTalk
Click  [![dingtalk](https://img.alicdn.com/imgextra/i3/O1CN01WMvMRG1ks3Ixc9x1v_!!6000000004738-55-tps-32-32.svg "dingtalk")](https://qr.dingtalk.com/action/joingroup?code=v1,k1,o9TXTPxGRNhCmrTUa4cHymeJCIcRiimCsH4FqEnbEWU=&_dt_no_comment=1&origin=11 "dingtalk")  to Subscribe
# Focus
So far, we've covered `6` `Countries or Regions` and  `198` `Apps` <br />Push notifications will only be sent when there are discounts for the listed  `Country or Region`  and  `App`  below. If your  `Country or Region`  or favorite  `App`  is not on the list, feel free to add it<br />
>Special Note:  `❌`  in the table below indicates that the app does not exist in the current  `Country or Region` 's  `App Store` <br />If certain apps in the list frequently offer discounts to attract you to install and use them, and you successfully get attracted to install and use them, but end up uninstalling the app due to poor user experience. For such cases, feedback is welcome via  `Issue` . If an app receives more than  `10`  complaints, its discount information push notifications are likely to be banned

|Serial Number|App ID|Mainland China（cn）|Hong Kong, China（hk）|Macao, China（mo）|Taiwan, China（tw）|United States（us）|Türkiye（tr）|
|:-|:-|:-|:-|:-|:-|:-|:-|
|1|1481853033|Strongbox Pro|Strongbox Pro|Strongbox Pro|Strongbox Pro|Strongbox Pro|Strongbox Pro|
|2|1581140954|Noir - 为Safari添加深色模式|Noir - Dark Mode for Safari|Noir - Dark Mode for Safari|Noir - Dark Mode for Safari|Noir - Dark Mode for Safari|Noir - Dark Mode for Safari|
|3|1592917505|Noir – 为Safari添加深色模式|Noir – Dark Mode for Safari|Noir – Dark Mode for Safari|Noir – Dark Mode for Safari|Noir – Dark Mode for Safari|Noir – Dark Mode for Safari|
|4|1591620171|Stay for Safari - 浏览器伴侣|Stay for Safari - 瀏覽器伴侶|Stay for Safari - 瀏覽器伴侶|Stay for Safari - 瀏覽器伴侶|Stay for Safari|Stay for Safari|
|5|1438243180|Dark Reader for Safari|Dark Reader for Safari|Dark Reader for Safari|Dark Reader for Safari|Dark Reader for Safari|Dark Reader for Safari|
|6|625206080|❌|Tomb Raider|Tomb Raider|Tomb Raider|Tomb Raider|Tomb Raider|
|7|1108032375|❌|Rise of the Tomb Raider™|Rise of the Tomb Raider™|Rise of the Tomb Raider™|Rise of the Tomb Raider™|Rise of the Tomb Raider™|
|8|1439569401|❌|Shadow of the Tomb Raider|Shadow of the Tomb Raider|Shadow of the Tomb Raider|Shadow of the Tomb Raider|Shadow of the Tomb Raider|
|9|6459738231|❌|Lies of P|Lies of P|Lies of P|Lies of P|Lies of P|
|10|1441532941|❌|神界：原罪2|神界：原罪2|神界：原罪2|Divinity: Original Sin 2|Divinity: Original Sin 2|
|11|6449748961|❌|DEATH STRANDING DIRECTOR'S CUT|DEATH STRANDING DIRECTOR'S CUT|DEATH STRANDING DIRECTOR'S CUT|DEATH STRANDING DIRECTOR'S CUT|DEATH STRANDING DIRECTOR'S CUT|
|12|6499559693|iStat Menus 7|iStat Menus 7|iStat Menus 7|iStat Menus 7|iStat Menus 7|iStat Menus 7|
|13|6475002485|❌|Reeder.|Reeder.|Reeder.|Reeder.|Reeder.|
|14|1198176727|Controller for HomeKit|Controller for HomeKit|Controller for HomeKit|Controller for HomeKit|Controller for HomeKit|Controller for HomeKit|
|15|904280696|Things 3|Things 3|Things 3|Things 3|Things 3|Things 3|
|16|1055511498|Day One 日記：私人日記|Day One|Day One|Day One|Day One|Day One|
|17|1208145167|Picsew - 滚动截图 & 长图拼接|Picsew - 滾動截圖 & 長圖拼接|Picsew - 滾動截圖 & 長圖拼接|Picsew - 滾動截圖 & 長圖拼接|Picsew - Scrollshot & Collage|Picsew - Scrollshot & Collage|
|18|1444636541|Photomator|Photomator|Photomator|Photomator|Photomator – Photo Editor|Photomator|
|19|1444383602|Goodnotes 6：笔记，PDF，AI|Goodnotes 6：筆記，PDF，AI|Goodnotes 6：筆記，PDF，AI|Goodnotes 6：筆記，PDF，AI|Goodnotes 6: AI Notes & Docs|Goodnotes 6: AI Notes & Docs|
|20|1473785373|钱迹记账-无广告超快捷记账存钱&资产管理&预算|錢跡記帳 - 無廣告超快捷 & 資產管理 & 預算|錢跡記帳 - 無廣告超快捷 & 資產管理 & 預算|錢跡記帳 - 無廣告超快捷 & 資產管理 & 預算|Qianji - Ad-Free Bookkeeping|Qianji - Ad-Free Bookkeeping|
|21|1461652639|网络调试精灵|TCP UDP Ping  Socket 網絡調試助手|TCP UDP Ping  Socket 網絡調試助手|TCP UDP Ping  Socket 網絡調試助手|iSocketTool|iSocketTool|
|22|6499198824|蜂软扫描 - 全能扫描仪|ScanGo - PDF Document Scanner|ScanGo - PDF Document Scanner|ScanGo - PDF Document Scanner|ScanGo - PDF Document Scanner|ScanGo - PDF Document Scanner|
|23|1538124245|哪里哪里|where I put it|where I put it|where I put it|where I put it|where I put it|
|24|6446469093|口袋时钟 - StandBy待机Widget桌面翻页创意时钟|口袋時鐘-創意全屏精準錶盤懸浮顯示鎖屏桌面小組件手錶|口袋時鐘-創意全屏精準錶盤懸浮顯示鎖屏桌面小組件手錶|口袋時鐘-創意全屏精準錶盤懸浮顯示鎖屏桌面小組件手錶|Clock Pocket:standby widget|Clock Pocket:standby widget|
|25|1610668825|FyTube - 没有广告的 YouTube|FyTube -沒有廣告的 YouTube|FyTube -沒有廣告的 YouTube|FyTube -沒有廣告的 YouTube|FyTube - YouTube Without Ads|FyTube - YouTube Without Ads|
|26|1175912897|EverMemo印象便签|EverMemo印象便簽|EverMemo印象便簽|EverMemo印象便簽|EverMemo - Fastest Note|EverMemo|
|27|6504433140|LaxtTime - 日常记录/循环提醒/习惯养成/倒计时|LaxtTime|LaxtTime|LaxtTime|LaxtTime - Remember Last Time|LaxtTime - Remember Last Time|
|28|920133658|解剖和生理学|Anatomy & Physiology|Anatomy & Physiology|Anatomy & Physiology|Anatomy & Physiology|Anatomy & Physiology|
|29|6463851696|功德++ : 锁屏，Standby，桌面小组件都可以敲的木鱼|Zen++|Zen++|Zen++|Zen++|❌|
|30|1358237203|时间胶囊-寄往未来的信|時間膠囊-寄往未來的信|時間膠囊-寄往未來的信|時間膠囊-寄往未來的信|时间胶囊-寄往未来的信|时间胶囊-寄往未来的信|
|31|1316883372|音乐世界赛特斯2|❌|❌|❌|❌|❌|
|32|956086985|美元折纸|Dollar Bill Origami|Dollar Bill Origami|Dollar Bill Origami|Dollar Bill Origami|Dollar Bill Origami|
|33|1436481293|迷失岛3宇宙的尘埃|ISOLAND 3 Dust of the Universe|ISOLAND 3 Dust of the Universe|ISOLAND 3 Dust of the Universe|ISOLAND 3 Dust of the Universe|ISOLAND 3 Dust of the Universe|
|34|1422480068|Notes Writer Pro: 笔记和 PDF 标注|Notes Writer Pro 2025|Notes Writer Pro 2025|Notes Writer Pro 2025|Notes Writer Pro 2025|Notes Writer Pro 2025|
|35|6443915320|发条日签-好心情制造机|发条日签-好心情制造机|发条日签-好心情制造机|发条日签-好心情制造机|发条日签-好心情制造机|发条日签-好心情制造机|
|36|884153085|Remote, Mouse & Keyboard Pro|Remote, Mouse & Keyboard Pro|Remote, Mouse & Keyboard Pro|Remote, Mouse & Keyboard Pro|Remote, Mouse & Keyboard Pro|Remote, Mouse & Keyboard Pro|
|37|1065802380|Stream Music Player|Stream Music Player|Stream Music Player|Stream Music Player|Stream Music Player|Stream Music Player|
|38|533055404|夜星 (Night Stars)|夜星 (Night Stars)|夜星 (Night Stars)|夜星 (Night Stars)|Night Stars|Night Stars|
|39|1493379610|时光进度 - 进度管理&待办计划|時光進度 - 待辦事項四象限規劃及進度管理|時光進度 - 待辦事項四象限規劃及進度管理|時光進度 - 待辦事項四象限規劃及進度管理|bProgress - Manage Daily Tasks|bProgress - Manage Daily Tasks|
|40|1255627901|方便面 - 朋友圈图文排版好帮手|泡麵｜經典原味|泡麵｜經典原味|泡麵｜經典原味|Instant Noodles: Original|Instant Noodles: Original|
|41|1449020025|不玩手机-自律习惯养成记|不玩手机-自律习惯养成记|不玩手机-自律习惯养成记|不玩手机-自律习惯养成记|不玩手机-自律习惯养成记|不玩手机-自律习惯养成记|
|42|1576004936|化学 - 元素周期表 2025|化學 - 元素週期表 2025|化學 - 元素週期表 2025|化學 - 元素週期表 2025|Chemistry Periodic Table 2025|Chemistry Periodic Table 2025|
|43|827740598|小牛计算器(高级版)|Xmart Calculator Pro|Xmart Calculator Pro|Xmart Calculator Pro|Xmart Calculator Pro|Xmart Calculator Pro|
|44|355460798|Inspire Pro|Inspire Pro|Inspire Pro|Inspire Pro|Inspire Pro|Inspire Pro|
|45|1595313870|瓦尔登 - 日程管理，一个就够|瓦爾登 - 終極個人管理工具|瓦爾登 - 終極個人管理工具|瓦爾登 - 終極個人管理工具|Walden - Calendar/ToDo/Notes|Walden - Calendar/ToDo/Notes|
|46|6449383791|GIF录制助手-录屏、裁剪、优化、生成一站式便捷体验|GIF Recorder-ImproveEfficiency|GIF Recorder-ImproveEfficiency|GIF Recorder-ImproveEfficiency|GIF Recorder-ImproveEfficiency|GIF Recorder-ImproveEfficiency|
|47|1587301632|全能记(录音,备忘,流水)|全能備忘錄|全能備忘錄|全能備忘錄|All In One Memo|All In One Memo|
|48|1464666446|我的足迹: GPS记录仪|我的足跡: GPS記錄儀|我的足跡: GPS記錄儀|我的足跡: GPS記錄儀|MyTracks: GPS Recorder|MyTracks: GPS Recorder|
|49|1665759338|坐在罐子里的人|❌|❌|❌|❌|❌|
|50|953426154|Be Focused Pro - Focus Timer|Be Focused Pro – 專工作學習番茄計時器|Be Focused Pro – 專工作學習番茄計時器|Be Focused Pro – 專工作學習番茄計時器|Be Focused Pro - Focus Timer|Be Focused Pro- Pomodoro Timer|
|51|1238778050|纪念碑谷2|❌|❌|❌|❌|❌|
|52|1020541183|电影精灵 - 专业视频编辑和电影制作|電影精靈 - 專業視頻編輯和電影製作|電影精靈 - 專業視頻編輯和電影製作|電影精靈 - 專業視頻編輯和電影製作|MovieSpirit - Movie Maker Pro|MovieSpirit - Movie Maker Pro|
|53|576718804|aTimeLogger - 时间记录工具|aTimeLogger 2 - 私人時間記錄儀&时间表|aTimeLogger 2 - 私人時間記錄儀&时间表|aTimeLogger 2 - 私人時間記錄儀&时间表|aTimeLogger Time Tracker|aTimeLogger Time Tracker|
|54|670400597|梁的挠度|樑的撓度|樑的撓度|樑的撓度|Deflection|Deflection|
|55|1400652313|冰钓大师|❌|❌|❌|❌|❌|
|56|1551596643|模拟地铁|❌|❌|❌|❌|❌|
|57|1437479513|逃脱者：困境突围|逃脱者：困境突围|逃脱者：困境突围|逃脱者：困境突围|❌|❌|
|58|1314212521|PPHub For GitHub - 开发者必备|PPHub For GitHub - Developer|PPHub For GitHub - Developer|PPHub For GitHub - Developer|PPHub For GitHub - Developer|PPHub For GitHub - Developer|
|59|1564383045|算法导论.助手|算法導論.助手|算法導論.助手|算法導論.助手|CLRS.Helper|CLRS.Helper|
|60|1380582804|手机帝国|手機帝國|手機帝國|手機帝國|Mobile Empire|Mobile Empire|
|61|6466390901|旋转音律 Rotaeno|❌|❌|❌|❌|❌|
|62|1596406400|黄鸭证件照-最美求职考试证照制作神器|黄鸭证件照-最美求职考试证照制作神器|黄鸭证件照-最美求职考试证照制作神器|黄鸭证件照-最美求职考试证照制作神器|黄鸭证件照-最美求职考试证照制作神器|黄鸭证件照-最美求职考试证照制作神器|
|63|598581396|Kingdom Rush Frontiers 塔防史诗冒险|Kingdom Rush Frontiers 塔防生存戰爭|Kingdom Rush Frontiers 塔防生存戰爭|Kingdom Rush Frontiers 塔防生存戰爭|Kingdom Rush Frontiers TD|Kingdom Rush Frontiers TD|
|64|1157863540|泰拉瑞亚|❌|❌|❌|❌|❌|
|65|1630541373|隐私相册-私密记忆，安心记录，安全保障隐藏秘密PRAM|Private Album - PRAM|Private Album - PRAM|Private Album - PRAM|Private Album - PRAM|Private Album - PRAM|
|66|1512838461|DayCircle - 倒数|DayCircle - 倒數|DayCircle - 倒數|DayCircle - 倒數|DayCircle - Day counter|DayCircle - Day counter|
|67|1400032769|Card.Note - 多彩卡片笔记|Card.Note - 多彩卡片笔记|Card.Note - 多彩卡片笔记|Card.Note - 多彩卡片笔记|Card.Note - 多彩卡片笔记|Card.Note - 多彩卡片笔记|
|68|460661291|安全笔记+ Pro|Safety Note+ Pro|Safety Note+ Pro|Safety Note+ Pro|Safety Note+ Pro|Safety Note+ Pro|
|69|1527841661|沙盒星球|沙盒星球|沙盒星球|沙盒星球|Sandbox Planet|Sandbox Planet|
|70|1159266744|双子 Gemini|雙子 Gemini|雙子 Gemini|雙子 Gemini|❌|❌|
|71|1453808408|恶果之地|Juicy Realm|Juicy Realm|Juicy Realm|Juicy Realm|Juicy Realm|
|72|1458460469|人类跌落梦境|❌|❌|❌|❌|❌|
|73|1481100296|BreatheIn: Calm Breathing|BreatheIn: Calm Breathing|BreatheIn: Calm Breathing|BreatheIn: Calm Breathing|BreatheIn: Calm Breathing|BreatheIn: Calm Breathing|
|74|1309638846|Goodak 复古胶片相机 - 拍立得旅行摄影，拍照水印滤镜|Goodak 底片相機 - 復古即可拍，拍立得膠卷攝影|Goodak 底片相機 - 復古即可拍，拍立得膠卷攝影|Goodak 底片相機 - 復古即可拍，拍立得膠卷攝影|Vintage Camera - Goodak|Vintage Camera - Goodak|
|75|1618180398|照片同步-导出备份相册照片视频|照片同步-備份相冊照片視頻|照片同步-備份相冊照片視頻|照片同步-備份相冊照片視頻|PhotoSync-Backup your photos|PhotoSync-Backup your photos|
|76|1453318714|Vostok — 创建美丽快拍页面|Vostok — 创建美丽快拍页面|Vostok — 创建美丽快拍页面|Vostok — 创建美丽快拍页面|Vostok — Story Maker|Vostok — Story Maker|
|77|931188326|DayCost|DayCost Pro - Personal Finance|DayCost Pro - Personal Finance|DayCost Pro - Personal Finance|DayCost Pro - Personal Finance|DayCost Pro - Personal Finance|
|78|6449930220|手表浏览器  Wafari|手表浏览器  Wafari|手表浏览器  Wafari|手表浏览器  Wafari|Wafari - Watch Browser|Wafari - Watch Browser|
|79|818394449|时间轴-全球历史|时间轴-全球历史|时间轴-全球历史|时间轴-全球历史|Timeline - World history|Timeline - World history|
|80|1391571907|Fine修图|Fine修圖|Fine修圖|Fine修圖|Fine - Photo Editor|Fine - Photo Editor|
|81|6499125531|完蛋！我被美女包围了！|完蛋！我被美女包围了！|完蛋！我被美女包围了！|完蛋！我被美女包围了！|完蛋！我被美女包围了！|完蛋！我被美女包围了！|
|82|1485101937|Juice Watch|Juice Watch|Juice Watch|Juice Watch|Juice Watch|Juice Watch|
|83|703265535|FocusDots · 专注于当下|FocusDots · 專注於當下|FocusDots · 專注於當下|FocusDots · 專注於當下|FocusDots · Focus What Matters|FocusDots · Focus What Matters|
|84|6479307181|灵体侦测器|靈體偵測器|靈體偵測器|靈體偵測器|Ghostly Detector|Ghostly Detector|
|85|1636719674|锁屏启动 - 万能桌面小组件&灵动岛一键快捷指令手机捷径布局|鎖屏啟動 - 個人化桌面小工具＆靈動動畫，一鍵美化主螢幕佈局|鎖屏啟動 - 個人化桌面小工具＆靈動動畫，一鍵美化主螢幕佈局|鎖屏啟動 - 個人化桌面小工具＆靈動動畫，一鍵美化主螢幕佈局|Lock Launcher - Screen Widgets|Lock Launcher - Screen Widgets|
|86|1543163106|末剑二|❌|❌|❌|❌|❌|
|87|6443812780|我的水世界求生|❌|❌|❌|❌|❌|
|88|1344655035|蜡烛人|❌|❌|❌|❌|❌|
|89|6446614518|画中世界|❌|❌|❌|❌|❌|
|90|1159700098|去月球-To the Moon|去月球-To the Moon|去月球-To the Moon|去月球-To the Moon|To the Moon|To the Moon|
|91|1271620263|艾希 - ICEY|ICEY|ICEY|ICEY|ICEY|ICEY|
|92|1361473095|喵斯快跑|MuseDash|MuseDash|MuseDash|MuseDash|MuseDash|
|93|6476010032|拦截猫-垃圾短信电话拦截|拦截猫-垃圾短信电话拦截|拦截猫-垃圾短信电话拦截|拦截猫-垃圾短信电话拦截|拦截猫-垃圾短信电话拦截|拦截猫-垃圾短信电话拦截|
|94|510249014|水平仪 HD|水準管 HD|水準管 HD|水準管 HD|Level HD.|Level HD.|
|95|904237743|Things 3|Things 3|Things 3|Things 3|Things 3|Things 3|
|96|1622341132|iSleeper - 梦话鼾声记录与睡眠监测|iSleeper - 夢話鼾聲記錄與睡眠監測|iSleeper - 夢話鼾聲記錄與睡眠監測|iSleeper - 夢話鼾聲記錄與睡眠監測|iSleeper: Sleep Tracker|iSleeper: Sleep Tracker|
|97|900833042|Fliqlo|Fliqlo|Fliqlo|Fliqlo|Fliqlo|Fliqlo|
|98|1467880680|LEDot|LEDot|LEDot|LEDot|LEDot|LEDot - Realistic Portable LED|
|99|1455055663|皮皮虾专业版|❌|❌|❌|❌|❌|
|100|1595901138|NES 模拟器 - 吞食天地|Handheld Game - NES Emulator|Handheld Game - NES Emulator|Handheld Game - NES Emulator|Handheld Game - NES Emulator|Handheld Game - NES Emulator|
|101|1163515895|鲨鱼记账Pro-3秒钟快速记账|鲨鱼记账Pro-3秒钟快速记账|鲨鱼记账Pro-3秒钟快速记账|鲨鱼记账Pro-3秒钟快速记账|鲨鱼记账本Pro-管家理财必备工具|鲨鱼记账本Pro-管家理财必备工具|
|102|754105884|NightCap相机|NightCap相機|NightCap相機|NightCap相機|NightCap Camera|NightCap Camera|
|103|1642364007|海拔指南针|海拔指南针|海拔指南针|海拔指南针|Altitude Compass|Altitude Compass|
|104|1522215205|拒之-骚扰电话批量拦截助手|拒之-骚扰电话批量拦截助手|拒之-骚扰电话批量拦截助手|拒之-骚扰电话批量拦截助手|拒之-骚扰电话批量拦截助手|拒之-骚扰电话批量拦截助手|
|105|1484181693|截图超人 - 微商专用的营销助手截图神器|截图超人 - 微商专用的营销助手截图神器|截图超人 - 微商专用的营销助手截图神器|截图超人 - 微商专用的营销助手截图神器|截图超人 - 微商专用的营销助手截图神器|截图超人 - 微商专用的营销助手截图神器|
|106|1117998129|2025人体解剖学图谱|Human Anatomy Atlas 2025|Human Anatomy Atlas 2025|Human Anatomy Atlas 2025|Human Anatomy Atlas 2025|Human Anatomy Atlas 2025|
|107|6444824570|ClashX - 服务监控面板|ClashX - 服务监控面板|ClashX - 服务监控面板|ClashX - 服务监控面板|ClashX - 服务监控面板|ClashX - 服务监控面板|
|108|469338840|飞常准PRO-全球航班查询机票酒店预订|飞常准PRO-全球航班查询机票酒店预订|飞常准PRO-全球航班查询机票酒店预订|飞常准PRO-全球航班查询机票酒店预订|飞常准PRO-全球航班查询机票酒店预订|飞常准PRO-全球航班查询机票酒店预订|
|109|1197275827|金十数据专业版-为交易而生|金十数据专业版-为交易而生|金十数据专业版-为交易而生|金十数据专业版-为交易而生|金十数据专业版-为交易而生|金十数据专业版-为交易而生|
|110|578665578|Threema。安全的通讯工具|《Threema》- 安全即時通訊工具|《Threema》- 安全即時通訊工具|《Threema》- 安全即時通訊工具|Threema. The Secure Messenger|Threema. The Secure Messenger|
|111|1547418803|Incredibox - 好玩的音乐盒|❌|❌|❌|❌|❌|
|112|1210251567|SleepTown 睡眠小镇|SleepTown 睡眠小鎮|SleepTown 睡眠小鎮|SleepTown 睡眠小鎮|SleepTown|SleepTown|
|113|1080235640|CNU - 顶尖视觉精选|CNU - 顶尖视觉精选|CNU - 顶尖视觉精选|CNU - 顶尖视觉精选|CNU - 顶尖视觉精选|CNU - 顶尖视觉精选|
|114|1658579911|小特钥匙 - 特斯拉蓝牙手表钥匙|小特钥匙 - 特斯拉蓝牙手表钥匙|小特钥匙 - 特斯拉蓝牙手表钥匙|小特钥匙 - 特斯拉蓝牙手表钥匙|XIAOTE - Tesla BLE Watch key|XIAOTE - Tesla BLE Watch key|
|115|1152396902|凤凰新闻(专业版)-头条新闻阅读平台|凤凰新闻(专业版)-头条新闻阅读平台|凤凰新闻(专业版)-头条新闻阅读平台|凤凰新闻(专业版)-头条新闻阅读平台|凤凰新闻(专业版)-头条新闻阅读平台|凤凰新闻(专业版)-头条新闻阅读平台|
|116|1633366918|Instant Lines|Instant Lines|Instant Lines|Instant Lines|Instant Lines|Instant Lines|
|117|6480159520|转录大师 - 录音转文字、实时离线转录|Whisper Pen - 語音轉文字|Whisper Pen - 語音轉文字|Whisper Pen - 語音轉文字|Whisper Pen - Speech to Text|Whisper Pen - Speech to Text|
|118|966489322|生辰 — 桌面时间小组件|生辰 — 桌面时间小组件|生辰 — 桌面时间小组件|生辰 — 桌面时间小组件|生辰 — 桌面时间小组件|生辰 — 桌面时间小组件|
|119|898876435|Planit巧摄专业版：风光摄影计划神器|Planit巧攝專業版：风光攝影計劃神器|Planit巧攝專業版：风光攝影計劃神器|Planit巧攝專業版：风光攝影計劃神器|Planit Pro: Photo Planner|Planit Pro: Photo Planner|
|120|1062745479|HeartWatch: 心脏和活动监测器|HeartWatch: 監測心率|HeartWatch: 監測心率|HeartWatch: 監測心率|HeartWatch: Heart Rate Tracker|HeartWatch: Heart Rate Tracker|
|121|6476963352|万能生成器|万能生成器|万能生成器|万能生成器|万能生成器|万能生成器|
|122|1459076631|隐形守护者|隐形守护者|隐形守护者|❌|隐形守护者|❌|
|123|1660014964|飞越13号房|❌|❌|❌|❌|❌|
|124|730712409|ProCam - 专业相机|ProCam - 專業相機|ProCam - 專業相機|ProCam - 專業相機|ProCam - Pro Camera|ProCam - Pro Camera|
|125|6451239549|全网短剧大全-热门短剧抢先看|全网短剧大全-热门短剧抢先看|全网短剧大全-热门短剧抢先看|全网短剧大全-热门短剧抢先看|全网短剧大全-热门短剧抢先看|全网短剧大全-热门短剧抢先看|
|126|1633865171|獬豸 · 民法典 - 法律/司法解释/指导案例|獬豸 · 民法典 - 法律/司法解释/指导案例|獬豸 · 民法典 - 法律/司法解释/指导案例|獬豸 · 民法典 - 法律/司法解释/指导案例|獬豸 · 民法典 - 法律/司法解释/指导案例|獬豸 · 民法典 - 法律/司法解释/指导案例|
|127|1492395549|爱美剧-人人美剧天堂社区|爱美剧-人人美剧天堂社区|爱美剧-人人美剧天堂社区|爱美剧-人人美剧天堂社区|爱美剧-人人美剧天堂社区|❌|
|128|1661419573|atvTools|atvTools|atvTools|atvTools|atvTools|atvTools|
|129|6479683928|AMood - 你的健康生活好伙伴|AMood - 你的健康生活好伙伴|AMood - 你的健康生活好伙伴|AMood - 你的健康生活好伙伴|AMood - 你的健康生活好伙伴|AMood - 你的健康生活好伙伴|
|130|6443798663|敲木鱼 - 打节拍敲音效解压神器|敲木魚|敲木魚|敲木魚|MuYu|MuYu|
|131|373454750|随手记Pro–个人家庭生意记账|隨手記Pro–個人家庭生意記帳|隨手記Pro–個人家庭生意記帳|隨手記Pro–個人家庭生意記帳|随手记Pro|随手记Pro–记账财务管理软件|
|132|916366645|Procreate Pocket|Procreate Pocket|Procreate Pocket|Procreate Pocket|Procreate Pocket|Procreate Pocket|
|133|1164801111|AutoSleep - 通过手表自动追踪睡眠|AutoSleep – 在手錶上追蹤睡眠|AutoSleep – 在手錶上追蹤睡眠|AutoSleep – 在手錶上追蹤睡眠|AutoSleep Track Sleep on Watch|AutoSleep Track Sleep on Watch|
|134|1625289361|空气投篮|AirBasketball - AuditoryAR|AirBasketball - AuditoryAR|AirBasketball - AuditoryAR|AirBasketball - AuditoryAR|AirBasketball - AuditoryAR|
|135|1261944766|Alook浏览器 - 8倍速|Alook瀏覽器 - 8倍速|Alook瀏覽器 - 8倍速|Alook瀏覽器 - 8倍速|Alook Browser - 8x Speed|Alook Browser - 8x Speed|
|136|866450515|Forest 专注森林 - 番茄钟学习计时器|Forest 專注森林 - 讀書專注番茄鐘|Forest 專注森林 - 讀書專注番茄鐘|Forest 專注森林 - 讀書專注番茄鐘|Forest: Focus for Productivity|Forest: Focus for Productivity|
|137|1600873673|炭炭背单词｜四六级考研等英语单词学习|炭炭背单词｜四六级考研等英语单词学习|炭炭背单词｜四六级考研等英语单词学习|❌|❌|❌|
|138|388624839|扫描全能王 - 官方出品1元畅用版，扫描PDF文件，文字识别|CamScanner+|CamScanner+|CamScanner+|CamScanner + | OCR Scanner|CamScanner + | PDF Scanner|
|139|768160271|航旅纵横PRO-官方机票、值机火车票接送机免税酒店|航旅纵横PRO-官方机票、值机火车票接送机免税酒店|航旅纵横PRO-官方机票、值机火车票接送机免税酒店|航旅纵横PRO-官方机票、值机火车票接送机免税酒店|航旅纵横PRO-官方机票、值机火车票接送机免税酒店|航旅纵横PRO-官方机票、值机火车票接送机免税酒店|
|140|1439723850|时间规划局 - 倒计时与提醒事项|Countdown! Reminders and Timer|Countdown! Reminders and Timer|Countdown! Reminders and Timer|Countdown! Reminders and Timer|Countdown! Reminders and Timer|
|141|6447023668|爱韩剧 - 韩剧TV大全|爱韩剧 - 韩剧TV大全|爱韩剧 - 韩剧TV大全|爱韩剧 - 韩剧TV大全|爱韩剧 - 韩剧TV大全|爱韩剧 - 韩剧TV大全|
|142|6468843723|❌|GTA III – Definitive|GTA III – Definitive|GTA III – Definitive|GTA III – Definitive|GTA III – Definitive|
|143|6468845173|❌|GTA: Vice City – Definitive|GTA: Vice City – Definitive|GTA: Vice City – Definitive|GTA: Vice City – Definitive|GTA: Vice City – Definitive|
|144|6468845068|❌|GTA: San Andreas – 最終版|GTA: San Andreas – 最終版|GTA: San Andreas – 最終版|GTA: San Andreas – Definitive|GTA: San Andreas – Definitive|
|145|1631331207|❌|Hitman: Blood Money — Reprisal|Hitman: Blood Money — Reprisal|Hitman: Blood Money — Reprisal|Hitman: Blood Money — Reprisal|Hitman: Blood Money — Reprisal|
|146|1598130789|❌|Company of Heroes Collection|Company of Heroes Collection|Company of Heroes Collection|Company of Heroes Collection|Company of Heroes Collection|
|147|1085114709|Parallels Desktop|Parallels Desktop|Parallels Desktop|Parallels Desktop|Parallels Desktop|Parallels Desktop|
|148|6450262949|Longshot - 截图 & OCR文字识别|Longshot - Screenshot & OCR|Longshot - Screenshot & OCR|Longshot - Screenshot & OCR|Longshot - Screenshot & OCR|Longshot - Screenshot & OCR|
|149|6451498949|❌|Stray|Stray|Stray|Stray|Stray|
|150|1630403500|APTV|APTV|APTV|APTV|APTV|APTV|
|151|1552536109|PasteNow - 剪贴板工具|PasteNow - 剪貼簿工具|PasteNow - 剪貼簿工具|PasteNow - 剪貼簿工具|PasteNow - Instant Clipboard|PasteNow - Instant Clipboard|
|152|1558391784|Filebar|Filebar|Filebar|Filebar|Filebar - media player|Filebar - media player|
|153|1548711022|Barbee - 清理您的菜单栏图标|Barbee - Hide Menu Bar Items|Barbee - Hide Menu Bar Items|Barbee - Hide Menu Bar Items|Barbee - Hide Menu Bar Items|Barbee - Hide Menu Bar Items|
|154|1575588022|MenubarX - 强大的菜单栏浏览器|MenubarX - 強大的選單列瀏覽器|MenubarX - 強大的選單列瀏覽器|MenubarX - 強大的選單列瀏覽器|MenubarX - Floating Browser|MenubarX - Floating Browser|
|155|1630034110|Bob - 翻译和 OCR 工具|Bob - 翻译和 OCR 工具|Bob - 翻译和 OCR 工具|Bob - 翻译和 OCR 工具|Bob - 翻译和 OCR 工具|Bob - 翻译和 OCR 工具|
|156|1009747025|zFuse - 影音播放器|zFuse - 影片播放器|zFuse - 影片播放器|zFuse - 影片播放器|zFuse - Video Player|zFuse - Video Player|
|157|1054505347|zFuse - 视频播放器|zFuse - 視頻播放器|zFuse - 視頻播放器|zFuse - 視頻播放器|zFuse - Media Player|zFuse - Media Player|
|158|1659622164|VidHub - 高清影片视频播放器，快速播放云盘网盘|VidHub -Video Library & Player|VidHub -Video Library & Player|VidHub -Video Library & Player|VidHub -Video Library & Player|VidHub -Video Library & Player|
|159|1136220934|Infuse|Infuse|Infuse|Infuse|Infuse|Infuse|
|160|1476649036|帕斯卡契约|Pascal's Wager|Pascal's Wager|Pascal's Wager|Pascal's Wager|Pascal's Wager|
|161|1635315427|暖雪|❌|❌|❌|❌|❌|
|162|1523446532|重生细胞|❌|❌|❌|❌|❌|
|163|1389752090|❌|Dead Cells|Dead Cells|Dead Cells|Dead Cells|Dead Cells|
|164|1640627334|❌|Resident Evil Village for Mac|Resident Evil Village for Mac|Resident Evil Village for Mac|Resident Evil Village for Mac|Resident Evil Village for Mac|
|165|6450980545|❌|Resident Evil Village|Resident Evil Village|Resident Evil Village|Resident Evil Village|Resident Evil Village|
|166|6462360082|❌|Resident Evil 4|Resident Evil 4|Resident Evil 4|Resident Evil 4|Resident Evil 4|
|167|1620883955|❌|Little Nightmares|Little Nightmares|Little Nightmares|Little Nightmares|Little Nightmares|
|168|1606703078|❌|槍火重生|槍火重生|槍火重生|Gunfire Reborn|❌|
|169|1373575045|❌|The Gardens Between|The Gardens Between|The Gardens Between|The Gardens Between|The Gardens Between|
|170|1371965583|❌|The Gardens Between|The Gardens Between|The Gardens Between|The Gardens Between|The Gardens Between|
|171|6450877530|花园之间|❌|❌|❌|❌|❌|
|172|1601446687|❌|Streets of Rage 4|Streets of Rage 4|Streets of Rage 4|Streets of Rage 4|Streets of Rage 4|
|173|1587860402|❌|籠中窺夢|籠中窺夢|籠中窺夢|Moncage|Moncage|
|174|1584313012|笼中窥梦|❌|❌|❌|❌|❌|
|175|1465779286|❌|GRIS|GRIS|GRIS|GRIS|GRIS|
|176|1445379072|❌|GRIS|GRIS|GRIS|GRIS|GRIS|
|177|1521190840|格莉斯的旅程|❌|❌|❌|❌|❌|
|178|728293409|❌|紀念碑谷|紀念碑谷|紀念碑谷|Monument Valley|Monument Valley|
|179|1582832845|纪念碑谷|❌|❌|❌|❌|❌|
|180|1644917705|无处遁形：全网公敌|無處遁形：全網公敵|無處遁形：全網公敵|無處遁形：全網公敵|Cyber Manhunt|Cyber Manhunt|
|181|1369179088|❌|Grimvalor|Grimvalor|Grimvalor|Grimvalor|Grimvalor|
|182|1669723530|原界之罪|❌|❌|❌|❌|❌|
|183|481629890|❌|LIMBO by Playdead|LIMBO by Playdead|LIMBO by Playdead|LIMBO by Playdead|LIMBO by Playdead|
|184|656951157|❌|Playdead's LIMBO|Playdead's LIMBO|Playdead's LIMBO|Playdead's LIMBO|Playdead's LIMBO|
|185|886561127|❌|INSIDE by Playdead|INSIDE by Playdead|INSIDE by Playdead|INSIDE by Playdead|INSIDE by Playdead|
|186|1201642309|❌|Playdead's INSIDE|Playdead's INSIDE|Playdead's INSIDE|Playdead's INSIDE|Playdead's INSIDE|
|187|1529448980|❌|Reeder Classic.|Reeder Classic.|Reeder Classic.|Reeder Classic.|Reeder Classic.|
|188|1529445840|❌|Reeder Classic|Reeder Classic|Reeder Classic|Reeder Classic|Reeder Classic|
|189|1596063349|❌|Stash|Stash|Stash|Stash - Rule Based Proxy|Stash - Rule Based Proxy|
|190|6444029612|❌|Loon Lite|Loon Lite|Loon Lite|Loon Lite|Loon Lite|
|191|1373567447|❌|Loon|Loon|Loon|Loon|Loon|
|192|1442620678|❌|Surge 5|Surge 5|Surge 5|Surge 5|Surge 5|
|193|1443988620|❌|Quantumult X|Quantumult X|Quantumult X|Quantumult X|Quantumult X|
|194|932747118|❌|Shadowrocket|Shadowrocket|Shadowrocket|Shadowrocket|Shadowrocket|
|195|1642682818|熊猫吃短信2 - 垃圾短信拦截|熊猫吃短信2 - 垃圾短信拦截|熊猫吃短信2 - 垃圾短信拦截|熊猫吃短信2 - 垃圾短信拦截|熊猫吃短信2 - 垃圾短信拦截|熊猫吃短信2 - 垃圾短信拦截|
|196|1319191852|熊猫吃短信 - 垃圾短信过滤|熊猫吃短信 - 垃圾短信过滤|熊猫吃短信 - 垃圾短信过滤|熊猫吃短信 - 垃圾短信过滤|熊猫吃短信 - 垃圾短信过滤|熊猫吃短信 - 垃圾短信过滤|
|197|1067198688|彩云天气Pro|彩云天气Pro|彩云天气Pro|彩云天气Pro|彩云天气Pro|彩云天气Pro|
|198|955297617|CodeRunner 4|CodeRunner 4|CodeRunner 4|CodeRunner 4|CodeRunner 4|CodeRunner 4|

# Operating Mechanism and Process
The entire mechanism relies on scheduled tasks provided by  `GitHub Actions` , executed every  `60 minutes` . The overall process is as follows:
1. Get the latest price information for apps
   1. Get app details and the price of  `App`  through  [iTunes Search API](https://developer.apple.com/library/archive/documentation/AudioVideo/Conceptual/iTuneSearchAPI/Searching.html#//apple_ref/doc/uid/TP40017632-CH5-SW1) 
   2. Based on the app details link obtained in the previous step, parse the link to get the price of  `In-App Purchases` 
2. Read stored price information
3. Calculate discount information
4. Store the latest price information
5. Update  `RSS`  files
6. Push notification to  `Telegram` 
7. Push notification to  `DingTalk` 
8. Update  `README.md` 
9. Submit  `Git`  update

After the above process, if there is discount information, friends who subscribed to  `RSS Source`  and  `Telegram Channel`  will receive a push notification
# How to Contribute

## 1. Add  `Country or Region`  or  `App` 
A basic understanding of  `TypeScript`  is required. Here are the general steps. If you find it difficult, you can open an  `Issue` 
* Add  `Country or Region` 
   1. Get the  `Code`  of  `Country or Region` 
      1. Open the  `App Store`  app on your Apple device
      2. Open the details of any app in  `App Store` 
      3. Click  `Share Button` 
      4. Click  `Copy Link` 
      5. Paste the copied  `Link`  to any input field, such as Notepad
         * You will get a similar link address: https://apps.apple.com/us/app/pages/id409201541?mt=12&l=en-US
         * Its rules are: Protocol://apps.apple.com/Country or Region's Code/app/App Name/idApp ID?x1=x1&x2=x2
         * For example, the  `Code`  obtained from this  https://apps.apple.com/us/app/pages/id409201541?mt=12&l=en-US  link is  `us` 
   2. Modify  `global.d.ts` 
      * If the code you get is  `xxx `
      * Type before modification:  `type Region = 'cn' | 'hk' | 'mo' | 'tw' | 'us'` 
      * Type after modified:  `type Region = 'cn' | 'hk' | 'mo' | 'tw' | 'us' | 'xxx'` 
   3. Modify  `appinfo.config.ts` 
      1. Add  `regions`  Variable Declaration
      2. Add  `getRegionNameMap`  Variable Declaration
      3. Add  `regionInAppPurchasesTextMap`  Variable Declaration
      4. Add  `regionLanguageCodeMap`  Variable Declaration
      5. Add  `regionTimezoneMap`  Variable Declaration
* Add  `App` 
   1. Get the  `ID`  of  `App` 
      1. Open the  `App Store`  app on your Apple device
      2. Open the details of the app you want to add in  `App Store` 
      3. Click  `Share Button` 
      4. Click  `Copy Link` 
      5. Paste the copied  `Link`  to any input field, such as Notepad
         * You will get a similar link address: https://apps.apple.com/us/app/pages/id409201541?mt=12&l=en-US
         * Its rules are: Protocol://apps.apple.com/Country or Region's Code/app/App Name/idApp ID?x1=x1&x2=x2
         * For example, the  `ID`  obtained from this  https://apps.apple.com/us/app/pages/id409201541?mt=12&l=en-US  link is  `409201541` 
   2. Modify  `appinfo.config.ts` 
      1. Add  `appConfig`  Variable Declaration
* Finally, pull request your commit to the  `dev`  branch of this project


## 2. Other
If you don't want to participate in coding implementation, you can open an  `Issue`  if you have good ideas or find bugs<br />If you want to participate in coding implementation, due to the complexity of existing logic, rash changes may affect stored data. It's best to open an  `Issue`  first. Follow-up tasks can be assigned based on the affected modules or difficulty
# Star History
<a href="https://star-history.com/#eyelly-wu/appstore-discounts&Date">
  <picture>
    <source media="(prefers-color-scheme: dark)"srcset="https://api.star-history.com/svg?repos=eyelly-wu/appstore-discounts&type=Date&theme=dark"></source><source media="(prefers-color-scheme: light)"srcset="https://api.star-history.com/svg?repos=eyelly-wu/appstore-discounts&type=Date"></source><img alt="Star History Chart"src="https://api.star-history.com/svg?repos=eyelly-wu/appstore-discounts&type=Date" />
  </picture>
</a>

# License
[MIT](./LICENSE)

Copyright (c) 2024-present Eyelly Wu