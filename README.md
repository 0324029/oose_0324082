# oose_0324082
資管系3B 0324082  陳毓廷 (組長)

資管系3B 0324038  黃珮禎

資管系3A 0324089  鄭婷瑀

#_專題名稱：樓E幢_
###功能：

1.用戶登入：入住房東就給房客一組專用的帳密；房東也有一組專用的帳戶。

2.水電費：讓房客即時上網知道自己當月水電費，房東無須另外口頭或寄信通知。

3.設備維修：直接利用手機就可以讓房東知道維修項目。

4.門禁管理：使用手機NFC功能無需使用鑰匙以及感應卡就可進入大樓以及自己房間。

5.最新公告：房東以及房客可以即時上傳最新大樓的情況。例如：大樓電梯的損壞、或是臨時停電等。


###圖形介面：

####房東介面：

![image](https://cloud.githubusercontent.com/assets/22367717/19625894/7dfc02a0-9957-11e6-94e2-5463fb73bf10.jpg)

####房客介面：

![image](https://cloud.githubusercontent.com/assets/22367717/19625892/7dfa3128-9957-11e6-9ff9-d1b598418604.jpg)

###use case圖：

![image](https://cloud.githubusercontent.com/assets/22367717/19625893/7dfb2be6-9957-11e6-8e20-6c314270260a.jpg)

###系統活動圖：

![image](https://cloud.githubusercontent.com/assets/22367717/19625891/7df79580-9957-11e6-9ba2-5d9d4b6b0a24.jpg)

###use case條件式描述：

####使用者個案名稱:房東登錄

行為者:房東

目標:使房東能以app管理其他個案。

前提:房東尚未成為完成會員。

－系列事件:

正常程序－

1.房東透過app進入系統登入帳號密碼。

2.系統驗證帳號密碼

3.系統驗證房東登入成功

例外狀況－

系統驗證不成功，房東登入失敗。


####使用者個案名稱:門禁管理

行為者:房東

目標:使房東能以帳密給予房客。

前提:房東要幫每位房客設定好帳密。

－系列事件:

正常程序－

1.房東透過app進入系統登入成功。

2.房東設定好每一位房客帳密。

例外狀況－

房客帳密重複。


####使用者個案名稱:水電費管理

行為者:房東

目標:使房東利用app給予每位房客當月水電費及歷史紀錄。

前提:房客已使用水電。

－系列事件:

正常程序－

1.房東透過app進入系統登入成功。

2.房東設定好每位房客水電費。

例外狀況－

還未使用水電至當月底。


####使用者個案名稱:設備維修管理

行為者:房東

目標:使房客能以app通知房東需要維修設備。

前提:有需要維修事項。

－系列事件:

正常程序－

1.房東透過app進入系統登入成功。

2.回復房客維修日。

3.等待房客回應即可完成維修單。

例外狀況－

沒有需要維修事項。


####使用者個案名稱:最新公告

行為者:房東

目標:使房東透過最新公告通知訊息。

前提:有最新公告。

－系列事件:

正常程序－

1.房東透過app進入系統登入成功。

2.房東或樓管輸入最新公告。

例外狀況－

沒有最新公告。


####使用者個案名稱:與房客聯絡

行為者:房東

目標:使房客能以app向房東聯絡或是建議事項。

前提:房客和房東聯絡。

－系列事件:

正常程序－

1.房東透過app進入系統登入成功。

2.回復房客或是不用回復。

例外狀況－

房客訊息傳送失敗。


####使用者個案名稱:房客登錄

行為者:房客

目標:使房客能以會員身份進入大樓管制系統。

前提:房客尚未成為會員身份。

－系列事件:

正常程序－

1.房客透過app進入系統登入帳號密碼。

2.系統驗證帳號密碼

3.系統驗證房客登入成功

例外狀況－

系統驗證不成功，房客登入失敗。


####使用者個案名稱:門禁感應

行為者:房客

目標:使房客以nfc功能感應進入大樓門禁。

前提:房客手機有nfc功能。

－系列事件:

正常程序－

1.房客透過app進入系統登入成功。

2.房客感應成功

例外狀況－

感應失敗，用密碼輸入進去。


####使用者個案名稱:水電費帳單

行為者:房客

目標:使房客利用app查詢當月水電費及歷史紀錄。

前提:已使用水電。

－系列事件:

正常程序－

1.房客透過app進入系統登入成功。

2.房客查詢水電費

例外狀況－

還未使用水電至當月底，或是房東尚未完成輸入水電費。


####使用者個案名稱:設備維修

行為者:房客

目標:使房客能以app通知房東需要維修設備。

前提:有需要維修事項。

－系列事件:

正常程序－

1.房客透過app進入系統登入成功。

2.房客輸入需要維修事項。

3.等待房東回應

例外狀況－

沒有需要維修事項。


####使用者個案名稱:最新公告

行為者:房客

目標:使房客透過最新公告通知訊息。

前提:有最新公告。

－系列事件:

正常程序－

1.房客透過app進入系統登入成功。

2.房東或樓管輸入最新公告

3.房客查詢最新公告。

例外狀況－

沒有最新公告


####使用者個案名稱:與房東聯絡

行為者:房客

目標:使房客能以app向房東聯絡或是建議事項。

前提:房客和房東聯絡。

－系列事件:

正常程序－

1.房客透過app進入系統登入成功。

2.房客輸入訊息，送出。

3.等待房東回應

例外狀況－

房客訊息傳送失敗。
