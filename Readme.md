# SuperACL 
#### 简洁易用的ACL进出网规则 
```

 ____                              _     ____  _
/ ___|  _   _  _ __    ___  _ __  / \   / ___|| |
\___ \ | | | || '_ \  / _ \| '__|/ _ \ | |    | |
 ___) || |_| || |_) ||  __/| |  / ___ \| |___ | |___
|____/  \__,_|| .__/  \___||_| /_/   \_\\____||_____|
              |_|

```
[![HomePAGE](https://img.shields.io/badge/Home-Page-blue.svg?style=flat)](https://powerfulweb.nciyuan.net)
[![MIT License](https://img.shields.io/badge/License-MIT-green.svg?style=flat)](https://github.com/Windelight/SuperACL/blob/master/License.md)
[![VersionName](https://img.shields.io/badge/Version-108Alpha1Pre1-orange.svg?style=flat)](https://github.com/Windelight/SuperACL/tree/master)
[![ChangeLOG](https://img.shields.io/badge/Change-Log-red.svg?style=flat)](https://github.com/Windelight/SuperACL/blob/master/ChangeLog.md)

**Tip**:[点击/长按此处立刻复制链接](https://raw.githubusercontent.com/Windelight/SuperACL/master/inchina.acl)并粘贴到软件中即可快速开始使用！  

_本项目是 `BitBucket` 和 `Coding` 以及 `GitLab` 上面的备份项目的同步源_

## 简介
 本规则有以下两种模式
 * 大陆出国模式(仅代理中国大陆有访问问题的网站)
 * 海外回国模式(代理范围为中国大陆地区的网站)  

本规则可以帮助您  
- [x] 代理在中国大陆被封锁的网站 (eg. Google、 Facebook、 Twitter)
- [x] 代理在中国大陆访问速度较慢或不稳定的网站 (eg. GitHub、 Amazon AWS)
- [x] 代理在中国大陆有访问限制的网站 (eg. Steam Powered、 Xbox Live)
- [x] 代理其它在中国大陆不能完整访问的网站 (eg. Bing、 Wikipedia、 WordPress)
- [ ] 回国模式则反之亦然，欢迎海外华人使用哦 (*σ´∀`)σ
> 但同时也请您注意：  
> 1. 我们不会主动去屏蔽广告和国内域名，所以本规则不具有主动屏蔽广告的功能，也不会代理任何 `.cn` 域名哦
> 2. 我们的项目不基于 `GFWList` 以及 `ChinaList`，并且更加严格，所以我们不会添加法轮功等实在是看不下去的网站
> 3. 我们会尽可能多地完善这份列表，但是仍然可能会存在失效、过期和疏漏，欢迎您通过PR或者Issue来反馈

## 使用
适用的软件平台 (已测试):
- [x] Shadowsocks for Android
- [x] Shadowsocks-RSS for Android  
- [ ] ~~Shadowsocks-Qt~~
- [ ] ~~Shadowsocks-Libev~~

文件内容:
- `inchina.acl` <u>适用于出国代理</u>  
  - 实时更新地址: https://raw.githubusercontent.com/Windelight/SuperACL/master/inchina.acl
- `inforeign.acl` <u>适用于回国代理</u>
  - 实时更新地址: https://raw.githubusercontent.com/Windelight/SuperACL/master/inforeign.acl  

使用方法 (via [Shadowsocks for Android](https://github.com/shadowsocks/shadowsocks-android)):
 1. 打开您的桌面/启动器上的 `影梭` 
 2. 从屏幕左侧边缘向右滑动，在侧栏上点击 `自定义规则` 
 3. 再点击位于右上角的添加规则图标并在下拉栏中点击手动设置
 4. 在对话框中点击下拉栏并选择 `在线规则文件URL` 
 5. 粘贴本规则的文件地址并点按确定
 6. 回到 `配置文件` 主界面点击笔按钮修改需要的配置项目
 7. 将配置中的 `功能设置` -> `路由` 更改为 `自定义规则` 并点击右上角 √ 保存  
 
支持列表 (Ver. 1.08-Alpha1-Pre1): 位于 [SupportList.md](https://github.com/Windelight/SuperACL/blob/master/SupportList.md) 文件中  
不会操作或使用吗？建议您先移步本项目 [Wiki](https://github.com/Windelight/SuperACL/wiki) 来获得更多帮助哦!  
遇到了使用问题？欢迎您移步到本项目 [Issue](https://github.com/Windelight/SuperACL/issues) 想我们提交反馈哦! 


## 版权
* Copyright &copy; 2016-2019 NciYuan! Team. Common Rights Statement.
* Copyright &copy; 2019 Guan 'Windelight' MingZheng. All Rights Reserved.  

*** MIT License ***
