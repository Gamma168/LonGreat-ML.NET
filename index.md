![Logo](/Images/image001.jpg)

# 開發團隊

| 姓名  | ename  | 單位 |  e-mail |
| -------|------ | -------|------ |
| 黃博翰 | Aaron | 清大研究生 | [polomarco159@gmail.com](polomarco159@gmail.com)  |
| 張楟穎 | Lisa | 虎尾科大   | [lisa911015@gmail.com](lisa911015@gmail.com)  |
| 張長豐 | Gamma | 豐碩科技   | [gamma168@gmail.com](gamma168@gmail.com)  |

# 簡介

[NET6](https://docs.microsoft.com/dotnet/core/whats-new/dotnet-6) & [ML.NET 17.1](https://docs.microsoft.com/dotnet/machine-learning/tutorials/) & [Devexpress](https://www.devexpress.com/)

支援所有資料來源，無須撰寫程式碼

![home](/Images/image007.jpg)

![nocode](/Images/NoCode.png)
![export](/Images/image008.png)
![fast](/Images/image009.png)

![fast](/Images/image010.png)

![fast](/Images/image011.png)

![fast](/Images/image012.png)

![fast](/Images/image013.png)

# 資料來源

幾乎涵蓋市面所有資料型態，資料聯合Federation DataSource提供不同資料源合併

![fast](/Images/image014.jpg)

![fast](/Images/image015.jpg)

![fast](/Images/image016.jpg)

## 資料聯合Federation DataSource

是一個聯合資料源，它集成了不同的數據源並通過聯合查詢提供統一的資料訪問。
建立以下類型的聯合查詢：
Join
根據共享的列組合來自兩個或多個表的行。連接類型指定在兩個表中具有匹配值的記錄。
Union / UnionAll
Union查詢將兩個或多個表中的行組合成一個數據集，並刪除合併表中的重複行。UnionAll查詢的操作類似於Union ，但是當它們包含相同的數據時，它們會復制來自不同表的行。您只能為包含同名列的數據源創建聯合查詢。此類列的數據類型應進行隱式轉換。
Transformation
如果數據源包含複雜的列（對象），您可以轉換其屬性以在平面視圖中將它們顯示為單獨的列。如果其中一個數據列是一個數組，您可以展開它的值並為數組的每個元素顯示一個新的數據行。展開柱時，您可以將其展平並創建展平視圖。

![fast](/Images/image017.jpg)

## 檔案目錄轉資料表

![fast](/Images/image018.jpg)

# 資料處理&轉換

## 資料處理程序

引導程式	BootstrapSample

快取	Cache

欄位篩選	FilterRowsByColumn

按關鍵欄位分數篩選	FilterRowsByKeyColumnFraction

缺失值欄篩選	FilterRowsByMissingValues

隨機資料列	ShuffleRows

跳過資料列	SkipRows

擷取資料列	TakeRows

## 資料轉換函式

![Transformation](/Images/Transformation.png)

# 特徵與標籤

拖拉欄位設定

![fast](/Images/image019.jpg)

# 訓練模型

![Trainer](/Images/Trainer.png)

# 評估

評估紀錄與相關分數紀錄

![fast](/Images/image020.jpg)

# 預測

批次預測與輸入預測

# 預測應用

訓練模型產生zip檔，程式載入使用

