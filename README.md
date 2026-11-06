<div align="center">

# 🎵 Lite Music · 轻聆

### 网易云音乐极简第三方客户端 · 中日多层逐字歌词 · 电脑 / 手机 / 平板 / Web

[![Release](https://img.shields.io/github/v/release/TerryYu12/lite-music-releases?label=Lite%20Music&color=60a5fa&style=for-the-badge)](https://github.com/TerryYu12/lite-music-releases/releases/latest)
[![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Android%20%7C%20Web%2FPWA-34d399?style=for-the-badge)](https://github.com/TerryYu12/lite-music-releases/releases)
[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](LICENSE-AlgerMusicPlayer.txt)

<p>
  <b>让听歌重回纯净、轻快与沉浸。</b><br/>
  无广告、无社交动态捆绑，专注于高品质音乐播放与极致歌词阅读体验。<br/>
  原生覆盖 <b>Windows</b> 与 <b>Android</b>，支持 <b>iPad / Web PWA</b> 大屏体验。
</p>

[📥 下载与安装](#-下载与安装) · [✨ 核心特性](#-核心特性) · [📱 iPad / Web 版使用说明](#-ipad--web-版使用说明) · [📸 界面预览](#-界面预览) · [❓ 常见问题](#-常见问题)

</div>

---

## 📥 下载与安装

| 平台 | 适用设备 | 特性亮点 | 下载入口 |
| :--- | :--- | :--- | :--- |
| 💻 **Windows** | Windows 10 / 11 (x64) | 桌面歌词悬浮窗、声屿灵动控制、全局快捷键、Mini 迷你模式、无损音频输出 | [⬇️ 最新安装包 (.exe)](https://github.com/TerryYu12/lite-music-releases/releases/latest) |
| 📱 **Android** | 手机 / 安卓平板 (Android 7.0+) | 状态栏/导航栏全沉浸、后台长效播放保活、桌面悬浮歌词、锁屏媒体控件 | [⬇️ 最新安装包 (.apk)](https://github.com/TerryYu12/lite-music-releases/releases/latest) |
| 🍎 **iPad / Web** | iPad / 跨平台浏览器 (PWA) | 免安装，大屏双栏响应式排版、触屏深度优化、Safari 添加至主屏幕全屏运行 | [📖 启动与部署说明](#-ipad--web-版使用说明) |

> 💡 **国内加速提示**：若 GitHub Releases 附件下载缓慢，可复制下载链接，在链接前增加加速前缀（如 `https://ghproxy.cn/`）后重试。

---

## ✨ 核心特性

### 1. 🈁 极致歌词系统与日语三层逐字排版
- **三层逐字对齐**：上振假名（ふりがな）、中原文、下罗马音逐字映射；汉字注音精准对齐，和声、促音、长音智能兼容。
- **双语 / 三语歌词合并**：同一时间轴自动聚合「原文 + 翻译 + 罗马音」，支持动态卡拉 OK 逐字高亮。
- **深度手感调教**：聚焦模式放大当前唱句、其余行波浪式淡化；字号、行距（0.8~4.0）、描边粗细与颜色自由定制。
- **悬浮窗与沉浸阅读**：Windows / Android 专属桌面歌词悬浮窗；全屏沉浸模式下自动淡出冗余控件。

### 2. 💿 视觉与播放美学
- **黑胶与 3D 封面**：拟真旋转黑胶唱片与唱臂起落动画，或一键切换超大幅专辑封面。
- **自定义动态壁纸**：支持静态图片与 4K 高帧率视频壁纸，循环平滑过渡无缝衔接。
- **全透毛玻璃美学**：卡片、背景板、弹窗全局透明度与高斯模糊度均可独立微调。
- **大屏自适应**：横屏平板模式自动呈现左侧封面控制器、右侧大幅歌词的双栏现代交互。

### 3. 📂 本地与云端音乐管理
- **大歌单全量接续**：万首超大歌单后台自动翻页拉取，支持全量乱序随机与全局搜索。
- **本地音频自动刮削**：支持 MP3、FLAC、WAV、OGG、M4A、AAC 等全格式，本地歌曲自动匹配内嵌/同名 `.lrc` 与联网歌词。
- **状态记忆**：记住上次播放列表、单曲进度与声音设置，启动即接续。

---

## 📱 iPad / Web 版使用说明

针对 iPad 用户与不便安装原生客户端的场景，Lite Music 提供了开箱即用的 Web / PWA 同源部署方案：

### 1. 启动服务（局域网 / 个人服务器）
在电脑或 NAS 上拉取本项目后运行：
```bash
# 构建并启动同源服务（集成接口代理与静态托管）
pnpm run build:mobile
pnpm run serve:web
```
控制台会输出本地及局域网访问地址（如 `http://192.168.x.x:4173`）。

### 2. iPad Safari 添加至主屏幕
1. 用 iPad 上的 **Safari 浏览器** 打开上述局域网地址；
2. 点击 Safari 分享按钮，选择 **“添加到主屏幕”**；
3. 从桌面图标启动，即可享受**无地址栏、无底栏的纯净独立全屏体验**，自动适配 iPad 大屏双栏排版与触屏手势。

---

## 📸 界面预览

### 黑胶唱片与三层歌词
<div align="center">
  <img src="assets/kazami-vinyl-120fps.gif" width="100%" alt="黑胶唱片与三层歌词" />
</div>

### 黑胶 / 大封面切换
<div align="center">
  <img src="assets/kazami-cover-switch.gif" width="100%" alt="黑胶与大封面切换" />
</div>

### 中日双语/三层歌词排版
<div align="center">
  <img src="assets/kazami-bilingual-sandwich.gif" width="100%" alt="中日双语歌词" />
</div>

### 平板大屏横屏双栏
<div align="center">
  <img src="assets/kazami-tablet-player.png" width="95%" alt="平板横屏双栏播放页" />
</div>

### 发现页与歌单
<div align="center">
  <img src="assets/kazami-discover-home.png" width="49%" alt="发现页" />
  <img src="assets/kazami-playlist-view.png" width="49%" alt="歌单页" />
</div>

---

## ❓ 常见问题

<details>
<summary><b>1. Windows 安装时提示「Windows 已保护你的电脑（SmartScreen）」？</b></summary>
由于个人开源项目未购买微软昂贵商业代码签名证书，首次运行 Windows 会弹出安全提示。点击<b>「更多信息」→「仍要运行」</b>即可正常安装。
</details>

<details>
<summary><b>2. Android 端提示应用内更新失败或覆盖安装报错？</b></summary>
- 本项目标准签名自 5.16 起已更新加固，若之前安装过非官方签名包或极旧历史版本，需先卸载旧版再安装新版（网易云线上歌单不受影响）。<br/>
- 覆盖安装时请认准同一版本分支的安装包。
</details>

<details>
<summary><b>3. 历史「风见 Kazami」定制版去哪了？</b></summary>
「风见 Kazami」原为针对东方 Project 幽香主题制作的定制版。自 2026 年 11 月起，为保证主线维护质量与包体精简，风见的歌词多层排版、双栏大屏等核心体验已整合进标准版，后续更新统一发布 Lite Music 标准包（Windows 与 Android），定制包不再单独迭代。历史版本仍可在 Release 归档中找到。
</details>

---

## 📜 声明与致谢

- 本项目基于开源项目 [AlgerMusicPlayer](https://github.com/algerkong/AlgerMusicPlayer) 二次深度开发与重构，遵循 [MIT 许可证](LICENSE-AlgerMusicPlayer.txt)。
- 本项目仅供个人学习交流使用，与网易云音乐官方无任何隶属关系。音频版权归各唱片公司及原作者所有，请支持正版音乐。
- 感谢所有为 Lite Music 提供体验反馈与代码贡献的开发者及用户！
