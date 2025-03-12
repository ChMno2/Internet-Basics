# Linux：
## ls 列出文件
-   –l顯示更詳細的信息
-   -a 顯示隱藏文件的所有文件
-   -h以人類可讀顯示
-   -t以時間排序
-   -r逆序顯示

## ln創建鏈接文件    
-   -s加上等於軟鏈結文件
-  -   Ex:ls –s hello.txt link.txt

-   可將文件更改成不同的權限
-  -   Ex : chmod +rx hello.txt 添加讀寫權限給hello.txt

## vi hello.txt 創建文件
-   touch hello.txt 創建文件
-   echo “hello” -    hello.txt


## 常用操作
-   pwd 顯示當前目錄所在位置
-   cd 切換目錄
-   cat 讀取文件內容
-   複製file1.text並取名為file2.text
-    cp file1.text file2.text 
-   遞迴複製目錄
-  -   cp –r folder1 folder_copy
-   重新命名文件
-  -   mv file2.text hello.text 
-   刪除文件
-  -   rm file1.text
-   創建目錄
-  -   makdir 
-   創建folder1目錄並把folder2塞入…以此類推
-  -   mkdir –p folder1/folder2/folder3
-   返回上一級目錄
-  -   cd..
-   返回上上級目錄
-  -   cd../..
-   列出當前所有目錄的結構
-  -   du
-   刪除目錄
-  -   rmdir folder (要在空目錄中執行)
-  -   rmdir –r folder (遞迴刪除每一個目錄)

