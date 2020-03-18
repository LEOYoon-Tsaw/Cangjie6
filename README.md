## 蒼頡檢字法〔Cangjie6〕

1. This is a Chinese input method(Cangjie, 6th edition) based on Rime input engine
2. `cangjie6.schema.yaml` is the configuration file, `cangjie6.dict.yaml` is the charactor encoding list, `cangjie6.extended.dict.yaml` is the phrase list, and `cangjie6.extsimp.dict.yaml` is the phrase list of simplified Chinese.
3. To personalise, follow instructions in `cangjie6.schema.yaml`

---
1. 本方案爲爲 Rime 輸入法引擎所製蒼頡檢字法輸入方案
2. `cangjie6.schema.yaml`爲方案配置文檔，`cangjie6.dict.yaml`爲蒼頡檢字法字表，`cangjie6.extended.dict.yaml`爲詞表，`cangjie6.extsimp.dict.yaml`爲簡體詞表
3. 如需更改默認配置，請循`cangjie6.schema.yaml`中註釋進行

## 蒼頡·快打模式〔Cangjie6 Express〕

1. Express mode is a mode of character-by-character typing with automatique word selection
2. `cangjie6_express.schema.yaml` is the configuration file, and `cangjie6.dict.yaml` is the charactor encoding list
3. To personalise, follow instructions in `cangjie6_express.schema.yaml`

---
1. 快打模式爲單字自動上屛模式
2. `cangjie6_express.schema.yaml`爲方案配置文檔，`cangjie6.dict.yaml`爲蒼頡檢字法字表
3. 如需更改默認配置，請循`cangjie6_express.schema.yaml`中註釋進行

## 使用方法〔How to use〕
<ol><li>Download <a href="https://rime.im">Rime</a></li>
<li>Clone or download the schema files from this repository, relocate the files to Rime's user folder:</li>
<br /><small><ul>
<code>MacOS X</code>: ~/Library/Rime<br />
<code>Windows</code>: User_Direction\AppData\Roaming\Rime
</small></ul>
<li>Add</li>
<pre>patch:
  schema_list:
    - schema: cangjie6
    - schema: cangjie6_express</pre>
to <code>default.custom.yaml</code> in Rime's user folder.
<li>Deploy. Then press <code>control</code>+<code>`</code> and choose Cangjie6 or Cangjie6 Express to start to use.</li></ol>

<hr>
<ol><li>下載<a href="https://rime.im">中州韻輸入法引擎</a></li>
<li>克隆或下載此中檔案，將下載的文件放入【用戶檔案夾】：</li>
<br /><small><ul>
<code>MacOS X</code>: ~/Library/Rime (鼠鬚管狀態欄選單中的「用戶文檔…」)<br />
<code>Windows</code>: User_Direction\AppData\Roaming\Rime (開始→所有程式→小狼毫→用戶檔案夾)
</small></ul>
<li>在<code>default.custom.yaml</code>中加入：
<pre>patch:
  schema_list:
    - schema: cangjie6  # 蒼頡檢字法
    - schema: cangjie6_express  # 蒼頡·快打模式
</pre>
<li>重新佈署後用<code>Control</code>+<code>`</code> 或 <code>F4</code> (僅 Windows) 叫出〔方案選單〕，選中「蒼頡檢字法」或「蒼頡·快打模式」。
</ol>
