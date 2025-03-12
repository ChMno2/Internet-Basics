## ls 列出文件
<br/>  –l顯示更詳細的信息
<br/>  -a 顯示隱藏文件的所有文件
<br/>  -h以人類可讀顯示
<br/>  -t以時間排序
<br/>  -r逆序顯示

## ln創建鏈接文件    
<br/>  -s加上等於軟鏈結文件
<br/> -  Ex:ls –s hello.txt link.txt

<br/>  可將文件更改成不同的權限
<br/> -   Ex : chmod +rx hello.txt 添加讀寫權限給hello.txt

## vi hello.txt 創建文件
<br/>  touch hello.txt 創建文件
<br/>  echo “hello” <br/>   hello.txt


## 常用操作
<br/>  pwd 顯示當前目錄所在位置
<br/>  cd 切換目錄
<br/>  cat 讀取文件內容
<br/>  複製file1.text並取名為file2.text
<br/>   cp file1.text file2.text 
<br/>  遞迴複製目錄
<br/> -   cp –r folder1 folder_copy
<br/>  重新命名文件
<br/> -   mv file2.text hello.text 
<br/>  刪除文件
<br/> -   rm file1.text
<br/>  創建目錄
<br/> -   makdir 
<br/>  創建folder1目錄並把folder2塞入…以此類推
<br/> -   mkdir –p folder1/folder2/folder3
<br/>  返回上一級目錄
<br/> -   cd..
<br/>  返回上上級目錄
<br/> -   cd../..
<br/>  列出當前所有目錄的結構
<br/> -   du
<br/>  刪除目錄
<br/> -   rmdir folder (要在空目錄中執行)
<br/> -   rmdir –r folder (遞迴刪除每一個目錄)

