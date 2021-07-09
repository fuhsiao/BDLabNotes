# Ensemble 集成
> 以系統化的方式將好幾個監督式學習的模型結合，目的是產生一個更強大的模型

<br>

## Types of Ensemble Methods
+ **Manipulate data distribution**
  + bagging
  + boosting
  
+ **Manipulate input features**
  + random forests
  
+ **Manipulate class labels**
  + error-correcting
  + output coding

## Bagging
> bootstrap aggregating 自助聚合
+ 從 trainning data 中隨機抽取(取後放回)，依每輪抽取的樣本 訓練多個分類器  
  每個分類器權重一致做 Majority vote(多數決)
+ 此抽樣的方法在統計上稱為 bootstrap  
+ 原始資料若有 noisy，可以降低不穩定性

示例 - [連結]()



