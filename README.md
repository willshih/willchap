#willchap  
<table><tr><td bgcolor=orange>背景色是：orange</td></tr></table>
# <font color="#dd0000">Final project--電子鎖</font><br />
## 使用工具  
FPGA開發版:
>8bit switch  

>顯示燈號

>按鈕  

  
筆電  
<font color=#A52A2A size=4 >Markdwon测试</font>
## 功能說明
1.8bit switch 之功能為 輸入設定之密碼 以及 輸入猜測的密碼。  

2.燈號顯示D1,D2為密碼鎖之狀態  

>D1表示該密碼鎖為關閉的狀態  

>D2表示該密碼鎖為解鎖的狀態  

3.D3~D6燈號 則會顯示設定的密碼  

4.按鈕S3為設定密碼 觸發的話會將D1=1 以及D3~D6顯示  

5.按鈕S1會比對猜測的密碼與設定的密碼是否相同，若不同則蜂鳴器會響起，  

範例影片中由於蜂鳴器太吵所以並沒有設置 不過可以正常的作用  

若是密碼相同的話則D1=0 D2=1;  

若是該鎖已經被解鎖過 (i.e. D2=1的話) 則並不會觸發動作  

6.clear按鈕則會將所有記數歸0


