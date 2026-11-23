# 九州九日旅帖

2026/12/27 – 2027/1/4・熊本進、福岡出的九天互動行程。

網址：https://eunice8678.github.io/Fukuoka_1227/

## 檔案

- `index.html`：頁面本身
- `trip.json`：行程資料（所有人看到的都是這一份）

## 修改行程，讓所有人看到

1. 打開網頁，點右上方的同步狀態，例如「已是最新行程」
2. 依照畫面說明建立 GitHub 金鑰：
   - 到 https://github.com/settings/personal-access-tokens/new
   - Repository access 選 Only select repositories → `Fukuoka_1227`
   - Permissions → Contents 設為 Read and write
3. 把金鑰貼上並儲存。金鑰只存在這台裝置的瀏覽器
4. 按右下角「編輯行程」，之後的修改約 2 秒內會自動寫回 `trip.json`

其他人打開或切回網頁時，會讀到最新的行程。已經開著的頁面大約每 1～3 分鐘會自動更新一次。

沒有設定金鑰的人也能編輯，但修改只會留在自己的瀏覽器。

## 注意

- 金鑰等於這個 repository 的寫入權限，不要分享出去，也不要用在公用電腦
- 上傳的照片會一起存進 `trip.json`，照片太多會讓網頁變慢
