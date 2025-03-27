# 🗣️ 文字轉語音網頁（繁體中文）

這是一個使用瀏覽器內建語音 API 製作的語音播放網頁，支援繁體中文語音播放與跑馬燈動畫，可透過網址參數控制文字、語音與跑馬燈顯示時間。

👉 [立即體驗 GitHub Pages 網頁](https://dong1121.github.io/dlpsText2speech/speech.html)

---

## 📌 功能特色

- ✅ 支援繁體中文語音 (`zh-TW`)
- ✅ 可從網址自動載入播放文字
- ✅ 可從網址選擇語音（第幾個語音）
- ✅ 支援跑馬燈顯示，顯示時間可自訂
- ✅ 可模擬自動播放語音（若瀏覽器阻擋，提供按鈕提示）

---

## 🔧 使用方式

將網頁部署到 GitHub Pages，並使用以下參數控制：

| 參數 | 說明 | 範例 |
|------|------|------|
| `text` | 要朗讀的文字 | `text=歡迎來到語音網頁` |
| `voice` | 使用第幾個語音（從 1 開始） | `voice=1` |
| `time` | 跑馬燈顯示時間（單位：分鐘） | `time=3` |

### ✅ 範例網址：
https://dong1121.github.io/dlpsText2speech/speech.html?text=大家好&voice=1&time=3


---

## 🧑‍💻 本專案技術

- HTML / CSS / JavaScript（純前端）
- [SpeechSynthesis API](https://developer.mozilla.org/en-US/docs/Web/API/SpeechSynthesis)
- GitHub Pages 靜態網站部署

---

## 🛠️ 如何部署到 GitHub Pages

1. 將 `index.html` 上傳到你的 GitHub Repo
2. 到 GitHub → `Settings` → `Pages`
3. 選擇 `main` 分支與根目錄 `/`
4. 儲存後幾秒會看到網站網址

---

## ⚠️ 注意事項

- 語音播放若被瀏覽器阻擋，會顯示「🔊 點我播放語音」提示
- 語音清單依瀏覽器與作業系統不同而異
- 無需安裝、無需金鑰、完全免費

---

## 📄 授權 License

本專案授權採用 MIT License，可自由使用、修改、商業應用。

---

製作 by 帥東 from chatgpt 4o

