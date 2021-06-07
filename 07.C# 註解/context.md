<div class="mdtable"></div>
<img src="https://github.com/JianTodo/BloggerUsage/blob/master/07.C%23%20%E8%A8%BB%E8%A7%A3/icon.png?raw=true"  />

## 前言
華語是小編母系語言
常看到變數名稱有以下兩種模式 **:**
   1. 跳躍式 ==英文醬用也OK==
   2. 無意義 ==資安防護==

為了降低維運成本
與確保撰寫人員與自己想法一致
當然 **!** 註解最好*寫好寫滿*
~~Clean Code 反倒是不寫註解!?~~
<!--more-->

## 基本
1.  #### 單行註解
	<pre class="brush:csharp;highlight:[4];">
	...
	static void Main(string[] args)
	{
		// 歡迎
		Console.WriteLine("Hello World");
	    Console.ReadKey();
	}
	...
	</pre>
2. #### 區塊註解
	<pre class="brush:csharp;highlight:[4,5];">
	...
	static void Main(string[] args)
	{
		/* 歡迎
		 * 世界
		*/
		Console.WriteLine("Hello World");
	    Console.ReadKey();
	}
	...
	</pre>

## 進階
1. #### 文件標籤
	> VS 快捷鍵`///`
	<pre class="brush:csharp;highlight:[2,3,4,5,6];">
	...
	/// <summary>
	/// 
	/// </summary>
	/// <param name="args"></param>
	/// <returns></returns>
	static int Main(string[] args)
	{
		Console.WriteLine("Hello World");
	    Console.ReadKey();
		return 0;
	}
	...
	</pre>
	- 主要標籤
		- `<summary>` 標籤主體，簡易描述
		- `<param>` 描述方法參數，==必須有參數==
		- `<remarks>` 備註，物件(class)無效
		- `<returns>` 回傳資訊，==必須有回傳==
		- `<exception>` 錯誤資訊
		- `<include>` 引用外部XML
		- `<value>` 屬性描述
		> 主要標籤通常是滑鼠移動至目標物件顯示內容
		> 如下圖
	- 輔助標籤
		- `<para>` 換行
		- `<c>` 粗體，中文沒效果
		- `<example>` 程式範例，`<code>`混合使用
		- `<list>` 列表，`<listheader>`&`<term>`&`<Description>`混合使用
		> 撰寫程式**當下**主要會看到輔助標籤內容
		> 輔助標籤會出現在`<summary>`內容中，範例
		`<summary>`
		測試
		`<para>` `<c>`測試`</c>` `</para>` 
		`</summary>`
		> 如下圖
	
2. #### 識別碼
參考:[https://docs.microsoft.com/zh-tw/dotnet/csharp/language-reference/language-specification/documentation-comments#permission](https://docs.microsoft.com/zh-tw/dotnet/csharp/language-reference/language-specification/documentation-comments#permission)