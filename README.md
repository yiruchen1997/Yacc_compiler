Yacc 編譯器
====

簡介
----

利用Yacc製作Java編譯器。

* Lex是UNIX中一種生成Scanner的工具，該Scanner為識別文件裡的詞彙模式的程序。當Lex接收到文件輸入時，<br>會試圖將其與程式碼中的regular expression進行匹配，若找到符合的pattern便執行相對應的動作。<br><br>
* Yacc為解析語法的工具，利用由Lex中辨識出之token組合文法結構，將測試檔輸入後程式便會掃描其中內容並<br>判斷是否正確，如果出現錯誤則顯示編譯訊息。<br><br>
* 製作編譯器的過程中，最複雜的部份為制定各語法，因Java語法數量非常龐大，必須一一分析、仔細思考後<br>才能得出較為完善的結果，如果其中有漏洞存在，在偵測錯誤方面就會出現十分明顯的差異；<br>要把特殊的情形剃除偵測規則之外，例如:在多重宣告的檢查上也須特別注意，不同scope中可以宣告相同名稱的變數，<br>class的名稱也可能重複出現。


成果展示
----

> Test1 : <br><br>
![](https://github.com/yiruchen1997/yacc_compiler/blob/master/yacc_test1.JPG)

> Test2 : <br><br>
![](https://github.com/yiruchen1997/yacc_compiler/blob/master/yacc_test2.JPG)

> Test3 : <br><br>
![](https://github.com/yiruchen1997/yacc_compiler/blob/master/yacc_test3.JPG)
