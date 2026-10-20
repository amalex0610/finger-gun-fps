# 🔫 Cyber Finger-Gun AR (賽博指槍 AR)

> **零硬體外設！用手機鏡頭 + 雙手直接開玩的實景第一人稱射擊（FPS）爽 Game！**

[![GitHub Pages](https://img.shields.io/badge/Live%20Demo-Play%20Now-00f0ff?style=for-the-badge&logo=googlechrome)](https://amalex0610.github.io/finger-gun-fps/)
[![MediaPipe](https://img.shields.io/badge/AI%20Vision-MediaPipe%20Hands-ff007f?style=for-the-badge)](https://developers.google.com/mediapipe)
[![Web Audio](https://img.shields.io/badge/Audio-Synthesized%20Web%20Audio-ffdd00?style=for-the-badge)](#)

---

## 🎮 玩法手勢 (How to Play)

不需要任何玩具槍或外接手把，只要將一隻手伸入相機畫面中：

| 動作 | 手勢說明 | 效果 |
| :---: | :--- | :--- |
| **👉 瞄準** | **伸直食指**，其餘手指握拳（比出手槍姿勢） | 槍口自動跟隨指尖，前方生成賽博科幻準星 |
| **💥 開火** | **大拇指往下扣一下**（Pull the trigger） | 瞬間發射高能雷射、螢幕震動、槍口火光、碎裂無人機 |
| **📱 觸控** | 點擊螢幕任意位置 | 備用強制開火模式（除錯或單手點擊時使用） |

---

## ⚡ 核心特色 (Features)

1. **AI 視覺即時追蹤**：採用 Google MediaPipe Hands 骨骼辨識，60 FPS 極速判定手勢與食指射線。
2. **純代碼合成戰鬥音效**：內建 **Web Audio API** 即時物理合成器，包含低音雷射手槍聲、爆頭清脆叮聲與無人機擊碎爆炸音，**零外部音效依賴，秒開秒玩**。
3. **滿屏爽感反饋**：
   - 槍口動態閃光與螢幕後座力晃動（Screen Shake）。
   - 手機硬體微震動回饋（Haptic Feedback）。
   - 無人機目標碎裂成 30+ 顆物理粒子、浮動傷害數字（Damage Popups）與連殺 Combo 計分。
4. **前後鏡頭一鍵切換**：預設後置鏡頭（把客廳/辦公室當成戰場），也可切換自拍前置鏡頭。

---

## 🛠️ 技術棧 (Tech Stack)

* **AI 骨骼追蹤**：Google MediaPipe Hands
* **圖形渲染**：HTML5 Canvas 2D + 粒子物理引擎
* **音效系統**：Web Audio API (Procedural Sound Synthesis)
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
*(注意：在手機上使用相機功能需透過 HTTPS 協議，建議使用 GitHub Pages 發布)*

---

*Made with passion by [Alex (amalex0610)](https://github.com/amalex0610)*
