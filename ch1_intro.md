# 資料探勘 DataMining
### 定義
在大量自動化資料中 找出有用的資訊流程，單純的搜尋不算資料探勘 e.g. 網站上搜尋關鍵字  
### 起源
<img src="https://user-images.githubusercontent.com/86312099/123188176-2b50d000-d4ce-11eb-8e08-5655709a249f.png" width="335" height="300">

傳統的方法可能無法分析下列資料
* 大規模 Large-scale
* 高維度 High dimensional
* 異質 Heterogeneous
* 複雜 Complex
* 分散 Distributed

### 資料探勘的工作
+ 預測方法 Prediction - 以其他屬性值，預測特定屬性值  
  + Classification
  + Prediction
  + Time - Series Analysis
+ 敘述性方法 Description - 找出人類可以解釋的描述資料的樣式
  + Association
  + Clustering
  + Summarization
  
</br>

## 四種主要技術
* 預測模式
* 關聯規則分析
* 分群分析
* 異常偵測

</br>

### 預測模式
建立一個將 目標變數 視為 解釋變數 的函式之模式
> 應變數（Dependent Variable）：又稱解釋變數，通常表示所要推測的結果
</br>

預測模式有兩種  
+ **分類模式 Classification**：應用在目標變數為 離散型 的資料上
  + 將信用卡交易歸類為合法或欺詐
  + 使用衛星數據對土地覆蓋（水體、城市地區、森林等）進行分類
  + 將新聞故事分類為金融、天氣、娛樂、體育等
  + 識別網絡空間中的入侵者
  + 預測腫瘤細胞為良性或惡性
  + 將蛋白質的二級結構分類為 α-螺旋、β-折疊或無規捲曲
+ **回歸模式 Regression**：應用在目標變數為 連續型 的資料上
  + 根據廣告支出預測新產品的銷售額
  + 預測作為溫度、濕度、氣壓等函數的風速
  + 股票市場指數的時間序列預測
  
>e.g. 花形預測(?)

### 關聯規則分析
+ **Association Analysis** : 用來發現資料中具有高度關聯的特徵屬性
  + 購物籃分析 - 商品採買關聯性
  + 醫學信息 - 找出特定症狀患者與測試結果的組合 

### 分群分析
+ **Clustering** : 找出一群具有相似特值得觀察值，該群需具有和其他觀察值不同的特性
  + 針對性營銷的自定義分析
  + 將相關文檔分群
  + 對具有相似功能的基因和蛋白質進行分組
  + 價格波動相似的集團股票

### 異常偵測
+ **Deviation/Anomaly/Change Detection** : 從資料中找出具有顯著差異的觀察值
  + 信用卡詐騙檢測
  + 網絡入侵檢測
  + 全球森林覆蓋變化檢測
  + 識別來自無線感測網路的異常行為以進行監視和監視
