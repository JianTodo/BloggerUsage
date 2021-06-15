
<div  class="mdtable"></div>

<img  src="https://github.com//JianTodo/BloggerUsage/blob/master/0010.nodeJs%20Install/0.png?raw=true"  />

  

## 前言

**Node.js 是什麼呢？**

官網說法：

> Node.js® is a JavaScript runtime built on Chrome's V8 JavaScript engine.

  

簡單來說Node.js 就是能執行 JavaScript 的環境，

並讓傳統的 JavaScript 程式跳脫一般的瀏覽器，

也可配合主流瀏覽器，

如 Google Chrome V8 JavaScript 引擎，

讓程式的整體的效能大幅提升

~~更簡單來說現在主流前端都仰賴它所以要裝~~

下面將介紹小編使用的步驟

<!--more-->
<hr>
<div class="headline">


  - <a href="#步驟">步驟</a>
  - <a href="#總結">總結</a>
</div>
<hr>

## 步驟

1. 前往 [Node.Js](https://nodejs.org/en/)，下載==長期支援版本(左邊 LTS)==<br/>![enter image description here](https://github.com//JianTodo/BloggerUsage/blob/master/0010.nodeJs%20Install/1.png?raw=true)
2. 點選 Next<br/>![enter image description here](https://github.com//JianTodo/BloggerUsage/blob/master/0010.nodeJs%20Install/2.png?raw=true)
3. 點選 Next<br/>![enter image description here](https://github.com//JianTodo/BloggerUsage/blob/master/0010.nodeJs%20Install/3.png?raw=true)
4. 小編都選預設值，點選 Next<br/>![enter image description here](https://github.com//JianTodo/BloggerUsage/blob/master/0010.nodeJs%20Install/4.png?raw=true)
5. ==預設原本沒有安裝 Chocolatey !!!==<br/>Chocolatey 是在 Windows 上的套件管理工具，它結合 Nuget 基礎服務與 powershell 指令，提供快速安裝應用程式與需要工具的服務，只需要一條簡單的指令，就可搜尋、安裝、更新、解安裝等操作，[詳細說明 What is Chocolatey?](https://chocolatey.org/about)<br/>**強大的工具，小編選擇安裝它!!!**<br/>點選 Next<br/>![enter image description here](https://github.com//JianTodo/BloggerUsage/blob/master/0010.nodeJs%20Install/5.png?raw=true)
6. 點選 Install<br/>![enter image description here](https://github.com//JianTodo/BloggerUsage/blob/master/0010.nodeJs%20Install/6.png?raw=true)
7. 點選 **是**<br/>![enter image description here](https://github.com//JianTodo/BloggerUsage/blob/master/0010.nodeJs%20Install/7.png?raw=true)
8. 等待安裝...<br/>![enter image description here](https://github.com//JianTodo/BloggerUsage/blob/master/0010.nodeJs%20Install/8.png?raw=true)

9. 點選 <u>F</u>inish<br/>![enter image description here](https://github.com//JianTodo/BloggerUsage/blob/master/0010.nodeJs%20Install/9.png?raw=true)
10. Node.js 安裝完成<br/>![enter image description here](https://github.com//JianTodo/BloggerUsage/blob/master/0010.nodeJs%20Install/10.png?raw=true)
11. 自動繼續安裝 Chocolatey，點選 **是**<br/>![enter image description here](https://github.com//JianTodo/BloggerUsage/blob/master/0010.nodeJs%20Install/11.png?raw=true)
12. 安裝中...<br/>![enter image description here](https://github.com//JianTodo/BloggerUsage/blob/master/0010.nodeJs%20Install/12.png?raw=true)
13. 這裡安裝需要點時間，安裝完畢<br/>![enter image description here](https://github.com//JianTodo/BloggerUsage/blob/master/0010.nodeJs%20Install/13.png?raw=true)
14. 開啟 cmd 並輸入以下指令<br/>確定 Node.js 版本<br/><pre class="brush:shell;">node -v</pre><br/>![enter image description here](https://github.com//JianTodo/BloggerUsage/blob/master/0010.nodeJs%20Install/14.png?raw=true)

## 總結

不得不說它安裝速度還算可以，
但在使用上，下載套件真的「**慢**」到有點受不了!!!之後會選用 FaceBook 開源套件 yarn 取代。
有時間再來分享 yarn vs npm。