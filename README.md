# TUSB_Patch

PonponのThe Unusual SkyBlock 二次創作物置き場です！  
主に1コマンドパッチを配布します。  
また、ISF_TUSBで使用するコマンドを置く予定です。  
コマンドパッチの配布はTwitterの[モーメント](https://twitter.com/i/events/1205486939643580416)にて行っています。

---
## これだけは知っておいてほしいこと
ここにあるコマンドパッチはPonponが作成している非公式のものだということを知っておいてください。   
非公式なのでここのパッチを導入して起きた可能性のあるバグは**公式TUSBに報告せず**、Ponponに連絡をください。  
連絡先は下のほうに掲載しておきます。

---
## コマンドパッチについて
私が製作する1コマンドパッチは、The Unusual SkyBlock v12.0.9 にて製作・動作確認を行っています。  
以下に、導入方法などを書き記しておきます。

#### 導入方法
OP権限の取得方法が、ソロプレイかマルチプレイで少し異なります。
- ソロプレイの場合  
取得方法はいくつかありますが、そのうちで簡単なものを説明します。  
ESCでメニュー画面にし、LANに公開を選択します。  
画像のように、「チートの許可」をオンにします。  
![lan_cheat](https://raw.githubusercontent.com/NePonpon/TUSB_Patch/images/lan_cheat.png)  
LANワールドを公開するとOP権限を取得できます。  

- マルチプレイの場合  
サーバーコンソールに以下のコマンドを打ち込みます。
> /op <OP権限を与えるプレイヤー名>  

以上の方法で、OP権限を取得することが出来ます。

コマンドパッチを実行する環境を整えます。  
まずはゲームモードをクリエイティブに変更します。
> /gamemode creative

次にコマンドパッチを実行するためのコマンドブロックを取得します。  
> /give @p command_block  

コマンドブロックの設定を画像のようにしておきます。  
![CommandBlock_Setting](https://raw.githubusercontent.com/NePonpon/TUSB_Patch/images/CommandBlock_Setting.png)  
「インパルス」「無条件」「常時実行」に設定しておきます。

コマンドパッチをコピーし、コンソールコマンドにペーストします。  
「完了」を押すと実行され、導入が始まります。

#### それぞれのコマンドパッチの内容について
各パッチのディレクトリを開くと、そのパッチについての細かい説明が書いてあると思うので、それを参考にしてください。

---
## コマンドパッチ製作ツールについて
mkm75氏作成の **ezpatch.jar** というコマンド圧縮ツールを使用しています。  
ツールは[こちら](https://github.com/crafter1415/ezpatch/blob/main/README.md)からダウンロードができます。細かい説明も書かれています。

---
## パッチを作るためにお世話になっているところとお礼
mkm75氏 [ezpath.jar](https://github.com/crafter1415/ezpatch/blob/main/README.md)  
[Pastebin.com](https://pastebin.com/)  
[Dropbox](https://www.dropbox.com/)  
**いつもありがとうございます!**

---
## バグ報告の際の連絡先
Twitter : [nepon13](https://twitter.com/nepon13)  
Discord : Ponpon#5326  
お気軽に連絡をお願いします。