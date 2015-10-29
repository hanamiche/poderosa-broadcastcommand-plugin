# Poderosa BroadcastCommand plugin
※日本語から英語への翻訳はBing翻訳を使用しています。  
(* From Japanese to English translations use the Bing translator.)

Poderosa用のブロードキャストコマンドプラグインです。  
(This is for Poderosa broadcast command plugin.)

このプラグインは、接続中のホストに対して入力したコマンドを一括送信するものです。  
(This plugin is to send bulk command you entered for the connected host.)

VisualC# 2013で開発し、Poderosa v4.3.16(.Net4.5)で動作確認しています。  
(Developed in VisualC# 2013, has confirmed on the Poderosa v4.3.16(.Net4.5).)


## Features
* テキストボックスに入力したコマンド文字列を選択したホストに送信します  
(Send the host commands typed in the text box is selected.)

* コマンドは1行または複数行を送信することができます  
(The command line or you can send more than one row.)

* コマンド入力後にEnterキーで送信します  
(After the command input with the Enter key sends.)

* コマンド入力後にShift+Enterキーで改行します  
(After the command input line with Shift + Enter.)

* モードレスダイアログなのでダイアログ表示中でもPoderosaウィンドウを操作できます  
(Modeless dialog so manipulate dialog among Poderosa window.)

* ダイアログの多重起動は防止されています  
(Prevents multiple startup dialog)

* 同一コマンドを繰り返し実行することが出来ます  
(You can repeat the same command.)

* 繰り返し実行する場合にインターバルを設定することが出来ます  
(You can set the interval to run repeatedly.)

* 改行コードを送信しない設定が出来ます  
(Setup does not send a NeeLine.)

* 送信したコマンドをログ表示できます (表示のみでファイル保存は無し)  
(You can send a command log. (View only with no files.))

* [ツール] - [オプション] - [コマンド]でキーバンド設定が出来ます  
(Can the KeyBinding settings in the [Tools] - [Options] - [Command])


## Installation
Poderosaディレクトリ内に下記のように配置します。  
(Poderosa directory in the position as shown below.)

`Poderosa/`  
`├── BroadcastCommand`  
`│   ├── Contrib.BroadcastCommand.dll`  
`│   └── Contrib.BroadcastCommand.pdb`  
`└── Poderosa.exe, and other files.`


## Usage
※表示言語はPoderosaの言語設定に準拠しています (画像は英語版)  
(* Language conforms to the language setting of the Poderosa (the image is the English version))

1. ツールメニューからブロードキャストコマンドを選択します  
(Select the Telnet/SSH connection profiles from the Tools menu.)  
![UsageImg1](https://github.com/yoshikixxxx/poderosa-broadcastcommand-plugin/wiki/img/img1.png)

2. 対象のホストにチェックを入れてテキストボックスにコマンドを入力してEnterキーを押下します  
(Put a check on the target host, and type command in the text box and press Enter.)  
![UsageImg2](https://github.com/yoshikixxxx/poderosa-broadcastcommand-plugin/wiki/img/img2.png)

3. 選択したホストにコマンドが一括送信されます  
(Sent out bulk command on the selected host.)  
![UsageImg3](https://github.com/yoshikixxxx/poderosa-broadcastcommand-plugin/wiki/img/img3.png)

4. テキストボックス内でShift+Enterを押下すると改行されコマンドを複数行入力することが出来ます。  
また、ログ表示ボタンを押すと右側に送信ログが表示されます。  
(You can command to enter multiple lines and line breaks and you press Shift + Enter in a text box.)  
(Also, pressing the log button displays send log on the right side.)
![UsageImg4](https://github.com/yoshikixxxx/poderosa-broadcastcommand-plugin/wiki/img/img4.png)

5. 必要に応じてキーバンド設定を行います  
(Optionally configure key band.)  
![UsageImg4](https://github.com/yoshikixxxx/poderosa-broadcastcommand-plugin/wiki/img/img5.png)


## History
* 2015/10/29 v1.0  
初期リリース  
(Initial release.)


## License
Copyright 2015 yoshikixxxx.  
Licensed under the Apache License, Version 2.0 (the "License");  
you may not use this file except in compliance with the License.
