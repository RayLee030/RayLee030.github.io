
# BSC 錢包每日發送 BNB 交易統計工具

## 📊 專案簡介

本工具提供 **BSC 錢包在指定日期（UTC+8）每日發送 BNB 的統計分析**，包含：
- BNB 發送總量及其 USD 價值
- 每日交易量（以 USD 計價）
- 綜合損益（根據收支與 Gas 估算）
- 詳細的交易明細

使用者只需輸入：
1. BscScan API 金鑰
2. 錢包地址（BSC）
3. 查詢日期

即可即時取得對應交易資料與視覺化分析結果。

---

## 🌟 功能特色

- 📆 自動依據 UTC+8 時區，統計每日 8:00 ~ 隔日 7:59 的發送紀錄
- 💰 自動換算 BNB 發送金額與當日交易量（以 USD 為單位）
- 📈 動態顯示交易量進度條（採用 2 的次方分級）
- 📉 自動估算當日損益（考慮內部交易、Gas）
- 🧾 明細列表含交易哈希與 BNB 數量

---

## 🖼️ 使用畫面

> ![功能畫面預覽](https://user-images.githubusercontent.com/your-image-placeholder.png)  
> 範例畫面：損益分析、交易明細、進度條等

---

## 🚀 使用方式

### 1. 前置準備

請先前往 [BscScan 官方網站](https://bscscan.com/myapikey) 申請一組 API Key。

### 2. 開啟網頁

直接開啟 `main.html` 即可使用，無需伺服器或額外安裝。

### 3. 輸入參數並查詢

- 填入 BscScan API Key
- 輸入 BSC 錢包地址（如 `0x...`）
- 選擇查詢日期
- 點擊「查詢交易量與損益」

---

## ⚠️ 注意事項

- 每日查詢次數受限於 BscScan API 速率限制
- 內部交易會一併納入損益計算
- 此工具僅供數據參考，請勿作為財務建議依據

---

## 📄 授權

本專案以 MIT License 授權。歡迎自由修改與轉載，請保留出處。

---

## 🙌 貢獻者

作者：[Ray Lee](https://github.com/your-profile)

若有建議或問題，歡迎提出 [Issue](https://github.com/your-repo/issues) 或 PR！
