![image](https://github.com/Youchenjiang/-SQL-Server-.xlsx-/assets/89691664/66cfb3ae-bd9d-4abb-8369-a9e5d1f0a19b)
# Visual Studio 2022 新版 SQL Server 匯入 EXCEL 資料方法  
說明：1表示Visual Studio 2022中操作；2表示SQL Server Management Studio 20中操作  
---
1-1.在「Visual Studio 2022」開啟專案後，在「方案總管」的網站處右鍵，選擇加入/加入新項目  
1-2.選擇加入「SQL Server資料庫」  
1-3.點擊新建的「Database1.mdf」，使得伺服器總管中的Database1.mdf為綠色圖標  
1-4.開啟工具/選項，在最下方的資料庫工具中找到資料連接，並複製SQL Server執行個體名稱  
接下來就可以在SSMS中作操作
---
2-1.資料來源處選擇「Microsoft Excel」，點擊「Next」  
<img width="400" height="150" src="/Image/1.png"/>  
2-2.會出現「」錯誤  
<img width="400" height="150" src="/Image/2.png"/>    
3.搜尋[Microsoft Access Database Engine 2016 可轉散發套件](https://www.microsoft.com/zh-tw/download/details.aspx?id=54920)  
<img width="400" height="150" src="/Image/3.png"/>  
4.將它存在「下載」目錄底下  
<img width="400" height="150" src="/Image/4.png"/>  
5.點擊「accessdatabaseengine_X64.exe」，安裝在「C:\Program Files\Microsoft Office\」資料夾內  
<img width="400" height="150" src="/Image/5.png"/>  
6.在「下載」資料夾下，右鍵後點擊「在終端中開啟」(無圖)  
輸入「cmd」，點擊Enter，輸入「AccessDatabaseEngine.exe」，點擊Enter  
<img width="400" height="150" src="/Image/6.png"/>  
7.回到第1步驟，此時已經可以點擊「Next」  
<img width="400" height="150" src="/Image/7.png"/>  
8.更改目的地為「Microsoft OLE DB Driver」  
<img width="400" height="150" src="/Image/7.png"/>  
9.點擊屬性，
