<div class="mdtable"></div>
<img src="https://github.com/JianTodo/BloggerUsage/blob/master/0003.Blog%20%E7%A8%8B%E5%BC%8F%E7%A2%BC%E9%A1%AF%E7%A4%BA/Icon.png?raw=true" style="display: none; width: 0px;" />

## 前言

> Google Search : Read Code in Blog With Syntax-Highlighter 

部落格`Blog`該如何展示美觀又看得順眼的程式 **?**
<!--more-->
老實說這問題困擾小編蠻久
關鍵字一直不知道一直不知該如何下手
**Google**發現原來是要搜尋==程式碼提高亮度==
市面上還蠻多種選擇
小編決定使用[**SyntaxHighlighter 3.0.83**](http://alexgorbatchev.com/SyntaxHighlighter/)
透過Blogger的`JavaScript(.js)`載入即可
[**載點**](https://github.com/syntaxhighlighter/syntaxhighlighter)

> 缺點：~~就是載入速度慢了點(是我的錯覺!?)~~

<hr>
<div class="headline">
 
 - <a href="#上傳教學">上傳教學</a>
    1. <a href="#google協作平台">Google協作平台</a>
    2. <a href="#github">GitHub</a>
 - <a href="#部落格教學">部落格教學</a>
    1. <a href="#googlePl">Google協作平台</a>
    2. <a href="#GitHubPl">GitHub</a>
 - <a href="#使用教學">使用教學</a>
 - <a href="#總結">總結</a>
</div>
<hr>

# 上傳教學
SyntaxHighlighter `JavaScript(.js)` 最好放置在自己的空間，例如自己掛載的主機或是代管主機以下將透過網路空間來說明。~~當然還有很多種方式...~~

**以下介紹兩種儲存空間方式:**

 1. [Google協作平台](https://sites.google.com/)
 2. [GitHub](https://github.com/)
 
 ## 1. Google協作平台
 
 1. 建立協作平台==選用傳統板==~~新版不太會用~~
![enter image description here](https://github.com/JianTodo/BloggerUsage/blob/master/0003.Blog%20%E7%A8%8B%E5%BC%8F%E7%A2%BC%E9%A1%AF%E7%A4%BA/1.png?raw=true)
2. 協作平台命名建立
    > 1. 命名規則會有提示
    > 2. 不能和全世界撞名
    
    ![enter image description here](https://github.com/JianTodo/BloggerUsage/blob/master/0003.Blog%20%E7%A8%8B%E5%BC%8F%E7%A2%BC%E9%A1%AF%E7%A4%BA/2.png?raw=true)
 3. 進入管理平台
    ![enter image description here](https://github.com/JianTodo/BloggerUsage/blob/master/0003.Blog%20%E7%A8%8B%E5%BC%8F%E7%A2%BC%E9%A1%AF%E7%A4%BA/3.jpg?raw=true)
4. 上傳所有`Javascript(.js)`與`CSS(.css)`檔案
    ![enter image description here](https://github.com/JianTodo/BloggerUsage/blob/master/0003.Blog%20%E7%A8%8B%E5%BC%8F%E7%A2%BC%E9%A1%AF%E7%A4%BA/4.jpg?raw=true)

## 2. GitHub
1. 建立GitHub帳號
2. 點選Repositories，再點選New
    >**[小編的GitHb]([https://github.com/JianTodo](https://github.com/JianTodo))**
    
    ![enter image description here](https://github.com/JianTodo/BloggerUsage/blob/master/0003.Blog%20%E7%A8%8B%E5%BC%8F%E7%A2%BC%E9%A1%AF%E7%A4%BA/5.png?raw=true)
3. 設定Repositorory name與`Public`即可建立
   **注意以下兩點:**
   1. Repository name : ==[Owner].github.io==
      - 小編為範例: JianTodo.github.io 
    2.  一定要選擇==Public==才可以公開連線

   ![enter image description here](https://github.com/JianTodo/BloggerUsage/blob/master/0003.Blog%20%E7%A8%8B%E5%BC%8F%E7%A2%BC%E9%A1%AF%E7%A4%BA/11.png?raw=true)
4. 進入剛剛建立的Repositorory點選==uploading an existing files.==
  ![enter image description here](https://github.com/JianTodo/BloggerUsage/blob/master/0003.Blog%20%E7%A8%8B%E5%BC%8F%E7%A2%BC%E9%A1%AF%E7%A4%BA/7.png?raw=true)
5. 上傳結果
   ![enter image description here](https://github.com/JianTodo/BloggerUsage/blob/master/0003.Blog%20%E7%A8%8B%E5%BC%8F%E7%A2%BC%E9%A1%AF%E7%A4%BA/8.png?raw=true)

> 根據Github[官方文件](https://help.github.com/en/github/working-with-github-pages/about-github-pages)的使用限制如下：
> 1. 一個目錄的檔案存放上限為 1GB
> 2. 流量限制為 1 個月 100GB 

# 部落格教學
在使用之前要先在部落格上面加入一些==程式==
以下為**Google Blogger**為例
1. 登入部落格點選主題，再點選`⋮`，選擇**編輯HTML**
    ![enter image description here](https://github.com/JianTodo/BloggerUsage/blob/master/0003.Blog%20%E7%A8%8B%E5%BC%8F%E7%A2%BC%E9%A1%AF%E7%A4%BA/9.png?raw=true)
2. 搜尋`</body>`
   > 要點選至編輯內文再按下`Ctrl`+`F`搜尋
  
    ![enter image description here](https://github.com/JianTodo/BloggerUsage/blob/master/0003.Blog%20%E7%A8%8B%E5%BC%8F%E7%A2%BC%E9%A1%AF%E7%A4%BA/10.png?raw=true)
3. body上方需加入上傳檔案鏈結
    - <div id="googlePl"><strong>Google協作平台</strong></div>
 
        ==可以直接用小編或是取代==https://sites.google.com/site/`blogcodecss`
       	<pre class="brush:html;">
	  &lt;body&gt;
	  ...
	  ...
      &lt;!--必要檔案--&gt;
      &lt;link href='https://sites.google.com/site/blogcodecss/shCore.css' rel='stylesheet' type='text/css'/&gt;
      &lt;link href='https://sites.google.com/site/blogcodecss/shThemeDefault.css' rel='stylesheet' type='text/css'/&gt;
      &lt;script src='https://sites.google.com/site/blogcodecss/shCore.js' type='text/javascript'&gt;&lt;/script&gt;
      &lt;script src='https://sites.google.com/site/blogcodecss/shLegacy.js' type='text/javascript'&gt;&lt;/script&gt;
      &lt;script src='https://sites.google.com/site/blogcodecss/shAutoloader.js' type='text/javascript'&gt;&lt;/script&gt;
      &lt;!-- 我是分隔線 --&gt;
      &lt;script src='https://sites.google.com/site/blogcodecss/shBrushXml.js' type='text/javascript'&gt;&lt;/script&gt;
      &lt;script src='https://sites.google.com/site/blogcodecss/shBrushSql.js' type='text/javascript'&gt;&lt;/script&gt;
      &lt;script src='https://sites.google.com/site/blogcodecss`/shBrushPython.js' type='text/javascript'&gt;&lt;/script&gt;
      &lt;script src='https://sites.google.com/site/blogcodecss/shBrushPhp.js' type='text/javascript'&gt;&lt;/script&gt;
      &lt;script src='https://sites.google.com/site/blogcodecss/shBrushJScript.js' type='text/javascript'&gt;&lt;/script&gt;
      &lt;script src='https://sites.google.com/site/blogcodecss/shBrushJava.js' type='text/javascript'&gt;&lt;/script&gt;
      &lt;script src='https://sites.google.com/site/blogcodecss/shBrushCss.js' type='text/javascript'&gt;&lt;/script&gt;
      &lt;script src='https://sites.google.com/site/blogcodecss/shBrushCSharp.js' type='text/javascript'&gt;&lt;/script&gt;
      &lt;script src='https://sites.google.com/site/blogcodecss/shBrushCpp.js' type='text/javascript'&gt;&lt;/script&gt;
      &lt;script src='https://sites.google.com/site/blogcodecss/shBrushBash.js' type='text/javascript'&gt;&lt;/script&gt;
      &lt;!--必要程式--&gt;
      &lt;script type='text/javascript'&gt;
          SyntaxHighlighter.all();
      &lt;/script&gt;
	  &lt;/body&gt;
	  </pre>

   - <div id="GitHubPl"><strong>GitHub</strong></div>

        ==可以直接用小編的或是**原作者**==
       	<pre class="brush:html;">
	  &lt;body&gt;
	  ...
	  ...
      &lt;!--必要檔案--&gt;
      &lt;link href='https://jiantodo.github.io/SyntaxHighlighter/shCore.css' rel='stylesheet' type='text/css'/&gt;
      &lt;link href='https://jiantodo.github.io/SyntaxHighlighter/shThemeDefault.css' rel='stylesheet' type='text/css'/&gt;
      &lt;script src='https://jiantodo.github.io/SyntaxHighlighter/shCore.js' type='text/javascript'&gt;&lt;/script&gt;
      &lt;script src='https://jiantodo.github.io/SyntaxHighlighter/shLegacy.js' type='text/javascript'&gt;&lt;/script&gt;
      &lt;script src='https://jiantodo.github.io/SyntaxHighlighter/shAutoloader.js' type='text/javascript'&gt;&lt;/script&gt;
      &lt;!-- 我是分隔線 --&gt;
      &lt;script src='https://jiantodo.github.io/SyntaxHighlighter/shBrushXml.js' type='text/javascript'&gt;&lt;/script&gt;
      &lt;script src='https://jiantodo.github.io/SyntaxHighlighter/shBrushSql.js' type='text/javascript'&gt;&lt;/script&gt;
      &lt;script src='https://jiantodo.github.io/SyntaxHighlighter/shBrushPython.js' type='text/javascript'&gt;&lt;/script&gt;
      &lt;script src='https://jiantodo.github.io/SyntaxHighlighter/shBrushPhp.js' type='text/javascript'&gt;&lt;/script&gt;
      &lt;script src='https://jiantodo.github.io/SyntaxHighlighter/shBrushJScript.js' type='text/javascript'&gt;&lt;/script&gt;
      &lt;script src='https://jiantodo.github.io/SyntaxHighlighter/shBrushJava.js' type='text/javascript'&gt;&lt;/script&gt;
      &lt;script src='https://jiantodo.github.io/SyntaxHighlighter/shBrushCss.js' type='text/javascript'&gt;&lt;/script&gt;
      &lt;script src='https://jiantodo.github.io/SyntaxHighlighter/shBrushCSharp.js' type='text/javascript'&gt;&lt;/script&gt;
      &lt;script src='https://jiantodo.github.io/SyntaxHighlighter/shBrushCpp.js' type='text/javascript'&gt;&lt;/script&gt;
      &lt;script src='https://jiantodo.github.io/SyntaxHighlighter/shBrushBash.js' type='text/javascript'&gt;&lt;/script&gt;
      &lt;!--必要程式--&gt;
      &lt;script type='text/javascript'&gt;
          SyntaxHighlighter.all();
      &lt;/script&gt;
	  &lt;/body&gt;
	  </pre>
      
# 使用教學   
[SyntaxHighlighter*套件使用說明*](http://alexgorbatchev.com/SyntaxHighlighter/manual/brushes/)

==brush 對照表如下==
| **語言名稱** | **Brush aliases** | **File name** |
|:--|:--:|:--|
|ActionScript3	|as3<br>actionscript3	                |shBrushAS3.js       |
|Bash/shell	    |bash, shell	                    |shBrushBash.js      |
|ColdFusion	    |cf<br>coldfusion	                |shBrushColdFusion.js    |  
|C#	            |c-sharp<br>csharp	                |shBrushCSharp.js    |  
|C++	            |cpp<br> c	                        |shBrushCpp.js       |
|CSS	            |css	                            |shBrushCss.js   |  
|Delphi	        |delphi<br>pas<br>pascal	            |shBrushDelphi.js    |
|Diff	        |diff<br>patch	                    |shBrushDiff.js      |
|Erlang	        |erl<br>erlang	                    |shBrushErlang.js    |
|Groovy	        |groovy	                        |shBrushGroovy.js        |  
|JavaScript	    |js<br>jscript<br>javascript	        |shBrushJScript.js   |  
|Java	        |java	                        |shBrushJava.js          |   
|JavaFX	        |jfx<br>javafx	                    |shBrushJavaFX.js    |     
|Perl	        |perl<br>pl	                    |shBrushPerl.js          |  
|PHP	            |php	                            |shBrushPhp.js   | 
|Plain Text	    |plain<br>text	                    |shBrushPlain.js     |    
|PowerShell	    |ps<br>powershell	                |shBrushPowerShell.js    |    
|Python	        |py<br>python	                    |shBrushPython.js        |     
|Ruby	        |rails<br>ror<br>ruby	            |shBrushRuby.js          |     
|Scala	        |scala	                        |shBrushScala.js         |   
|SQL	            |sql	                            |shBrushSql.js   |    
|Visual Basic	|vb<br>vbnet	                    |shBrushVb.js            |        
|XML	            |xml<br>xhtml<br>xslt<br>html<br> xhtml	|shBrushXml.js       | 


**使用方式如下:**(範例為`C#`)
```Html
<pre class="brush:csharp">
<!--程式碼-->
</pre>
```
**實作結果如下**
<pre class="brush:csharp">
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
 
namespace SyntaxHighlighter
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Hello World");
            Console.ReadKey();
        }
    }
}
</pre>
# 總結
老實說現在支援程式碼亮度有很多套
但我還是最喜歡==SyntaxHighlighter 3.0.83==
~~其他程式碼亮度小編也會混著用~~
雖然SyntaxHighlighter有些很麻煩的地方
日後小編已改至心目中最理想的狀態
再分享給大家
