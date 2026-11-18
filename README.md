# DINO AI 學習 App 下載

數學遊樂園、新課綱數學、迪諾玩注音拼音的 Android 安裝檔。三個 App 可以同時安裝。

| App | 版本 | APK 下載 | 網頁版 |
|---|---|---|---|
| 數學遊樂園 | 1.1.0 | [下載 APK](https://github.com/ichanchiu/dino-math-android-releases/releases/download/android-2026-11-18/DINO-AI-Math-Park-1.1.0.apk) | [開啟網站](https://mathpark.dinoailearning.com/) |
| 新課綱數學 | 1.0.0 | [下載 APK](https://github.com/ichanchiu/dino-math-android-releases/releases/download/android-2026-11-18/DINO-AI-New-Curriculum-Maths-1.0.0.apk) | [開啟網站](https://newmath.dinoailearning.com/) |
| 迪諾玩注音拼音 | 1.0.0 | [下載 APK](https://github.com/ichanchiu/dino-math-android-releases/releases/download/android-2026-11-18/DINO-AI-Zhuyin-Pinyin-1.0.0.apk) | [開啟網站](https://zhuyinpinyin.dinoailearning.com/) |

[三個 APK 一起下載 ZIP](https://github.com/ichanchiu/dino-math-android-releases/releases/download/android-2026-11-18/DINO-AI-Learning-Apps-2026-11-18.zip) · [完整發布頁與檔案校驗](https://github.com/ichanchiu/dino-math-android-releases/releases/tag/android-2026-11-18)

注音與拼音包含在同一個 App，登入後從共同入口選擇。各套教材保留原有的中文／中英／英文模式，練習紀錄分開儲存並綁定同一會員帳號。

## 安裝與登入

1. 使用 Android 8.0 以上的手機或平板，下載對應的 APK。
2. 開啟 APK，依 Android 提示允許該檔案來源安裝。
3. 開啟 App，使用課程會員帳號登入。下載 APK 不會自動取得課程存取資格；如有帳號或課程權限問題，請洽原課程管理員。

這三個都是連線版 App，需要網路，沒有內附整套離線教材。App 的登入狀態與 Chrome 分開，三個 App 也各自登入。

原本兩個數學 App 的版本與簽章保持相同，已安裝者可繼續使用，不必先移除。先前發布頁與下載連結仍保留。

## 更新與學習紀錄

教材、遊戲和網站功能由正式網站提供。網站更新後，完整關閉 App 再開啟即可載入；原生 App 本身改版時，仍須安裝新版 APK。

學習與遊玩紀錄依各站功能綁定會員帳號。「待同步」表示尚未確認寫入雲端，應保持連線完成同步。清除 App 資料或移除 App 可能失去尚未同步的紀錄。

注音拼音首頁顯示最近 20 筆已儲存練習，區分開啟教材、書寫、答題、遊戲完成或中途離開、自評及本機音高練習。開啟紀錄及星星不等於客觀能力評量。

## 權限與錄音

數學遊樂園與新課綱數學只要求網路權限。注音拼音另宣告麥克風權限，僅在點選錄音練習時詢問；啟動或一般教材不要求麥克風。錄音在頁面本機處理與回放，不上傳聲音；雲端只存練習操作與自評等數值紀錄，沒有外部語音辨識。

## 版本與驗證

- 數學遊樂園：`com.dinoailearning.mathpark`，1.1.0，versionCode 2。
- 新課綱數學：`com.dinoailearning.newmath`，1.0.0，versionCode 1。
- 迪諾玩注音拼音：`com.dinoailearning.zhuyinpinyin`，1.0.0，versionCode 1。
- 已驗證正式 APK 簽章、16 KiB zip alignment、SHA-256，以及 Android 15 隔離模擬器的安裝與正式網站匿名登入入口。注音拼音也檢查直橫向與鍵盤操作。
- 實體裝置、Android 上真實會員完整遊玩、實際系統麥克風授權視窗及真人收音／聆聽品質尚未驗收。
- 這是 APK 側載下載，未上架 Google Play。

[SHA256SUMS.txt](SHA256SUMS.txt) 提供公開附件的校驗值；[app-versions.json](app-versions.json) 提供套件及版本資訊。合併 ZIP 內另有 `APK-SHA256SUMS.txt` 校驗三個 APK。

## 教材來源

- [數學遊樂園原始專案](https://github.com/claudecat30-sys/newmathpark)
- [新課綱數學原始專案](https://github.com/claudecat30-sys/newmath)
- [迪諾玩注音拼音原始專案](https://github.com/claudecat30-sys/Dino-ZhuyinPinyin)

此儲存庫提供整合會員功能的連線版 Android APK 與下載說明。
