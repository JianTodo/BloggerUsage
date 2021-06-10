<div class="mdtable"></div>
<img src="https://github.com/JianTodo/BloggerUsage/blob/master/0006.PO%20BO%20VO%20DTO%20DAO%20%E5%90%8D%E8%A9%9E%E8%A7%A3%E9%87%8B%E8%88%87%E9%97%9C%E4%BF%82/1.jpg?raw=true"  />

## 前言
剛出社會的工程師，很多專有名詞聽都沒聽過!
~~小編倒是只會用幾個~~
以下將針對`PO` 、`BO` 、`VO` 、`DTO` 、`DAO` 說明 **:**

<!--more-->

<hr>
<div class="headline">

 - <a href="#名詞說明">名詞說明</a>
 - <a href="#名詞關係">名詞關係</a>
 - <a href="#總結">總結</a>
</div>
<hr>

1. <div id="名詞說明">名詞說明</div> 
	
	<div class="mdtable"></div>
	
	| 專屬名詞 | 縮寫 |中譯|詳細說明|
	|:--|:--:|:--|:--|
	| Persistent Object | PO |持續性物件|資料庫的一筆紀錄|
	| Business Object|BO|業務性物件|將業務邏輯封裝為一個物件|
	| Value Object|VO|數值物件|對應界面所顯示的物件|
	| Data Transfer Object|DTO|資料傳輸物件|主要用於需要大量傳輸物件的地方|
	| Data Access Object | DAO| 資料存取物件|主要用於撰寫資料庫的指令
	

2. <div id="名詞關係">名詞關係</div>     

	```mermaid
	sequenceDiagram
	User ->> VO: Request
	VO ->> PO: Give Data To Response
	PO ->> BO: Logical judgment
	PO ->> DAO: Give Data From DataBase
	DAO ->> DTO: Transform Data To Response
	DAO -->> PO: Response DAO 
	DTO -->> VO: Response DTO
	BO -->> VO: Response BO
	PO -->> VO: Response PO
	VO -->> User: Response

	Note right of DAO: It will connection<br> dataBase to get data.
	```
## 總結
小編只常用`DAO`與`DTO`
所以其他名詞也是邊看邊學
> 如有錯或是要補充請留言**謝謝!!!**
