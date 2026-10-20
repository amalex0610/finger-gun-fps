# 🔫 Cyber Finger-Gun AR 3.0 (賽博指槍 AR · 肉鴿晶片版)

> **零硬體外設！用手機鏡頭 + 雙手直接開玩的實景第一人稱射擊（FPS）肉鴿爽 Game！**

[![GitHub Pages](https://img.shields.io/badge/Live%20Demo-Play%20Now-00f0ff?style=for-the-badge&logo=googlechrome)](https://amalex0610.github.io/finger-gun-fps/)
[![MediaPipe](https://img.shields.io/badge/AI%20Vision-MediaPipe%20Hands-ff007f?style=for-the-badge)](https://developers.google.com/mediapipe)
[![Web Audio](https://img.shields.io/badge/Audio-Procedural%20BGM%20%26%20Tesla%20SFX-ffdd00?style=for-the-badge)](#)

---

## 🎮 玩法手勢 (How to Play)

不需要任何玩具槍或外接手把，只要將一隻手伸入相機畫面中：

| 武器模式 | 手勢說明 | 效果 |
| :---: | :--- | :--- |
| **👉 單指手槍 (Pistol)** | **伸直食指**，其餘手指握拳 | 槍口跟隨指尖，單發精準高爆雷射，180ms 極速射擊 |
| **💥 雙指霰彈 (Shotgun)** | **伸直食指＋中指** 併攏 | 準星自動擴大，扣動扳機瞬間發射 **5 顆扇形擴散彈丸**！ |
| **⚡ 扣扳機開火 (Fire)** | **大拇指往下扣一下**（Pull Trigger） | 動態速度偵測，瞬間發射、螢幕後座力震動、槍口閃光 |
| **🎁 射擊拾取晶片** | 用手槍直接瞄準浮動晶片開火射擊 | 晶片瞬間吸入核心，啟動特異肉鴿技能！ |

---

## ⚡ 3.0 全新升級亮點 (What's New in v3.0)

1. **🎁 肉鴿戰鬥晶片系統（Shoot-to-Equip）**：
   * 每累積擊殺 7 隻敵人，天空會空投懸浮的全息肉鴿晶片箱！
   * **不需要放下手去摸螢幕**，直接拿手槍瞄準想選的晶片「砰！」打爆，直接吸附啟用！
   * 包含 4 種特異晶片：
     * ⚡ **【連環高壓電弧 (Tesla Chain)】**：擊殺目標時，一道藍紫色高壓電弧彈射至周圍 2 隻敵人引發連鎖擊破！
     * 💥 **【高爆核子穿透 (Cluster Bomb)】**：子彈貫穿直線敵人，並引發範圍 AOE 爆炸！
     * ⏱️ **【駭客子彈時間 (Chrono Shift)】**：時間流速減慢 72% 持續 6 秒，進入慢動作世界挨個點爆！
     * 🛡️ **【緊急奈米護甲 (Nano Shield)】**：回復 40 HP，並獲得一層可抵擋一次自爆撞擊的防護力場！
2. **👀 極簡全通透懸浮 HUD（視野釋放 100%）**：
   * 移除頂部大塊黑色背景條，改為極細懸浮微型條，完全不擋自爆怪飛出路徑。
   * 武器狀態直接整合到準星下方，按鈕改為右上角微型圖示。
3. **🎵 Web Audio 賽博 BGM & 閃電滋滋音效**：
   * 內建 124 BPM Synthwave 律動音樂，配合子彈時間具備動態時空低頻調變。

---

## 🛠️ 技術棧 (Tech Stack)

* **AI 骨骼追蹤**：Google MediaPipe Hands (Lite 60FPS 模式)
* **圖形渲染**：HTML5 Canvas 2D + 粒子系統 + 鋸齒閃電物理
* **音訊引擎**：Web Audio API (Procedural Cyber BGM & Tesla Synthesis)
* **硬體調用**：WebRTC `getUserMedia` + `navigator.vibrate`
* **部署環境**：GitHub Pages (HTTPS)

---

*Made with passion by [Alex (amalex0610)](https://github.com/amalex0610)*
