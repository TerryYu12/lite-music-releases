<div align="center">

# 🌸 Lite Music - Kazami (风见)
### 次世代流体极光 · 120 FPS 全管线重构 · 拟物唱机与三层音素排版艺术

[![Release](https://img.shields.io/github/v/release/TerryYu12/lite-music-releases?color=f472b6&style=for-the-badge&logo=android)](https://github.com/TerryYu12/lite-music-releases/releases)
[![Platform](https://img.shields.io/badge/Platform-Android%20%7C%20Windows-60a5fa?style=for-the-badge&logo=windows)](https://github.com/TerryYu12/lite-music-releases/releases)
[![FPS](https://img.shields.io/badge/FrameRate-120%20FPS%20V--Sync-34d399?style=for-the-badge)](https://github.com/TerryYu12/lite-music-releases)
[![License](https://img.shields.io/badge/License-MIT-amber?style=for-the-badge)](LICENSE-AlgerMusicPlayer.txt)

<p align="center">
  <b>让音乐如同掠过发梢的风，吹拂有迹。</b><br>
  不只是第三方播放器，而是一台融汇了语言学排版、流体物理学与拟物美学的沉浸视听仪器。
</p>

[📥 立即下载最新安装包](#-安装包版本与下载选择) • [✨ 核心特性解析](#-七大核心美学与技术突破) • [📸 视觉全景画廊](#-视觉与动效全景画廊)

</div>

---

## 📸 视觉与动效全景画廊

### 1. 拟物黑胶唱机与 120 FPS 满帧流体平移
> **同心微槽唱纹物理匀速旋转，拉丝金属唱臂精准落针阻尼，三层夹心日文歌词行云流水。**

<div align="center">
  <img src="assets/kazami-vinyl-120fps.gif" width="100%" alt="拟物黑胶与120帧动态演示" />
</div>

* **视觉与动效解析**：
  * **Compositor 硬件轨道驱动**：脱离传统 CPU 重排重绘，`translate3d` 独立合成层直通屏幕 120Hz 垂直同步脉冲，在高刷屏上如丝般顺滑。
  * **拟物唱机物理学**：同心圆高光唱纹物理旋转，唱针起落与切歌回弹带有真实阻尼，完美还原发烧级实体唱片质感。
  * **同轴多音素排版**：三层夹心（顶部振假名 + 中间正文 + 底部逐字罗马音），汉字纯白高光，罗马音独立荧光绿，背景歌词自适应景深淡化。

---

### 2. 黑胶 / 现代方形大封面：一键双模态无缝形变
> **随心在“复古旋转黑胶”与“现代大画幅封面”间切换，复杂动态背景下依然清晰防撞色。**

<div align="center">
  <img src="assets/kazami-cover-switch.gif" width="100%" alt="封面双模切换与防撞色演示" />
</div>

* **视觉与动效解析**：
  * **无感双模形变**：点击封面右下角图标，可在「拟物旋转黑胶唱盘」与「大画幅现代方形专辑封面」间毫秒级平滑过渡。
  * **8 通道 HSL 像素级防撞色**：在红白飘带等高动态、高饱和度复杂壁纸下，通过独立 HSL 色彩通道将假名与主词设定为高反差对比色，文字轮廓清晰锐利，彻底根除“背景吃字”。

---

### 3. 中日多音素同轴对齐与聚光灯景深聚焦
> **中文正文与日文假名同轴共存，当前活跃行如舞台聚光灯夺目，上下文柔和沉入背景。**

<div align="center">
  <img src="assets/kazami-bilingual-sandwich.gif" width="100%" alt="中日多音素排版演示" />
</div>

* **视觉与动效解析**：
  * **Kazami Sandwich Flow 夹心流**：无论是日文原词还是中文本地化歌词，顶部振假名、中间重圆体、底部罗马音严丝合缝同轴对齐，配合等高透明占位符，滚动时坐标零垂直抖动。
  * **聚光灯聚焦模式（Spotlight Focus）**：当前播放行赋予饱满实体光泽（支持 105%~150% 自由放大倍率），非活跃行自适应虚化微缩（60%~95%），营造出剧场级视线焦点。

---

### 4. 巨幕平板横屏：Apple Music 黄金双栏与微质感抽屉
> **4:6 黄金比例巨幕分屏，边听歌边实时滑出调节面板，所见即所得。**

<div align="center">
  <img src="assets/kazami-tablet-player.png" width="95%" alt="平板双栏播放页与设置抽屉" />
</div>

* **特色设计解析**：
  * **左栏**：大画幅封面/黑胶 + 歌曲大标题 + 超长歌手名平滑跑马灯 + 超清母带音质胶囊 + 定制发光播放控制器。
  * **右侧深色抽屉**：直观提供【当前行放大倍率（105%~150%）】与【其他行缩小倍率（60%~95%）】连续阻尼滑块，随调随看，毫秒级实时响应。

---

### 5. 全聚合音乐大厅与四音源一键无缝漫游
> **网易云、酷我、酷狗、QQ 音乐无缝切换，每日推荐、智能电台、心动模式一触即发。**

<div align="center">
  <img src="assets/kazami-discover-home.png" width="49%" alt="发现首页推荐" />
  <img src="assets/kazami-playlist-view.png" width="49%" alt="歌单浏览与沉浸安全区" />
</div>

* **特色设计解析**：
  * **四源融合胶囊**：无需安装多个庞大应用，网易云 / 酷我 / 酷狗 / QQ音乐一键切换音源。
  * **全面屏 Edge-to-Edge 沉浸**：Android 原生状态栏与导航条穿透，时间与电量自然浮在壁纸上，搭配全透毛玻璃微质感卡片，视觉通透清爽。

---

## ⚡ 七大核心美学与技术突破

### 1. 120 FPS 全 GPU 合成器渲染管线
彻底抛弃导致掉帧发热的传统 `scrollTop` 机制，自研 GPU 硬件平移轨道（`translate3d` + `will-change: transform`）。配合 `requestAnimationFrame` 与微秒级音频时钟预测算法（`currentTimeSec`），直接向 DOM 写入 CSS 变量 `--kw-progress`，在 90Hz / 120Hz 高刷屏上呈现行云流水般的顺滑体验。

### 2. 独步全网的「三层夹心」多音素排版艺术
专为 ACG 与日系音乐发烧友打造：
* **顶部**：HTML5 标准 `<ruby>` 振假名，字号严格等比锁死在 0.44em，平摊无挤压；
* **中间**：内置 13.6MB 完整定制 `ResourceHanRoundedCN-Heavy`（源柔重圆体），字号最高支持 72px 大字号自适应防断裂换行；
* **底部**：逐字分词连贯罗马音；
* **防抖占位符**：无注音汉字自动填充等高透明占位符，消除换行时的上下抖动。

### 3. 双缓冲无缝循环动态视频壁纸引擎
突破性引入浏览器 IndexedDB 本地二进制流媒体库（`wallpaperDb.ts`），支持导入 1080P/4K 高帧率视频壁纸：
* **双槽位乒乓缓冲**：后台槽位预解码第 0 帧待命，前台播完微秒级交接，根除原生 seek 导致的 300ms 停顿黑屏；
* **智能色差分析（detectSeam）**：32×18 矩阵首尾帧比对，瞬切（Cut）与缓动淡入（Fade）自适应决策；
* **1/D² 降采样高斯模糊**：计算面积降至 1/16，节省 90%+ 显存纹理带宽，流畅不发烫。

### 4. 8 通道 HSL 像素级色彩调谐系统
* 主歌词、振假名、罗马音、中文翻译、歌曲标题、歌手名全部拆分为独立物理 CSS 色彩通道；
* 搭载原生硬件加速三滑条（色相/饱和度/明度）与 HEX 色号直填；
* 内置【幽香默认（随深浅主题自适应日光花田）】、【极简亮色】、【深邃暗夜】、【复杂背景防撞色】等 5 大预设。

### 5. 极致细节修复与工业级稳定性
* **彻底修复移动端歌词重影缺陷**：修复移动端单语种及关闭逐字时，罗马音与主歌词缺失分支互斥（`v-else`）导致的双重重复渲染 Bug。
* **平板手势与进度事件解耦**：接入 rAF 硬件轨与手势动量阻尼，解耦进度条拖拽状态（`progressDragTime`），杜绝触摸跳帧。
* **状态即时存盘**：切换后台瞬间即时写入持久化进度，彻底消除切后台丢失进度的顽疾。

---

## 📦 安装包版本与下载选择

同一个 Release 页面下，我们同时提供两款不同取向的 Android 移动端安装包：

| 安装包名称 | 文件体积 | 核心定位与适用人群 | 下载直链 |
| :--- | :--- | :--- | :--- |
| 📱 **LiteMusic-5.14.0.apk** | **7.1 MB** | **【标准基础版】**：极致轻量纯净，保留原生字库与经典基础听歌体验。 | [📥 立即下载](https://github.com/TerryYu12/lite-music-releases/releases/download/v5.14.0/LiteMusic-5.14.0.apk) |
| 🌸 **LiteMusic-Kazami-5.14.0.apk** | **14.5 MB** | **【风见臻享版】**：内置完整源柔重圆体，独占 120 FPS 全 GPU 硬件轨、拟物黑胶唱臂双模、Apple Music 4:6 巨幕双栏、三层夹心假名排版、动态视频壁纸引擎与 8 通道 HSL 调色（已修复歌词重影 Bug）。 | [📥 立即下载](https://github.com/TerryYu12/lite-music-releases/releases/download/v5.14.0/LiteMusic-Kazami-5.14.0.apk) |
| 💻 **LiteMusic-Setup-5.14.0.exe** | **108 MB** | **【Windows 电脑桌面版】**：全功能桌面客户端，支持灵动岛声屿悬浮窗、桌面歌词与全局快捷键。 | [📥 立即下载](https://github.com/TerryYu12/lite-music-releases/releases/download/v5.14.0/LiteMusic-Setup-5.14.0.exe) |

---
<div align="center">
  <b>Lite Music · Kazami Edition</b><br>
  Crafted with passion for Music, Art & Code.
</div>
