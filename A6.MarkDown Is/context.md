<div class="mdtable"></div>
<img src="https://github.com/JianTodo/BloggerUsage/blob/master/A6.MarkDown%20Is/0.png?raw=true" />

## 前言
**MD 副檔名的檔案 是什麼呢？**
> MD 副檔名全名為 [Markdown](https://en.wikipedia.org/wiki/Markdown)，
	是一種「輕量級」標記式語言，
	終極目標就是讓**讀寫**更加方便。
	
下面將介紹小編常使用的指令
<!--more-->
> 範例列表

以下列表皆會按照「==範例==」順序來 Demo 「==結果==」。
<hr>
<div class="headline">

- <a href="標題">標題</a>
- <a href="文字">文字</a>
- <a href="項目">項目</a>
- <a href="外部連結">外部連結</a>
- <a href="程式碼">程式碼</a>
- <a href="表格">表格</a>
- <a href="其他">其他</a>
</div>
<hr>

## 標題
- 範例
	<pre class="brush:shell;">
	// H1 文字大小
	# Size H1
	// H2 文字大小
	## Size H2
	// H6 文字大小
	###### Size H6
	</pre>
- 結果
	# Size H1

	## Size H2

	###### Size H6
	
## 文字
- 範例
	<pre class="brush:shell;">
	// 斜體
	_emphasize_
	// 粗體
	*Strong*
	// 黃色字體
	==Yellow text.==
	// 刪除體
	~~Mistaken text.~~
	// 區塊
	> Quoted text.
	</pre>
- 結果
	_emphasize_
	**Strong**  
	==Yellow text.==
	~~Mistaken text.~~
	> Quoted text.
## 項目
- 範例 1
	<pre class="brush:shell;">
	- Item
		 * Item
			 + Item
	</pre>
- 結果 1
	- Item
		 * Item
			 + Item
- 範例 2
	<pre class="brush:shell;">
	1. Item1
	2. Item2
	</pre>
- 結果 2
	1. Item1
	2. Item2
- 範例 3
	<pre class="brush:shell;">
	- [ ] Non-Done item
	- [x] Done item
	</pre>
- 結果 3
	- [ ] Non-Done item
	- [x] Done item
## 外部連結
- 範例 1
	<pre class="brush:shell;">
	[Google](https://www.google.com)
	</pre>
- 結果 1
	[Google](https://www.google.com)
- 範例 2
	<pre class="brush:shell;">
	![MarkDown Image](https://github.com/JianTodo/BloggerUsage/blob/master/A6.MarkDown%20Is/0.png?raw=true)
	</pre>
- 結果 2
![MarkDown Image](https://github.com/JianTodo/BloggerUsage/blob/master/A6.MarkDown%20Is/0.png?raw=true)
## 程式碼
- 範例
	<pre class="brush:csharp;">
	// Hello World String
	var str= "Hello World";
	</pre>
- 結果
	```
	// Hello World String
	
	var str= "Hello World";
	```
## 表格
- 範例
	<pre class="brush:shell;">
	| 標題 1  | 標題 2 |  標題 3 |
	|:------:|:-------|-------:|
	|   置中  |  置左  |   置右  |
	</pre>
- 結果
	| 標題 1 | 標題 2 | 標題 3 |
	|:--------:|:--------|--------:|
	| 置中| 置左 | 置右 |
## 其他
- 範例 - 下底線
	<pre class="brush:shell;">
	**&lt;u&gt;下底&lt;/u&gt;**==線==
	</pre>
- 結果 - 下底線
	**<u>下底</u>**==線==
## 總結
小編以前寫 Blogger 都是直接使用 HTML 與 CSS，
每每寫一篇可能必須花3~7天，
曾經苦苦尋找能否有更快速的撰寫範例或規範，
但是都沒有很大的效果，
直到 MD 的出現，彷彿看到救星一般，
此 Blogger 也陸續全面改用 MD 編寫，
效率真的是快了不少，
而且很多大廠牌也將說明檔改為 MD，
一舉兩得!!!非常推薦大家一起使用。