# ![](https://qingchenyou-1301914189.cos.ap-beijing.myqcloud.com/this_32.png)NeuroSangSpider

> [!NOTE]
**本项目已不限期暂停功能性更新及ISSUE**

![image-20260109162010403](https://qingchenyou-1301914189.cos.ap-beijing.myqcloud.com/image-20260109162010403.png)

> [!important] 
由 Soul 开发，众多社群成员共同打造的非官方牛曲在线播放网站 Neuro & Evil Karaoke Web Player 已正式上线，网站承担v1至今的歌回、已授权封面二创、直播切片、语音的存档，兼备社区像素画布功能。具备功能完备的播放界面，支持同步歌词、自建及共享歌单。未来还将更新其他功能。网站可直连。相关非官方开源项目支持将在后续上线（也许吧）。
https://www.neurokaraoke.com
https://www.evilkaraoke.com

## 项目简介

这是一个基于 `Python 3.13` 开发的歌回软件

运行原理是从 Bilibili（哔哩哔哩）爬取 **Neuro/Evil** 的歌曲的视频内容。

~~(当然也可以通过自定义 **UP 主列表** 和 **关键词**甚至是**BV号**，灵活调整爬取目标)~~

~~你甚至能通过设置直接**关掉过滤器** “啊？”~~

**NeuroSangSpider 不止于 Neuro/Evil**

---

## 特性概述
### ✅ 已实现功能
- 获取歌回列表，支持按设置的 UP 主和关键词筛选目标视频
- 支持搜索歌曲，下载指定歌回、本地播放歌曲
- 基础的歌曲推荐功能
- 调用bilibili搜索补全歌曲列表
- 升级 GUI 界面，提供可视化交互（设置面板等）
- 支持修改更多设置项

### 🚧 正在计划中
- 支持在线播放，无需下载歌曲
- 添加更多功能

---

## 安装步骤

选择对应的系统版本，下载后解压
打开`NeuroSongSpider.exe`既可

如果你想要更好的效果要点击“获取视频列表”!!!

---

## 构建步骤

因为最开始写成neuroSongSpider了，所以请勿使用neuroSangSpider作为项目文件夹名称

> [!important] 
> 
> **请注意，如果你要拉取仓库，请拉取master仓库！**
> 
> **如果你要提交代码，请PR到Other仓库！**
> 
> **请确保你的代码没有问题后再提交到master仓库！**

首先你需要将ffmpeg扔到ffmpeg文件夹，因为这个软件需要ffmpeg

路径为 `项目根目录/ffmpeg/bin/ffmpeg.exe`

```bash
# 克隆仓库
git clone https://github.com/qingchenyouforcc/neuroSangSpider

# 进入目录
cd neuroSangSpider

# 安装依赖
uv sync

# 安装 pre-commit 钩子
uv run pre-commit install

# 运行
uv run main.py
```

---

## 感谢名单

### 感谢宅笙绘制软件部分UI图标

- [宅笙Zhai_Sheng](https://space.bilibili.com/49541366)

### 感谢Klef授权软件图标

![](https://qingchenyou-1301914189.cos.ap-beijing.myqcloud.com/b179a2b1bd812119dbb31b9c6bd6d184.png)

### 感谢萝卜猫提供的启动动画授权

- [魔法少女_卡洛特](https://space.bilibili.com/2038218765)

### 感谢Stazer提供的加载动画授权

- [稳定器stz](https://space.bilibili.com/125198191)

### 感谢以下up主对Neuro/Evil歌回的贡献，没有你们就不会有这个项目的出现

- [\_环戊烷多氢菲\_](https://space.bilibili.com/351692111)
- [Neuro21烤肉组](https://space.bilibili.com/1880487363)
- [绅士羊OuO](https://space.bilibili.com/22535350)
- [NSC987](https://space.bilibili.com/3546612622166788)
- [西街Westreet](https://space.bilibili.com/5971855)
- [BulletFX](https://space.bilibili.com/483178955)
- [ASDFHGV](https://space.bilibili.com/690857494)
- [意念艾特感叹号](https://space.bilibili.com/390418501)

以及感谢所有切Neuro/Evil歌回和做二创的UP主们

还有对本项目做出贡献的所有开发者

![](https://qingchenyou-1301914189.cos.ap-beijing.myqcloud.com/681dcdd42da7fc5484c1dd3a9875b54a_324.png)

---
## 广告位
**如果你对neuro社区项目感兴趣的话**

**请加入STNC了解更多内容**

**STNC蜂群技术情报中心 125081756**

请加入文学社谢谢喵

**NeuroEcho文学社1063898428**

---

## Star 趋势

[![Star History Chart](https://api.star-history.com/svg?repos=qingchenyouforcc/neuroSangSpider&type=Date)](https://star-history.com/#qingchenyouforcc/neuroSangSpider&Date)
