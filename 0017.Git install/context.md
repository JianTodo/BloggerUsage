<div  class="mdtable"></div>

<img  src="https://github.com/JianTodo/BloggerUsage/blob/master/0017.Git%20install/0.png?raw=true"  />

## 前言
> 什麼是 Git？

簡單來說「[Git](https://en.wikipedia.org/wiki/Git) 是一種分散式的版本控制系統」。以下說明一下兩個名詞==分散式==與==版本控制系統==：

> 何謂分散式？
何謂版本控制系統？

==分散式==便可以將記錄分佈在線下(offline)本機或是線上(online)伺服器「多個」環境上。
==版本控制系統==問世原因是電腦上檔案，往往都是需要新增、編輯、修改許多次，但每次都只儲存一次，也就是最後一次的變更，那該怎麼確認每次異動的部分呢？這時候能夠控制每次儲存後版本之變更內容的系統便問世了。
以下小編將介紹每個作業系統的安裝步驟：
<!--more-->
<hr>
<div class="headline">

 - <a href="#ubuntu">Ubuntu</a>
 - <a href="#windows">Windows</a>
 - <a href="#mac-檔案篇">Mac 檔案篇</a>
 - <a href="#mac-指令篇">Mac 指令篇</a>
 - <a href="#總結">總結</a>
</div>
<hr>

## Ubuntu
1. 更新系統<br/><pre  class="brush:shell;">sudo apt update</pre>![enter image description here](https://github.com/JianTodo/BloggerUsage/blob/master/0017.Git%20install/Linux/1.png?raw=true)
2. 輸入下載指令<br/><pre  class="brush:shell;">sudo apt install git</pre>![enter image description here](https://github.com/JianTodo/BloggerUsage/blob/master/0017.Git%20install/Linux/2.png?raw=true)
3. 安裝完成，確認 Git 版本<pre  class="brush:shell;">git --version</pre>![enter image description here](https://github.com/JianTodo/BloggerUsage/blob/master/0017.Git%20install/Linux/3.png?raw=true)

## Windows
1. [官網下載](https://git-scm.com/download/win)後執行<br/>![enter image description here](https://github.com/JianTodo/BloggerUsage/blob/master/0017.Git%20install/Windows/1.png?raw=true)
2. 合約條款，點選「Next」<br/>![enter image description here](https://github.com/JianTodo/BloggerUsage/blob/master/0017.Git%20install/Windows/2.png?raw=true)
3. 選擇安裝於哪個資料夾，小編使用預設值，點選「Next」<br/>![enter image description here](https://github.com/JianTodo/BloggerUsage/blob/master/0017.Git%20install/Windows/3.png?raw=true)
4. 選擇安裝套件，小編使用預設值，點選「Next」<br/>![enter image description here](https://github.com/JianTodo/BloggerUsage/blob/master/0017.Git%20install/Windows/4.png?raw=true)
5. 點選「Next」<br/>![enter image description here](https://github.com/JianTodo/BloggerUsage/blob/master/0017.Git%20install/Windows/5.png?raw=true)
6. 選擇 Git 編輯方式，小編使用預設值，點選「Next」<br/>![enter image description here](https://github.com/JianTodo/BloggerUsage/blob/master/0017.Git%20install/Windows/6.png?raw=true)
7. 選擇新增 Repository 初始化名稱，小編使用預設值，點選「Next」<br/>![enter image description here](https://github.com/JianTodo/BloggerUsage/blob/master/0017.Git%20install/Windows/7.png?raw=true)
8. 選擇設定環境變數，點選「Next」<br/>![enter image description here](https://github.com/JianTodo/BloggerUsage/blob/master/0017.Git%20install/Windows/8.png?raw=true)
9. 點選「Next」<br/>![enter image description here](https://github.com/JianTodo/BloggerUsage/blob/master/0017.Git%20install/Windows/9.png?raw=true)
10. 點選「Next」<br/>![enter image description here](https://github.com/JianTodo/BloggerUsage/blob/master/0017.Git%20install/Windows/10.png?raw=true)
11. 點選「Next」<br/>![enter image description here](https://github.com/JianTodo/BloggerUsage/blob/master/0017.Git%20install/Windows/11.png?raw=true)
12. 點選「Next」<br/>![enter image description here](https://github.com/JianTodo/BloggerUsage/blob/master/0017.Git%20install/Windows/12.png?raw=true)
13. 點選「Next」<br/>![enter image description here](https://github.com/JianTodo/BloggerUsage/blob/master/0017.Git%20install/Windows/13.png?raw=true)
14. 點選「Next」<br/>![enter image description here](https://github.com/JianTodo/BloggerUsage/blob/master/0017.Git%20install/Windows/14.png?raw=true)
15. 點選「Install」<br/>![enter image description here](https://github.com/JianTodo/BloggerUsage/blob/master/0017.Git%20install/Windows/15.png?raw=true)
16. 等待安裝<br/>![enter image description here](https://github.com/JianTodo/BloggerUsage/blob/master/0017.Git%20install/Windows/16.png?raw=true)
17. 點選「Finish」<br/>![enter image description here](https://github.com/JianTodo/BloggerUsage/blob/master/0017.Git%20install/Windows/17.png?raw=true)
18. 安裝後，滑鼠右鍵，便可以看到「Git GUI Here」和「Git Bash Here」<br/>![enter image description here](https://github.com/JianTodo/BloggerUsage/blob/master/0017.Git%20install/Windows/18.png?raw=true)

## Mac 檔案篇
1. 根據[官網](https://sourceforge.net/projects/git-osx-installer/)提供的路徑，~~超像釣魚網站~~，點選「下載」<br/>![enter image description here](https://github.com//JianTodo/BloggerUsage/blob/master/0017.Git%20install/Mac/2.png?raw=true)
2. 等待下載<br/>![enter image description here](https://github.com//JianTodo/BloggerUsage/blob/master/0017.Git%20install/Mac/3.png?raw=true)
3. 點開剛剛下載好的 .pkg 檔案 <br/>![enter image description here](https://github.com//JianTodo/BloggerUsage/blob/master/0017.Git%20install/Mac/6.png?raw=true)
4. Mac 因為保護機制導致無法開啟==未信賴檔案==，所以需要先去「系統偏好設定」<br/>![enter image description here](https://github.com//JianTodo/BloggerUsage/blob/master/0017.Git%20install/Mac/7.png?raw=true)
5. 點選「安全性與隱私權」<br/>![enter image description here](https://github.com//JianTodo/BloggerUsage/blob/master/0017.Git%20install/Mac/8.png?raw=true)
6. 點選「強制開啟」<br/>![enter image description here](https://github.com//JianTodo/BloggerUsage/blob/master/0017.Git%20install/Mac/9.png?raw=true)
7. 點選「打開」產生 .dmg 檔案<br/>![enter image description here](https://github.com//JianTodo/BloggerUsage/blob/master/0017.Git%20install/Mac/10.png?raw=true)
8. 點開 .dmg 檔案<br/>![enter image description here](https://github.com//JianTodo/BloggerUsage/blob/master/0017.Git%20install/Mac/5.png?raw=true)
9. 開始安裝，點選「繼續」<br/>![enter image description here](https://github.com//JianTodo/BloggerUsage/blob/master/0017.Git%20install/Mac/11.png?raw=true)
10. 點選「安裝」<br/>![enter image description here](https://github.com//JianTodo/BloggerUsage/blob/master/0017.Git%20install/Mac/12.png?raw=true)
11. 輸入密碼，點選「安裝軟體」<br/> ![enter image description here](https://github.com//JianTodo/BloggerUsage/blob/master/0017.Git%20install/Mac/13.png?raw=true)
12. 安裝成功<br/>![enter image description here](https://github.com//JianTodo/BloggerUsage/blob/master/0017.Git%20install/Mac/14.png?raw=true)
13. 貼心的刪除服務<br/>![enter image description here](https://github.com//JianTodo/BloggerUsage/blob/master/0017.Git%20install/Mac/4.png?raw=true)
14. 開啟「終端機」<br/>![enter image description here](https://github.com//JianTodo/BloggerUsage/blob/master/0017.Git%20install/Mac/15.png?raw=true)
15. 確認 Git 版本<pre  class="brush:shell;">git --version</pre>![enter image description here](https://github.com//JianTodo/BloggerUsage/blob/master/0017.Git%20install/Mac/16.png?raw=true)

## Mac 指令篇
1. [官網](https://git-scm.com/download/mac)是透過 Homebrew 進行安裝，小篇之前已經分享過[Mac Install Homebrew](../../2021/06/mac-package-anager-homebrew.html)<br/>![enter image description here](https://github.com//JianTodo/BloggerUsage/blob/master/0017.Git%20install/Mac/1.png?raw=true)
2. 指令如下<pre  class="brush:shell;">#安裝 git<br/>brew install git
#安裝 git GUI<br/>brew install git-gui</pre>

## 總結
Git 原本就是 Linux 發產下的產物，在 Ubuntu 環境下完全可以看出優勢啊！！！
雖然 Git 是非常夯的分散式版本控制工具，但它指令的水也是相當深，除去安裝簡單外，根據每個開發者開發後怎麼取得遠端伺服器的程式、上傳檔案、合併、取代⋯⋯等等的指令，根據每一條支線有很多種組合方法，什麼時候該下什麼指令就是一門藝術，小編會繼續努力將 Git 語法練習並且在分享給各位 。