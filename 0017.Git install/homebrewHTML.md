<div class="mdtable"></div>
<img src="https://github.com/JianTodo/BloggerUsage/blob/master/0017.Git%20install/Mac/17.png?raw=true">
<h2 id="前言">前言</h2>
<p>Mac 系統對開發者來說很多工具還是得自己想辦法<s>它很封閉的</s>，甚至安裝都得從原始程式碼進行下載後編譯再進行安裝。</p>
<blockquote>
<p>那該怎麼管理 Mac 套件呢？</p>
</blockquote>
<p><strong><a href="https://brew.sh/">Homebrew</a></strong> 絕對是您最佳的選擇，該工具就像是 Linux 的  <mark>apt-get</mark>  之類的工具，官網上介紹幾乎都是一行指令就可完成下載、編譯、安裝。</p>
<p>下面將介紹小編如何在 Mac 上安裝 Homebrew</p>
<!--more-->
<hr>
<div class="headline">
</div><ul>
<li><a href="#基本安裝">基本安裝</a></li>
<li><a href="#No Password Install">No Password Install</a></li>
<li><a href="#Bash to ZSH">Bash to ZSH</a></li>
<li><a href="#總結">總結</a></li>
</ul>

<hr>
<h2 id="基本安裝">基本安裝</h2>
<pre class="brush:shell;">	/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
</pre>
<p>開啟終端機輸入上面一行，並且輸入密碼就搞定了!!! 但是小編沒有設定密碼，所以要比較麻煩來處理一下◦</p>
<blockquote>
<p>以下將介紹<a href="https://docs.brew.sh/Installation#untar-anywhere">沒有密碼怎麼安裝</a></p>
</blockquote>
<h2 id="no-password-install">No Password Install</h2>
<ol>
<li>開啟終端機，輸入下面語法 <pre class="brush:shell;"> mkdir homebrew &amp;&amp; curl -L https://github.com/Homebrew/brew/tarball/master | tar xz --strip 1 -C homebrew
</pre></li>
</ol>

<ol start="2">
<li>
<p>準備加入「<strong><mark>$PATH</mark></strong>」，但小編不是很確定路徑位置，所以先根據下載位置先找到 <strong>brew 執行檔</strong> ，例如小編開啟終端機預設是使用者/charlesjian/<mark>homebrew/bin</mark></p>
<p><img src="https://github.com/JianTodo/BloggerUsage/blob/master/0017.Git%20install/Mac/18.png?raw=true" alt="enter image description here"></p>
</li>
<li>
<p>點選 「<strong>brew 執行檔</strong>」，PATH 需要新增 <mark>/Users/charlesjian/homebrew/bin/brew</mark><br>
<img src="https://github.com/JianTodo/BloggerUsage/blob/master/0017.Git%20install/Mac/19.png?raw=true" alt="enter image description here"></p>
</li>
<li>
<p>加入 $PATH</p>
<ol>
<li>開啟終端機，輸入下述語法 <pre class="brush:shell;"> vi ~/.bash_profile
</pre>
<img src="https://github.com/JianTodo/BloggerUsage/blob/master/0017.Git%20install/Mac/20.png?raw=true" alt="enter image description here">
</li>
</ol>
<ol start="2">
<li>
<p>再輸入下述語法<br>
<mark>export PATH=$PATH:{剛剛下載路徑}</mark><br>
輸入完按「<strong><mark>esc</mark></strong>」<br>
最後輸入「<strong><mark>:wq!</mark></strong>」</p>
 <pre class="brush:shell;"> export PATH=$PATH:/Users/charlesjian/homebrew/bin/brew
</pre>
<img src="https://github.com/JianTodo/BloggerUsage/blob/master/0017.Git%20install/Mac/21.png?raw=true" alt="enter image description here">
</li>
</ol>
<ol start="3">
<li>輸入下述語法，完成設定 <pre class="brush:shell;"> soucre ~/.bash_profile
</pre>
<img src="https://github.com/JianTodo/BloggerUsage/blob/master/0017.Git%20install/Mac/22.png?raw=true" alt="enter image description here">
</li>
</ol>

</li>
<li>
<p><mark>請<strong>另開</strong>終端機</mark>，輸入下述語法確認儲存成功<br>
</p><pre class="brush:shell;">
echo $PATH
brew -v
</pre><p></p>
<p><img src="https://github.com/JianTodo/BloggerUsage/blob/master/0017.Git%20install/Mac/23.png?raw=true" alt="enter image description here"></p>
</li>
</ol>
<h2 id="bash-to-zsh">Bash to ZSH</h2>
<p>小編 Mac 的終端機一直提醒建議從 bash 改成 <a href="https://en.wikipedia.org/wiki/Z_shell">zsh</a></p>
<blockquote>
<p>在哪裡變更!?</p>
</blockquote>
<p>最簡單的方法就是透過 「終端機 」&gt; 「偏好設定 」&gt; 「打開 Shell 的設定 」&gt; 選擇「指令 」，並輸入 <mark>/bin/zsh</mark>，如下圖<br>
<strong><mark>但這會導致原先指令無法使用!!!</mark></strong><br>
<img src="https://github.com/JianTodo/BloggerUsage/blob/master/0017.Git%20install/Mac/24.png?raw=true" alt="enter image description here"></p>
<blockquote>
<p>怎麼解決!?</p>
</blockquote>
<p>只要將 第4步驟 「bash_profile」換成 「zprofile」重做一次即可</p>
<p><img src="https://github.com/JianTodo/BloggerUsage/blob/master/0017.Git%20install/Mac/25.png?raw=true" alt="enter image description here"></p>
<h2 id="總結">總結</h2>
<p>小編對 Mac 指令很陌生，所以一直卡卡的，好在都有解掉，都怪小編真的太不喜歡打密碼或是設定密碼，要不然應該秒安裝，也不會遇到那麼多問題，不過多學幾找還是好的，如果各位看官還有其他好解決方法，分底下留言分享，小編感謝!!!</p>
