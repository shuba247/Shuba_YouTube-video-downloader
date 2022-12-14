# Shuba YouTube影片下載器
此專案是110學年度第二學期自主學習計畫「以Python製作YouTube影片下載器」之成果。以下針對本專案內容進行介紹。

## 成果簡介
(待補)

## 初始設計版(v1.0)
規劃期間：2022.04.14\~2022.04.17<br>
製作期間：2022.04.20\~2022.05.25

### 目標
- [x] 使用tkinter模組製作下載器介面
- [x] 使用pytube模組製作執行影片下載部分程式
- [x] 完成各按鈕事件處理function
- [x] 使用try-except語法處理影片下載失敗之作為
- [x] 使用pyinstaller將程式碼封裝為exe執行檔

### 實際成果
(待補)

### 檢討與展望
根據各方使用後給予之回饋，以及自我審視後，整理出目前v1.0有以下問題須解決：
1. 以1080p與2160p下載影片時，影音會分開<br>
發生原因：pytube模組本身缺陷<br>
解決方法：以moviepy模組進行影音合併輸出
2. 下載器介面留空過多<br>
發生原因：介面設計不良<br>
解決方法：重新進行排版，部分區塊改以彈出視窗代替
3. 存檔路徑需手動輸入<br>
發生原因：設計時未考慮到使用者使用方便性<br>
解決方法：改用彈出視窗進行存檔資料夾選擇
4. 影片存檔完需自行至資料夾開啟<br>
發生原因：設計時未考慮到使用者使用方便性<br>
解決方法：影片下載完成後自動開啟下載位置
5. 影片名稱確認區塊有點多餘<br>
發生原因：設計該區塊，本意是幫助使用者確定下載之影片是否正確，然使用者經常在下載前忘記確認，導致使用者覺得不便，是考慮不周全<br>
解決方法：改以彈出視窗進行確認
<!-- -->
──更新於2022.05.28

## 功能增進版(v2.0)
規劃期間：2022.05.26\~2022.05.29<br>
製作期間：2022.06.01\~2022.08.07

### 目標
- [x] 使用moviepy模組，解決v1.0之問題1
- [x] 刪除提示文字區塊，以彈出視窗代替
- [x] 刪除存檔路徑輸入區塊，改以彈出視窗進行存檔資料夾選取
- [x] 影片名稱確認區塊刪除，其功能併入確認下載彈跳視窗
- [x] 影片下載完成後開啟下載位置
- [x] 添加程式資訊(2022.07.17追加)
- [x] 下載器介面重新排版，減少視窗大小(2022.08.05追加)
- [x] 添加音訊下載功能(2022.08.05追加)

### 實際成果
(待補)

### 檢討與展望
根據各方使用後給予之回饋，以及自我審視後，整理出目前v2.0有以下問題須解決：
1. 運行速度太慢
2. 影片下載失敗率偏高
3. 影音合併失敗率偏高
<!-- -->
上述問題發生原因，我推測是，但目前尚未有解決方法，望各界能給予相關建議。<br>
另有期望未來能新增之功能或改進部分如下：
1. 播放清單下載
2. 影片指定時間段下載  
<!-- -->
──更新於2022.08.12

## 參考資源
YouTube下載器製作架構：<br>
[文淵閣工作室（2020）。**《Python初學特訓班(第四版)：從快速入門到主流應用全面實戰》**。碁峰。](https://www.books.com.tw/products/0010863623?gclid=CjwKCAjwu5yYBhAjEiwAKXk_eFixvJkAJg-YIuSghUsdzmiLBSoYs2ZUGww0TmxnEz_cFcrSBeLnIBoCozcQAvD_BwE)