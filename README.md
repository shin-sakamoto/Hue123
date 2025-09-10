# Hue123
Hue App 再点灯対策アプリ

Hueランプの輝度が1%になったら自動で消灯するプログラムです。
不明点があったらXで@OneHuefan147187に質問してください。

右上の[Code]->[Download Zip]->Zipファイルを解凍

JDKインストールが必須です。
https://www.oracle.com/java/technologies/downloads/
JDKをダウンロードしてインストールしてください。

Java.exeファイルがあるフォルダを指定してjave.exe -jar Hue123.jar
とするとアプリが起動します。

通常は以下のように起動します。
Windows)
ターミナルで
C:\(JDKインストールフォルダ)\org.eclipse.justj.openjdk.hotspot.jre.full.win32.x86_64_23.0.1.v20241024-1700\jre\bin\java.exe -jar .\Hue123.jar

Mac)
ターミナルで
sudo (JDKインストールフォルダ)\bin\java.exe -jar .\Hue123.jar

最初の画面(メッセージがなぜか出ないです)でブリッジのボタンを押してください。

先に、Hueランプが再点灯する場合は、Hueアプリの[設定]->[デバイス]->[ランプ]->[電源オン]->[カスタム]
で目立たない色の明るさ1%を指定してみてください。
そしてこのアプリを起動したままにしておけばとりあえず回避策にはなるようです。



