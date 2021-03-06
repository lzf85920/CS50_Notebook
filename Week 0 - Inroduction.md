# Week 0 - Inroduction


馬蘭教授（David J. Malan）認為電腦科學是一種問題解決的方法，從輸入（input）到輸出（output），中間那塊就是電腦科學（Algorithm）。

 ![](https://i.imgur.com/sC9Rl0u.png)
1. **Binary digit(Bit)**
二進制在數學和數位電路中指以2為基數的記數系統。這一系統中，通常用兩個不同的數字0和1來表示，每個數字稱為一個位元（Bit，Binary digit 的縮寫）。

|二進位|十進位|二進位|十進位|
|----------|----------|----------|----------|
|0|000|4|012 $\Rightarrow$ 100|
|1|001|15|$2^3+2^2+2^1+2^0$ $\Rightarrow$ 00001111|
|2|002 $\Rightarrow$ 010|50|$2^5+2^4+2^1$ $\Rightarrow$ 11010
|3|011|123|$2^6+2^5+2^4+2^3+2^1+2^0$ $\Rightarrow$ 01111011

\
2. **ASCII（American Standard Code for Information Interchange，美國資訊交換標準代碼）**
ASCII是基於拉丁字母的一套電腦編碼系統。它主要用於顯示現代英語。

缺點：ASCII的局限在於只能顯示26個基本拉丁字母、阿拉伯數字和英式標點符號，因此只能用於顯示現代美國英語。因此，現在的軟體系統大多採用Unicode。

\
3. **RGB（Red,Green,Blue）**
常見的設定值是 24 位元模式，即每一個原色以 8 位元來處理。24 位元編碼的 RGB 值，是以紅綠藍（通常按這個次序）強度的 3 組 8 位元（0 ~ 255）來表示。每一原色的強度依照 8 位元的最高值 28，可以分為 256 個數值，用這種方法能組合出 1,670 萬（256 × 256 × 256）種顏色。但是，人眼實際只能分辨出約 1,000 萬種左右的顏色。

For example：
黑色(0,0,0)、白色(255,255,255)、紅色(255,0,0)、綠色(0,255,0)、藍色(0,0,255)。

一張圖片由上百萬個像素(Pixel)組成，而每個pixel為一個RGB的組成原色區塊。此外影片的顯示，則是透過即時更新每個pixel來達成視覺效果。

\
4. **演算法（Alogrithm）**
演算法是找尋、計算資料的方法，假設我們想在電話簿裡找到Joe，我們可以有下列3種方法：
* 從第一頁開始翻，翻到最後一頁。
* 每一次翻兩頁，但是如果翻過頭，就得回頭。
* 將電話簿從中間分一半，確認Joe是在左邊還是右邊的電話簿，如果在左邊，就可以把右邊丟棄。然後再將剩下的電話不分一半，再確認是在左邊還是右邊。如果電話簿為1024頁，最多只要10步驟，就能找到任何要找的人名。


![](https://i.imgur.com/9rhaJGG.png)
* 第一個方法為紅線，所花的時間最多。
* 第二個方法為黃線，雖然只需要紅線的一半，但是隨著頁數的增加，也會大量增加解決時間。
* 第三個方法，綠線所耗費的時間最短，因為僅有10個步驟，不管頁數再怎麼增加，也不會增加太多時間。



