# EAGLE用ライブラリ（など） #

ライセンスは特に主張しません。自由に使ってください。
**できたら**、以下の事をお願いします。

* 使用したプロジェクトを公表する際に、この場所への言及。
* 改良点、新しいファイル部品のフィードバック。

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
* chinese-con.lbr
 * USB-A --- 中国製のデータシート無しのAコネクタ。点線で基板のエッジを記してあります。
 * USB-B --- 中国製のデータシート無しのBコネクタ。MiniとMicroがあります。点線で基板のエッジを記してあります。
* Raspberry_Pi_B+.lbr
 * HAT_BOARD --- Raspberry Pi model B+用のHAT(Hardware Attached Top) board。

## ライブラリ作成のルール ##

* ひとつのファイルに、あまり数多くの部品を入れない。メーカー等でファイルを分ける。
* パッケージ
 * 文字サイズは標準40mil。
* シンボル
 * 文字サイズは標準70mil。
 * 線は標準10mil。
* なるべく、ちゃんとKeepoutレイヤを指定する。

## ヒント ##
* シンボルのPinでは、「Point」をうまく使う。
* 現行のEAGLE5での制限。
 * 複数のピンに同じ信号名を指定する事はできない。
 * バイナリファイルなのでマージができない。複数人で作業する時は声を掛け合う事。
