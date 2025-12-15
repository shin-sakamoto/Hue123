# Hue123
----------------------------(English)----------------------------------------------

Hue App for Win/Mac

Please feel free to ask the question for X @OneHuefan147187

1) Workaround for unwanted lit

It will off the lamp automatically if brightness is 1%.

If you are concerning with unwanted lit even after you turn off,
please configure the [Hue App]->[Setting]->[Device]->[Light]->your light->[Power on]->[Custom]->1% dimming level and low-profile color.

Then the app will turn off unwanted lit.

The function is always enabled while the Hue123 is launched.

If you want to disable the function, [Setting]->[Check Every [X] milliseconds], set value 0(Zero)


2) Support for Coming home automation

It will turn on the scene when the target device is connected to the same WiFi network.

* need root priviledge for Mac OS to scan network, need [sudo] on command line for the function

[Setting]->[Leaving/Coming Home]section

[ScanNW] and choose IP of your cell phone.

Choose your favorite scene.

Set exclusive period if you need. set [00:00:00] to [00:00:00] then disabled.

[Save Host and Scene]

Click [?] to check the current setting.



3) Remove/Save/Load configuration

[Delete Bridge Info]  !! Delete all lamps and scenes from memory of the bridge !!

[Detect New Lamp] Detect new lamps. New lamps will be added to the right [Found Lamps] tree. 

[Save Bridge Info]  Save setting of rooms and lamps as text file. 

[Load Bridge Info]  Load setting and show on the left [Loaded lamps] tree 

[Match]/[Unmatch] Choose new lamp and right-click, lamp flashes. Choose corresponding [Loaded lamp] and press [Match].Then new lamp is linked to the loaded lamp. 

[Restore Bridge Info] After all new lamps are matched, press [Restore] and rooms and lamps will be restored to the bridge. 


    
-------------------------------
Install)
Upper right green [Code]->[Download Zip]->unzip file

JDK is needed.Download and install.
https://www.oracle.com/java/technologies/downloads/

Copy the Hue.jar to the folder of Jave.exe.
 
Windows)
./jave.exe -jar ./Hue123.jar

Mac)
sudo ./jave.exe -jar ./Hue123.jar


(If you don't use [Coming Home], no need [sudo])

Please push the link button on the Hue bridge at the first sceen.

Please dim the light to the 1% for testing.

-------------------------(日本語/Japanese)----------------------------------------------

不明点があったらXで@OneHuefan147187に質問してください。


Hue123 アプリ


1)再点灯対策機能

Hueランプの輝度が1%になったら自動で消灯するプログラムです。

先に、Hueアプリで

[設定[->[デバイス[->[ライトとスマートプラグ]->自分のランプを選択->[電源オン]->[カスタム]->輝度1%で目立たない色を選択
としておくと、自動で再点灯したランプを消灯します。

この機能は自動で有効になっているので、無効にしたい場合はチェック間隔を0ミリ秒にしてください。

ＰＣの性能に応じてチェック間隔を調整してください。


2)帰宅時自動点灯

帰宅オートメーションの補助で指定携帯がWiFiに接続されたのを検知してシーンを自動点灯します

* MAC OSの場合はルート権限が必要なので[sudo]を付けて起動する必要がありますが、この機能を使わないならば[sudo]なしでも動作します。

[Setting]->[Leaving/Coming Home]セクションで

[ScanNW] を押して携帯電話のＩＰアドレスを選択してください。

右のパネルで起動したいシーンを選択してください。

起動させたくない時間があれば時間帯をしていしてください。いらないばあいは[00:00:00] から [00:00:00]としてください。

[Save Host and Scene]で設定を保存してください。

[?]　を押すと設定が確認できます。



3)設定の保存、自動再設定

[Delete Bridge Info]  !! ブリッジ情報をクリアします。部屋、ランプ、シーンが削除されます。 !!

[Detect New Lamp] ランプを検索します。見つかったものは右の [Found Lamps] ツリーへ追加されます. 右クリックするとランプが点滅します。

[Save Bridge Info]  部屋、ランプをテキストファイルに保存します。

[Load Bridge Info]  保存した設定を読み込みます。左の [Loaded lamps] ツリーへ表示されます。

[Match]/[Unmatch] 右のツリーの新規ランプを右クリックして点滅させて、対応するランプを左のツリーの[Loaded lamp]から選んで [Match]を押します。新規ランプと保存されたランプがリンクします。

[Restore Bridge Info] 全ての新規ランプをリンクしてから [Restore] を押すと部屋とランプが自動で作成されます。


---------------------------------------------
インストール方法)

このページの右上の[Code]->[Download Zip]->Zipファイルを解凍

JDKインストールが必須です。
https://www.oracle.com/java/technologies/downloads/

JDKをダウンロードしてインストールしてください。

Java.exeファイルがあるフォルダにHue.jarをコピーしてjave.exe -jar Hue123.jar

とするとアプリが起動します。


通常は以下のように起動します。

Windows)

ターミナルで

C:\(JDKインストールフォルダ)\org.eclipse.justj.openjdk.hotspot.jre.full.win32.x86_64_23.0.1.v20241024-1700\jre\bin\java.exe -jar .\Hue123.jar


Mac)

ターミナルで

sudo (JDKインストールフォルダ)\bin\java.exe -jar .\Hue123.jar

(帰宅時自動点灯を使わないならsudoはなくても問題ありません)


最初の画面(メッセージがなぜか出ないです)でブリッジのボタンを押してください。


先に、Hueランプが再点灯する場合は、Hueアプリの[設定]->[デバイス]->[ランプ]->[電源オン]->[カスタム]
で目立たない色の明るさ1%を指定してみてください。
そしてこのアプリを起動したままにしておけばとりあえず回避策にはなるようです。



