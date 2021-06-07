<div class="mdtable"></div>
<img src="https://github.com/JianTodo/BloggerUsage/blob/master/02.CSharp%E5%91%BD%E5%90%8D%E5%89%8D%E7%B6%B4%E5%AD%97/NamingPrefix.png?raw=true" style="display: none; width: 0px;" />


## 前言
>程式撰寫難免會遇到**取名**上的問題...`嘆~`
>取名真的<span style="color:red;">難!!!</span>
>以下參考整理由Google神人搜尋：程式縮寫

通常取名會有以下兩種準則:
 1. Perfix 前綴字
    : **EX  :** 按鈕 ->  Button -> btn
 2. 有意義物件名稱
    : **EX :** 儲存 -> Save

**以下只針對`Perfix`駱駝峰式寫法提供參考 :**
~~(寫久了就會習慣)~~
<!--more-->
<hr>
<div class="headline">
 
 - <a href="#基本">基本</a>
 - <a href="#asp.net">ASP.NET</a>
    - <a href="#標準">標準</a>
    - <a href="#資料">資料</a>
    - <a href="#驗證樹狀結構報表">驗證/樹狀結構/報表</a>
    - <a href="#帳號相關">帳號相關</a>
    - <a href="#webparts">WebParts</a>
    - <a href="#html">HTML</a>
    - <a href="#ado.net">ADO.NET</a>
 - <a href="#windows-form-winform">Windows Form`WinForm`</a>
</div>
<hr>

## 基本
>
>
<div class="noth"></div>

|    |    |    |    |    |   |
|:--:|:--:|:--:|:--:|:--:|:--:|
|**Original**|string|int    |char |sbyte|byte  |
|**Perfix**  |str   |i      |chr  |sb   |bt    |
|**Original**|uint  |long   |ulong|float|double|
|**Perfix**  |ui    |l      |ul   |f    |d     |
|**Original**|bool  |decimal|     |     |      |
|**Perfix**  |b     |dec    |     |     |      |

## ASP.NET
> ### 標準
<div class="noth"></div>

|    |    |    |    |    |   |
|:--:|:--:|:--:|:--:|:--:|:--:|
|**Original**|AdRotator   |BulletedList|Button  |Calendar|CheckBox|
|**Perfix**  |art         |blst        |btn      |cal     |chk     |
|**Original**|CheckBoxList|DropDownList|FileUpload|HiddenField|HyperLink|
|**Perfix**  |chkl    |drop      |fup   |hfld    |hlk    |
|**Original**|Image|ImageButton|ImageMap|Label|LinkButton|
|**Perfix**  |img    | ibtn    |imap     |  lbl   | lbtn|
|**Original**|ListBox|Literal|Localize|MultiView|Panel|
|**Perfix**  |lst    | ltl   |loc    |  mvw   | pnl|
|**Original**|PlaceHolder|RadioButton|Radio<br/>ButtonList|Substitution|Table|
|**Perfix**  |plh    | rad    |radl     |  subs  | tbl|
|**Original**|TextBox|View|Wizard|Xml||
|**Perfix**  |txt    | vw    |wiz     |  xml   | |
> ### 資料
<div class="noth"></div>

|||||||
|:--:|:--:|:--:|:--:|:--:|:--:|
|**Original**|Chart|DataList|DataPager|DetailsView|EnityData<br/>Source|
|**Perfix**|ch|dlst|dp|dv|eds|
|**Original**|FormView|GridView|LinqDataSource|ListView|ObjectData<br/>Source|
|**Perfix**|fv|gv|lds|lv|ods|
|**Original**|QueryExtender|Repeater|SitMapData<br/>Source|SqlData<br/>Source|XmlData<br/>Source|
|**Perfix**|qe|rpt|smds|sds|xds|
> ### 驗證/樹狀結構/報表
<div class="noth"></div>

|||||||
|:--:|:--:|:--:|:--:|:--:|:--:|
|**Original**|Compare<br/>Validator|Custom<br/>Validator|Range<br/>Validator|Regular<br/>Expression<br/>Validator|Require<br/>Field<br/>Validator|
|**Perfix**|valc|valx|valg|vale|valr|
|**Original**|Validation<br/>Summary|Menu|SiteMap|TreeView|ReportViewer|
|**Perfix**|vals|mnu|smp|trv|rpv|
> ### 帳號相關
<div class="noth"></div>

|||||||
|:--:|:--:|:--:|:--:|:--:|:--:|
|**Original**|ChangePassword|CreateUserWizard|Login|LoginName|LoginStatus|
|**Perfix**|cpwd|cuw|lgn|logn|logns|
|**Original**|LoginView|PasswordRecovery||||
|**Perfix**|lognv|pwdr||||
> ### WebParts
<div class="noth"></div>

