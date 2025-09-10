# Hue123
----------------------------(English)----------------------------------------------
Hue App for Win/Mac

It will off the lamp automatically if it is 1% dimming level.
If you are concerning with unwanted lit after you turn off,
please configure the [Hue App]->[Setting]->[Device]->[Light]->your light->[Power on]->[Custom]->1% dimming level and low-profile color.
Then the app will turn off unwanted lit.

Please feel free to ask the question for X @OneHuefan147187

Upper right green [Code]->[Download Zip]->unzip file

JDK is needed.Download and install.
https://www.oracle.com/java/technologies/downloads/

Copy the Hue.jar to the folder of Jave.exe.
And 
Windows)
./jave.exe -jar ./Hue123.jar
Mac)
sudo ./jave.exe -jar ./Hue123.jar
(If you don't use [Coming Home], no need [sudo])

Please push the button on the Hue bridge at the first sceen.

Please dim the light to the 1% for testing.

-------------------------(日本語/Japanese)----------------------------------------------
Hue App アプリ
1)再点灯対策機能
Hueランプの輝度が1%になったら自動で消灯するプログラムです。
不明点があったらXで@OneHuefan147187に質問してください。

2)帰宅時自動点灯
帰宅オートメーションの補助で指定携帯がWiFiに接続されたのを
検知してシーンを自動点灯します

3)設定の保存、自動再設定 開発中です
ランプのシリアル番号の入力が必須です

インストール方法)
右上の[Code]->[Download Zip]->Zipファイルを解凍

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



