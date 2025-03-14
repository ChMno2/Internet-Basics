# 基本cmd指令

1. cd:切換資料夾位

2. cd:切換到該槽的根目錄

> cd..:退回到上一層
> d::直接移至D槽
> e::直接移到E槽(下e:即可,移到其他槽,以此類推)

3. cls:清除螢幕

4. dir:列出目錄中的檔案及子目錄(若是Mac輸入Is,Windows輸入 dir)

5. 記事本：打開記事本

6. shutdown:倒數關機指令

7. calc:打開計算機

8. psr:錄製電腦操作步驟

9. hostname:顯示電腦名稱

10. winver:查詢當前Windows版本

11. <Tab>鍵:在cmd中按下tab鍵,有「自動補充」的功能(會使用方便很多)。

例如：<br>

如果有一個資料夾名稱為「test123Hi」, <br>

在cmd中輸入「te」+「Tab鍵」,後續字元會自動補充完成。 <br>

對於名稱很長的非常有幫忙,可以少打很多! <br>

如果有兩個資料夾名稱分別為「test123Hi」及「telegram」, <br>
一樣在cmd中輸入「te」+「多次Tab鍵」,可以自動對應到te開頭的名稱,非常方便! <br>


# 常用網路cmd指令

1. ping:用來檢測網絡的連通情況和分析網絡速度(最常用到)

> ping-t:不間斷的一直ping

2. nslookup:查詢域名對應的IP位址

3. tracert (trace route):來追蹤封包傳遞到目的地所經的路徑和時間,在網路固障時常用來查找是哪一台機器出問題

※ 直接下tracert,可看到使用參數介紹

4. netstat:查看網路連線、路由表、連接埠狀態及相關統計資訊的工具,常常被用來檢測網路環境是否正常

> netstat -a:列出所有連接埠

> netstat -at:只列TCP部分

> netstat -au:隻列UDP部分

> netstat -b:列出port相對應的程式

> netstat -r:列出目前的路由表(Routing Table),有助於網路連線故障的判斷

5. ipconfig:查詢本機IP位址

ipconfig/all:會顯示出更detail資料
