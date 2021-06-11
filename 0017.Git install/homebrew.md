<div  class="mdtable"></div>

<img  src="https://github.com/JianTodo/BloggerUsage/blob/master/0017.Git%20install/Mac/17.png?raw=true"  />

## 前言
Mac 系統對開發者來說很多工具還是得自己想辦法~~它很封閉的~~，甚至安裝都得從原始程式碼進行下載後編譯再進行安裝。
> 那該怎麼管理 Mac 套件呢？

**[Homebrew](https://brew.sh/)** 絕對是您最佳的選擇，該工具就像是 Linux 的  ==apt-get==  之類的工具，官網上介紹幾乎都是一行指令就可完成下載、編譯、安裝。

下面將介紹小編如何在 Mac 上安裝 Homebrew 
<!--more-->
<hr>
<div class="headline">

 - <a href="#基本安裝">基本安裝</a>
 - <a href="#No Password Install">No Password Install</a>
 - <a href="#Bash to ZSH">Bash to ZSH</a>
 - <a href="#總結">總結</a>
</div>
<hr>

## 基本安裝

<pre  class="brush:shell;">
	/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
</pre>
開啟終端機輸入上面一行，並且輸入密碼就搞定了!!! 但是小編沒有設定密碼，所以要比較麻煩來處理一下◦

> 以下將介紹[沒有密碼怎麼安裝](https://docs.brew.sh/Installation#untar-anywhere)

## No Password Install

1. 開啟終端機，輸入下面語法
<pre  class="brush:shell;">
	mkdir homebrew && curl -L https://github.com/Homebrew/brew/tarball/master | tar xz --strip 1 -C homebrew
</pre>
2. 準備加入「**==$PATH==**」，但小編不是很確定路徑位置，所以先根據下載位置先找到 **brew 執行檔** ，例如小編開啟終端機預設是使用者/charlesjian/==homebrew/bin==

![enter image description here](https://github.com/JianTodo/BloggerUsage/blob/master/0017.Git%20install/Mac/18.png?raw=true)

3. 點選 「**brew 執行檔**」，PATH 需要新增 ==/Users/charlesjian/homebrew/bin/brew==
	![enter image description here](https://github.com/JianTodo/BloggerUsage/blob/master/0017.Git%20install/Mac/19.png?raw=true)

4. 加入 $PATH 
	1. 開啟終端機，輸入下述語法
	<pre  class="brush:shell;">
		vi ~/.bash_profile
	</pre>		
	![enter image description here](https://github.com/JianTodo/BloggerUsage/blob/master/0017.Git%20install/Mac/20.png?raw=true)
	2. 再輸入下述語法
		==export PATH=$PATH:{剛剛下載路徑}==
	輸入完按「**==esc==**」
	最後輸入「**==:wq!==**」
		<pre  class="brush:shell;">
		export PATH=$PATH:/Users/charlesjian/homebrew/bin/brew
	</pre>	
	
	![enter image description here](https://github.com/JianTodo/BloggerUsage/blob/master/0017.Git%20install/Mac/21.png?raw=true)
	3. 輸入下述語法，完成設定
		<pre  class="brush:shell;">
		soucre ~/.bash_profile
	</pre>
	
	![enter image description here](https://github.com/JianTodo/BloggerUsage/blob/master/0017.Git%20install/Mac/22.png?raw=true)
	
5. ==請**另開**終端機==，輸入下述語法確認儲存成功
		<pre  class="brush:shell;">
		echo $PATH
		brew -v
	</pre>
	
![enter image description here](https://github.com/JianTodo/BloggerUsage/blob/master/0017.Git%20install/Mac/23.png?raw=true)

## Bash to ZSH

小編 Mac 的終端機一直提醒建議從 bash 改成 [zsh](https://en.wikipedia.org/wiki/Z_shell)

> 在哪裡變更!?

最簡單的方法就是透過 「終端機 」> 「偏好設定 」> 「打開 Shell 的設定 」> 選擇「指令 」，並輸入 ==/bin/zsh==，如下圖
**==但這會導致原先指令無法使用!!!==**
![enter image description here](https://github.com/JianTodo/BloggerUsage/blob/master/0017.Git%20install/Mac/24.png?raw=true)

> 怎麼解決!?

只要將 第4步驟 「bash_profile」換成 「zprofile」重做一次即可

![enter image description here](https://github.com/JianTodo/BloggerUsage/blob/master/0017.Git%20install/Mac/25.png?raw=true)

## 總結
小編對 Mac 指令很陌生，所以一直卡卡的，好在都有解掉，都怪小編真的太不喜歡打密碼或是設定密碼，要不然應該秒安裝，也不會遇到那麼多問題，不過多學幾找還是好的，如果各位看官還有其他好解決方法，分底下留言分享，小編感謝!!!