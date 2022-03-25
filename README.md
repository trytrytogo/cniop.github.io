# DIYP接口：

加速接口地址（推荐） ：

http://gg.gg/fastdiy

https://cdn.jsdelivr.net/gh/cniop/cniop.github.io@main/diy

备用接口：

http://gg.gg/ggdiy

# EGP节目清单
### DIYP EGP接口1（推荐）：

http://gg.gg/diypegp  （好记）

http://gg.gg/112114  （输入较方便）

https://epg.112114.xyz/

运行状态查询

https://epg.112114.xyz/status

自定义名字,检测到恶意提交永久封锁ip

https://epg.112114.xyz/alias

### DIYP EGP接口2：

http://gg.gg/113112

http://epg.51zmt.top:8000/api/diyp/ 

### DIYP EGP接口3：

https://epg.sec.st/epg.php

### DIYP EGP接口4：
https://epg.hicloud.co/epg.php

# 猫影视TV





---
**更新2.1.0_正式版**

采集站playUrl增强列表页筛选增加左方向键弹出解决SurfaceView渲染黑屏卡屏问题，增加S+渲染

手机端增加沉浸式适配

增加聚搜模式

增加type：4站点类型优化精简lJK播放器内核库更多修改和修复，请更新后自行体验


更新2.0.9正式版

增加WebDav协议配置地址支持

优化配置历史记录的操作

影片详情页增加剧集倒序按钮

IJK内核优化，增加M2音频格式支持

直播增加频道播放器设置保存

直播配置可单独重定向到独立地址，示例参考[https://wds.ecsxs.com/212757.json](https://wds.ecsxs.com/212757.json)

自定义爬虫增加应用内地址代理支持

自定义爬虫增加外挂字幕支持

### 直播配置重定向代理配制方法

```json

"lives": [
    {
      "group": "redirect",
      "channels": [
        {
          "name": "redirect",
          "urls": [
            "proxy://do=live&type=txt&ext=aHR0cHM6Ly9mZW54aWFuZ21pLmNvZGluZy5uZXQvcC96Yi9kL256eS9naXQvcmF3L21hc3Rlci9tYW9saXZlLnR4dA=="
          ]
        }
      ]
    }
  ]
```


软件下载2.0.9正式版本

https://sharerw.lanzoux.com/b0afu5apg

官方维护的源供参考:

2022/3/23更新接口

https://c1n.cn/2

自维护接口地址:

http://bit.do/gcat

国内配置接口 👉 https://maoys.c1n.cn 👈

海外配置接口 👉 http://bit.do/maoys 👈


# Cn.m3u

引用地址：
http://gg.gg/123365

================================================

文件格式及属性说明如下：

#EXTM3U x-tvg-url="定义节目清单xml网址,多个网址之间使用逗号分隔"

#EXTINF:-1 tvg-id="cctv1与目清单相匹配" tvg-country="国家" tvg-language="语言" tvg-logo="台标url" group-title="分组名",CCTV-1综合

http://223.110.243.159/ott.js.chinamobile.com/PLTV/3/224/3221227725/index.m3u8

注意：可以在文件头一次性配制多个节目清单源，也可以为每个频道单独配制节目源地址。


