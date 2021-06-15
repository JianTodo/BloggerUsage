
<div  class="mdtable"></div>

<img  src="https://github.com/JianTodo/BloggerUsage/blob/master/0011.Angular%20Install/0.png?raw=true"  />

  

## 前言

>**Angular 是什麼呢？**

是一個基於 [TypeScript](https://en.wikipedia.org/wiki/TypeScript) 的 開源 Web 應用框架，
由 Google 的 [Angular](https://zh.wikipedia.org/wiki/Angular) 團隊以及社群共同領導

  

>**Angular vs AngularJS**

AngularJS 是 Angular 之前出的版本

整體架構差別相當多，為了區別兩者從 2.0 開始將 JS 移除，市面上所指的純前端皆是 Anuglar，目前也推出了 11.0，Angular更新也相當快。

基礎底層也是由 2.0 出發，~~雖然更新幅度都沒有很大，小編都很猶豫要不要學~~

下面將介紹小編使用的步驟

<!--more-->
<hr>
<div class="headline">


  - <a href="#步驟">步驟</a>
  - <a href="#總結">總結</a>
</div>
<hr>

## 步驟

1. 安裝 [Node.js](../2021/06/nodejs-install.html#more)
2. 安裝Angular Cli，開啟 cmd 輸入以下指令<br/><pre  class="brush:shell;">npm install -g @angular/cli</pre><br/>![enter image description here](https://github.com/JianTodo/BloggerUsage/blob/master/0011.Angular%20Install/1.png?raw=true)
3. 安裝完成<br/>![enter image description here](https://github.com/JianTodo/BloggerUsage/blob/master/0011.Angular%20Install/2.png?raw=true)
4. 再次確認 Node.js 版本與 npm 版本<br/><pre  class="brush:shell;">node -v
npm -v</pre><br/>![enter image description here](https://github.com/JianTodo/BloggerUsage/blob/master/0011.Angular%20Install/3.png?raw=true)
5. 建立 **AngularApp** 資料夾<br/>==進入== **AngularApp** 資料夾<br/>輸入新增 **MyApp** 專案<br/>命令模式會問你是否加入Angular專案，**輸入 `y`**<br/><pre  class="brush:shell;">mkdir AngularApp
cd AngularApp
ng new MyApp</pre>![enter image description here](https://github.com/JianTodo/BloggerUsage/blob/master/0011.Angular%20Install/4.png?raw=true)
6. 小編選用 CSS，按下 `Enter`<br/>![enter image description here](https://github.com/JianTodo/BloggerUsage/blob/master/0011.Angular%20Install/5.png?raw=true)
7. 等待專案完成<br/>![enter image description here](https://github.com/JianTodo/BloggerUsage/blob/master/0011.Angular%20Install/6.png?raw=true)
8. 新增專案完成<br/>![enter image description here](https://github.com/JianTodo/BloggerUsage/blob/master/0011.Angular%20Install/7.png?raw=true)
9. 進入專案資料夾 **MyApp**<br/>啟動專案<br/><pre  class="brush:shell;">cd MyApp
ng serve --open</pre><br/>![enter image description here](https://github.com/JianTodo/BloggerUsage/blob/master/0011.Angular%20Install/8.png?raw=true)
10. 預設瀏覽器會自動啟動，Angular ==預設== http://localhost:4200<br/>![enter image description here](https://github.com/JianTodo/BloggerUsage/blob/master/0011.Angular%20Install/9.png?raw=true)
11. ctrl + c 並輸入 `y` 可以停止服務<br/>![enter image description here](https://github.com/JianTodo/BloggerUsage/blob/master/0011.Angular%20Install/10.png?raw=true)

## 總結

小編一向都以全端自居，也曾試過寫 AngularJS，
當時 AngularJS 剛出，練習過幾個小 Project，但一直對它印象沒有很好，忽然它更新為「`純前端`」
**有種很不習慣感!!!** 
除了每次都要 Build 很久以外，對 SEO 也不太友善~~畢竟是 Client Side Random~~，也讓學習成本也變高，或許開發速度可能變快，但小編 Debug 速度反而變慢，說不定小編...
**==喔!!!小編承認自己很不擅長前端==**
~~但是小編的 JQuery 還可以阿~~
希望未來純前端能寫得越來越順。