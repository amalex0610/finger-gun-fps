# 🔫 Cyber Finger-Gun AR 2.0 (賽博指槍 AR)

> **零硬體外設！用手機鏡頭 + 雙手直接開玩的實景第一人稱射擊（FPS）爽 Game！**

[![GitHub Pages](https://img.shields.io/badge/Live%20Demo-Play%20Now-00f0ff?style=for-the-badge&logo=googlechrome)](https://amalex0610.github.io/finger-gun-fps/)
[![MediaPipe](https://img.shields.io/badge/AI%20Vision-MediaPipe%20Hands-ff007f?style=for-the-badge)](https://developers.google.com/mediapipe)
[![Web Audio](https://img.shields.io/badge/Audio-Synthesized%20BGM%20%26%20SFX-ffdd00?style=for-the-badge)](#)

---

## 🎮 玩法手勢 (How to Play)

不需要任何玩具槍或外接手把，只要將一隻手伸入相機畫面中：

| 武器模式 | 手勢說明 | 效果 |
| :---: | :--- | :--- |
| **👉 單指手槍 (Pistol)** | **伸直食指**，其餘手指握拳 | 槍口跟隨指尖，單發精準高爆雷射，180ms 極速射擊 |
| **💥 雙指霰彈 (Shotgun)** | **伸直食指＋中指** 併攏 | 準星自動擴大，扣動扳機瞬間發射 **5 顆扇形擴散彈丸**！ |
| **⚡ 扣扳機開火 (Fire)** | **大拇指往下扣一下**（Pull Trigger） | 動態速度偵測，瞬間發射、螢幕後座力震動、槍口閃光 |
| **📱 觸控備用** | 點擊螢幕任意位置 | 支援螢幕單點強制開火（除錯或單手點擊時使用） |

---

## ⚡ 2.0 全新升級亮點 (What's New in v2.0)

1. **🎵 程式化賽博電子 BGM (124 BPM Synthwave)**：
   * 內建 **Web Audio API 物理合成器**，合成 4/4 拍底鼓（Kick）、金屬踩鑔（Hi-hat）、合成器重低音 Bassline 與賽博琶音旋律。
   * **零外部音訊依賴，秒開秒響，永不 404**，右上角隨時可一鍵切換靜音。
2. **💥 雙武器手勢自動切換**：
   * 食指 👉：手槍模式（精準打擊）。
   * 雙指 ✌️：霰彈槍模式（雙管 5 連發扇形覆蓋，近身秒殺）。
3. **⚠️ 自爆衝鋒怪 (Kamikaze Drone) 與玩家生命值 (HP)**：
   * 新增帶有旋轉紅刺、自帶急促嗶嗶警報聲的自爆怪，會直線加速衝撞玩家鏡頭！
   * 玩家擁有 100 點 HP，被撞擊時觸發螢幕暗紅裂紋閃爍與手機強烈震動！
   * 支援 Game Over 結算與滿血一鍵重啟。
4. **⚡ 60 FPS 極速 Lite 手勢模型**：
   * 換裝輕量級 AI 手部模型，延遲大幅降低 70%，加上科幻霓虹骨骼微光顯示與平滑防抖準星。

---

## 🛠️ 技術棧 (Tech Stack)

* **AI 骨骼追蹤**：Google MediaPipe Hands (Lite 模式)
* **圖形渲染**：HTML5 Canvas 2D + 粒子物理引擎
* **音訊引擎**：Web Audio API (Procedural Cyber BGM & Dynamic Sound Synthesis)
* **硬體調用**：WebRTC `getUserMedia` + `navigator.vibrate`
* **部署環境**：GitHub Pages (HTTPS)

---

## 🚀 本地開發與測試 (Local Development)

```bash
# 啟動本地微型伺服器
python -m http.server 8000

# 透過瀏覽器訪問
http://localhost:8000
```
*(注意：在手機上使用相機功能需透過 HTTPS 協議，請透過 GitHub Pages 發布網址進行實測)*

---

*Made with passion by [Alex (amalex0610)](https://github.com/amalex0610)*
