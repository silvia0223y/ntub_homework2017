只要輸入Scaffold 並寫出需要的欄位內容和格式就可以馬上幫你建立好網站，這個指令幫你輸入有以下幾方面的程式：
View ：幫你把表單名稱和欄位顯示出來。
Controller ：建立了新增、顯示、修改、刪除動作。
例如在新增、顯示、修改、刪除動作連結方面，在老師利用拆解的方式來教導時，就利用link_to來連結，在動作設計用 redirect_to candidates_path和notice
來回到主畫面和提示訊息。為防止駭客惡作劇竄改程式碼，程式碼還設計只允許當初設計要填寫的欄位，可避免增加資料庫遭竄改