|||||||
|:--:|:--:|:--:|:--:|:--:|:--:|
|**Original**|Appearance<br/>EditorPart|Behavior<br/>EditorPart|CatalogZone|Connections<br/>Zone|Declarative<br/>CatalogPart|
|**Perfix**|pade|pbed|zca|zcon|pdca|
|**Original**|EditorZone|Import<br/>CatalogPart|Layout<br/>EditorPart|Page<br/>CatalogPart|Property<br/>GridEditor<br/>Part|
|**Perfix**|zed|pica|pled|ppca|ppge|
|**Original**|ProxyWeb<br/>PartManager|WebPart<br/>Manager|WebPartZone|||
|**Perfix**|mpwp|mwp|zwp|||
> ### HTML
<div class="noth"></div>

|||||||
|:--:|:--:|:--:|:--:|:--:|:--:|
|**Original**|Input<br/>`Button`|Input<br/>`Reset`|Input<br/>`Submit`|Input<br/>`Text`|Input<br/>`File`|
|**Perfix**|hbtn|hrbtn|hsbtn|hitxt|hifile|
|**Original**|Input<br/>`Password`|Input<br/>`Checkbox`|Input<br/>`Radio`|Input<br/>`Hidden`|Textarea|
|**Perfix**|hpwd|hick|hir|hihd|htxta|
|**Original**|Table|Image|Select|Horizontal Rule|Div|
|**Perfix**|htab|himg|hslt|hhr|dv|

> ### ADO.NET
<div class="noth"></div>

|||||||
|:--:|:--:|:--:|:--:|:--:|:--:|
|**Original**|Connection|Command|Parameter|DataAdapter|DataReader|
|**Perfix**|conn|cmd|parm|da|dr|
|**Original**|DataSet|DataTable|DataRow|DataColumn|DataView|
|**Perfix**|ds|dt|drow|dcol|dv|

## [Windows Form `WinForm`](https://docs.microsoft.com/zh-tw/visualstudio/ide/step-1-create-a-windows-forms-application-project?view=vs-2019)
>
>
<div class="noth"></div>

|||||||
|:--:|:--:|:--:|:--:|:--:|:--:|
|**Original**|Background<br/>Worker|Binding<br/>Navigator|Binding<br/>Source|Button|CheckBox|
|**Perfix**|bgw|bdn|bds|btn|chk|
|**Original**|Checked<br/>ListBox|Color<br/>Dialog|ComboBox|Context<br/>MenuStrip|DataGridView|
|**Perfix**|clst|cdlg|cbo|cms|dgv|
|**Original**|DataSet|DataTime<br/>Picker|Directory<br/>Entry|Directory<br/>Searcher|DomainUpDown|
|**Perfix**|ds|dtp|dre|drs|dud|
|**Original**|ErrorProvider|EventLog|FileSystem<br/>Watcher|Flow<br/>Layout<br/>Panel|Folder<br/>Browser<br/>Dialog|
|**Perfix**|err|evl|fsw|flpnl|fbdlg|
|**Original**|FontDialog|GroupBox|Help<br/>Provider|HSrollBar|ImageList|
|**Perfix**|fdlg|gbx|hlp|hsb|ilst|
|**Original**|Label|LinkLabel|ListBox|ListView|MaskedTexBox|
|**Perfix**|lbl|llbl|lst|lvw|mtx|
|**Original**|MenuStrip|Message<br/>Queue|Month<br/>Calendar|NotifyIcon|Numeric<br/>UpDown|
|**Perfix**|ms|msq|cdr|icn|nud|
|**Original**|OpenFile<br/>Dialog|PageSetup<br/>Dialog|Pancel|Performance<br/>Count|PictureBox|
|**Perfix**|odlg|psd|pnl|pfc|pic|
|**Original**|PrintDialog|Print<br/>Document|Print<br/>Preview<br/>Control|Print<br/>Preview<br/>Dialog|Process|
|**Perfix**|pdlg|pdc|prv|dlg|prc|
|**Original**|ProcessBar|Progress<br/>Bar|Property<br/>Grid|RadioButton|RichTextBox|
|**Perfix**|prcb|prgb|prg|rbtn|rtf|
|**Original**|SaveFile<br/>Dialog|SerialPort|Service<br/>Controller|Spltter|StatusStrip|
|**Perfix**|sdlg|spt|scl|spl|ss|
|**Original**|TabControl|Table<br/>Layout<br/>Panel|TextBox|Timer|ToolStrip|
|**Perfix**|tctl|tlpnl|tb|tm|ts|
|**Original**|ToolStrip<br/>Container|ToolTip|TrackBar|TreeView|VScrollBar|
|**Perfix**|tsc|tip|trkb|tvw|vsb|
|**Original**|WebBrowser|||||
|**Perfix**|wbs|||||

> 如有錯或是要補充請留言**謝謝!!!**
