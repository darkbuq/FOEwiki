## BER_dB_sensitivity

[bit error rate (BER)位元錯誤率](https://zh.wikipedia.org/zh-tw/%E6%AF%94%E7%89%B9%E8%AF%AF%E7%A0%81%E7%8E%87)

指單位時間差錯位元的數量  
通常以百分比的形式表示

```
舉一個例子，假設傳輸的位元序列為：

0 1 1 0 0 0 1 0 1 1

而接收到的位元序列為：

0 0 1 0 1 0 1 0 0 1,

在本例中，差錯位元（加底線的位元）的數量為3。誤碼率為差錯位元數3除以傳輸的位元數10，也就是0.3或者30%。
```

---

在光通信模組中，`BER` 代表位元錯誤率（Bit Error Rate）  
而 `db sensitivity` 則指的是接收端的靈敏度，通常以分貝（dB）為單位  
因此，`BER db sensitivity` 的意思是  
指 `光通信模組能夠在特定的位元錯誤率下 接收並辨識出的最低光信號強度`  
這個數值越小，代表模組越能夠在較低的光信號條件下正確地解讀資料。  

<img src="PSK_BER_curves.png" alt="drawing" width="500"/>  


BER 取了 `log對數`  似乎會變成直線  

<img src="BER-versus-receiver-sensitivity-of-DS.png" alt="drawing" width="500"/>
