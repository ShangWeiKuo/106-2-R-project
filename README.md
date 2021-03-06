# 106-2-R-project
## 以R語言分析台灣觀光產業
### 資料來源: 政府開放資料平台、高雄市政府 (以上資料是介於2013-2016)
### 提供數據較完善的城市: 新北市、桃園市、高雄市

1. 熱力圖分析: <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;利用cor()函數了解「年份」、「人數」和「收入」三者之間的相關性，並繪製成熱力圖以方便知悉三者間的關聯。由熱力圖上的顯示結果可以得知人數與收入之間呈現低度相關，亦即人數並非決定收入的主要因素。
<p align="center">
  <kbd><img src="https://github.com/ShangWeiKuo/106-2-R-project/blob/master/%E7%86%B1%E5%8A%9B%E5%9C%96.png"></kbd>
</p>

2. 信賴區間圖: <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;利用ddply對資料集進行分群並計算出內部資料的平均數、全距的最大和最小值，之後將結果畫出三個城市之觀光收入的信賴區間圖。圖上顯示高雄市的觀光收入明顯遠高於新北與桃園市。
<p align="center">
  <kbd><img src="https://github.com/ShangWeiKuo/106-2-R-project/blob/master/%E4%BF%A1%E8%B3%B4%E5%8D%80%E9%96%93%E5%9C%96.png"></kbd>
</p>

3. 小結: <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;大眾常有南北差距的認知，不論是經濟、人口、或是各種資源等方面，許多人普遍認為北部優於南部。再者，我們常會將觀光人數的多寡與收入的多少畫上等號。由上述的分析中，可以得知在各縣市的觀光收入比較上，南部城市(高雄市)明顯高於北部城市(新北市、桃園市)，且從熱力圖的呈現可看出觀光人數與觀光收入的關聯為低度相關，也就是說<b>觀光人數多不一定代表連帶的收入也會高於其他縣市</b>。
