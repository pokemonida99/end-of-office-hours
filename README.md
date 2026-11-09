# 上班時間的盡頭 · The End of Office Hours

一間會照你電腦時間倒數到 18:00 的 3D 辦公室。
下班那一刻，鐘聲響起，時鐘化成夕陽，螢幕變成燈籠升空，文件摺成紙飛機飛向晚霞。

A 3D office that counts down to 18:00 on your own computer's clock. When the bell rings, the clock becomes the sunset, every screen rises as a lantern, and every document folds into a paper plane.

**a4不想上班 製作** · [@a4ux_reels](https://www.instagram.com/a4ux_reels/)

## 玩法 · How to play

| 操作 | 效果 |
|---|---|
| 拖曳畫面 | 環顧四周 |
| 滾輪／按住空白鍵 | 推進時間 |
| 拖曳右上時間條 | 直接快轉（只能往前） |
| 點一塊螢幕 | 讓那個座位提早下班 |
| 下班後點海面 | 激起漣漪 |
| R ／ M ／ H | 重來／靜音／隱藏文字 |

上班時會從座位隨機冒出 70 句彩蛋台詞，結尾的「收集冊」會記下你聽過哪些，沒聽過的顯示 ???。

## 本機執行 · Run locally

網頁要透過 http 伺服器開，直接雙擊 `index.html` 會讀不到音樂。

```bash
py -m http.server 8912
```

然後打開 http://localhost:8912

## 檔案 · Files

- `index.html`：整個作品（Three.js 0.160，從 jsDelivr 載入）
- `music/office.m4a`：上班的歌〈fluorescent hum〉
- `music/clockout.m4a`：下班的歌〈Golden Hour Release〉
- `music/bell.mp3`（選用）：18:00 的寺鐘音效；沒有這個檔就用內建合成鐘聲

音樂以 Suno 製作。
