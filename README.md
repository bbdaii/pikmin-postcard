# 皮克敏明信片編輯器（Pikmin Postcard Editor）

一個用於製作 **Pikmin Bloom** 明信片的非官方網頁小工具，可上傳照片、編輯明信片名稱與寄件位置，以及寄件人名稱，並可以一鍵下載圖片。

## 功能特色

- 上傳明信片主圖與寄件人頭像
- 自訂明信片名稱、寄件位置、寄件人名稱
- 一鍵隨機切換明信片底圖與郵票樣式
- 即時預覽明信片排版
- 透過 [html2canvas](https://html2canvas.hertzen.com/) 將明信片輸出並下載為圖片
- 使用 [GSAP](https://gsap.com/) 製作提示訊息的淡入淡出動畫

## 使用方式

本專案為單一 HTML 檔案（`PostcardEditor.html`），無需安裝任何套件即可在瀏覽器中執行。

由於下載功能會將本地圖片繪製到圖片上，瀏覽器的安全機制會阻擋直接開啟檔案時的下載（會出現錯誤訊息），因此建議透過本地伺服器開啟，例如：

```bash
# 任選一種方式
python3 -m http.server
# 或
npx serve
# 或
npx http-server
```

啟動後在瀏覽器開啟對應網址（如 `http://localhost:8000/PostcardEditor.html`）即可使用。

## 版權聲明與免責聲明

### 遊戲版權

本專案為**非官方粉絲作品**，與任天堂（Nintendo）或 Niantic, Inc. 無任何官方關聯、隸屬、贊助或背書關係，亦未獲其授權或認可。

- **Pikmin** 與 **Pikmin Bloom** 為任天堂（Nintendo）與 Niantic, Inc. 的註冊商標
- 頁面中所使用之「Pikmin」、「Pikmin Bloom」相關名稱、角色、圖像及商標，其著作權與商標權均屬 Nintendo / Niantic 所有
- 本專案不主張對任何遊戲內容擁有版權

### 合理使用聲明

本網站僅供**個人興趣與非商業用途**使用：

- 本工具為非營利性質，目的在於提供製作明信片的便利性
- 本站僅依據著作權法之「合理使用」原則，基於個人興趣、評論與資訊分享目的使用相關素材
- 若有侵權疑慮，請透過下方聯絡方式告知，將立即移除或調整內容

詳見頁面內的[版權免責聲明](https://www.pikminwiki.com/Pikipedia:General_disclaimer)。

### 本專案原創內容

本專案的**原創程式碼**採用 [MIT License](./LICENSE)，內容包含：

- 網站架構與程式碼
- 使用者介面設計與排版

### 免責聲明

- 本工具所提供的功能可能不完整或包含錯誤，我們努力維持其可用性但不提供任何保證
- 使用者需自行承擔使用本工具的風險
- 本專案開發者不對任何因使用本工具而產生的損失負責
- 若任天堂或 Niantic 要求移除任何內容，將立即配合處理

## 授權條款

本專案的原創程式碼採用 **MIT License**，詳見 [LICENSE](./LICENSE)。所有 Pikmin / Pikmin Bloom 相關素材版權歸任天堂所有，本專案基於合理使用原則使用這些素材。

## 聯繫方式

如有版權疑慮或建議，歡迎透過 Email 聯繫：[hellobbdai@gmail.com](mailto:hellobbdai@gmail.com)
