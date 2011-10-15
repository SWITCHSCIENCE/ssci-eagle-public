# EAGLE用ライブラリ（など） #

ライセンスは特に主張しません。自由に使ってください。
**できたら**、以下の事をお願いします。

* 使用したプロジェクトを公表する際に、この場所への言及。
* 改良点、新しいファイル等のフィードバック。

[ダウンロードするには、ここをクリックしてください。](https://github.com/SWITCHSCIENCE/ssci-eagle-public/zipball/master)

## ファイルの内容 ##

* akizuki.lbr
 * C9767 --- [C9767コンデンサマイク](http://akizukidenshi.com/catalog/g/gP-01810/)
* avr-isp.lbr
 * AVR-ISP-6PIN --- AVR用ISP端子。信号名を指定してあるので、配線が簡単。干渉する領域をマークしてあります。
* cream-dxf.ulp --- 基板図からステンシルのDXFを吐き出すスクリプト。
* generic.lbr
 * CAPACITOR --- 普通のコンデンサ。1608と2012があります。
 * CAPACITOR\_POL --- 電解コンデンサ。パナソニックのサイズに合わせてあります。
 * LED --- 普通のLED。1608と2012があります。
 * REGISTOR --- 普通の抵抗。1608と2012があります。
* kyocera-elco.lbr
 * ELCO-6222-6 --- [京セラエルコFFCコネクタ0.5mmピッチ][] 6ピン
 * ELCO-6222-8 --- [京セラエルコFFCコネクタ0.5mmピッチ][] 8ピン

  [京セラエルコFFCコネクタ0.5mmピッチ]: http://www.kyocera-elco.com/jp/prdct/type/fpc/6223.html
