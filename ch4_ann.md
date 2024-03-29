# Artificial Neural Networks ( ANN )
> 類神經網路  
> 當資料不是呈線性分布時，logistic 分類器的效果就會很差  
> ANN 可以解決 資料對稱分布( [XOR Neural Network](https://github.com/fuhsaio/BDLabNotes/blob/main/src/XOR_network.png) )、無法簡易定義其特徵值 . . . [參考文章](http://terrence.logdown.com/posts/1132631-neural-networks-with-backpropagation-one-notes)

## 神經網路結構
<img src ="https://user-images.githubusercontent.com/86312099/125405767-a9780680-e3ea-11eb-8d98-0bd9c50b4a4b.png" width="500">

+ 輸入層 input layer
+ 隱藏層 hidden layer - 多個
+ 輸出層 output layer

<br>

## 感知器 Perceptron
> 上圖中每個圓圈為神經元( 也可稱為 感知器 )  
> 每個感知器中分為 輸入節點、輸出節點 ( 如下圖 )  
> 範例 - [連結](https://user-images.githubusercontent.com/86312099/125407330-5b640280-e3ec-11eb-85e9-e1773483a7a0.png)
<div style="display:inline-block;">
<img src="https://user-images.githubusercontent.com/86312099/125406447-6e2a0780-e3eb-11eb-9232-d7d11467af36.png" width="300">
<img src="https://user-images.githubusercontent.com/86312099/125406626-9dd90f80-e3eb-11eb-9d40-2b5fa5ae0d4e.png" width="250">
</div>

### 激活函數 activation functions 
> 像是控制每個神經元傳遞的閥門，將線性數值轉為非線性  
> eg. Sign函數 > 0 傳遞 1 ; < 0 傳遞 -1

<img src="https://user-images.githubusercontent.com/86312099/125413503-ae2e2c06-4c80-4816-937b-f1a3dbc5f4c8.png" width="350">

> 為什麼需要激活函數 - [影片](https://www.youtube.com/watch?v=tI9AbaBfnPc)


### Perceptron Learning Rule
> 初始化權重 Weight

**範例** - [連結](https://github.com/fuhsaio/BDLabNotes/blob/main/src/ch4_ann_perceptron.pdf)

### Backpropagation
> 反向傳播  
> 搭配 梯度下降法（Gradient Descent）更新權重

(1) 初始化神經網路所有權重  
(2) 將資料由input layer往output layer向前傳遞運算(forward)計算出所有神經元的output  
(3) 計算誤差由output layer往input layer向後傳遞運算(backward)算出每個神經元對誤差的影響  
(4) 用誤差影響去更新權重  
重複 2、3、4 直到誤差收斂到夠小

<br>


---

### 文章參考
ANN 系列鐵人賽 - [連結](https://ithelp.ithome.com.tw/articles/10201931)  



