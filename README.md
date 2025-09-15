English version: [README_en.md](README_en.md)

# グローバルシャッターMIPI高速度カメラ(PYTHON300 + Spartan7)

## 概要

オンセミコンダクター社 [PYTHON300イメージセンサー](https://www.onsemi.jp/products/sensors/image-sensors/python300) と AMD(Xilinx) の [Spartan7](https://www.amd.com/ja/products/adaptive-socs-and-fpgas/fpga/spartan-7.html) FPGA を用いた研究開発向けの小型のカメラモジュールの設計データです。

KiCAD にて設計を行っております。

データシート上は VGA サイズながら 815fps の高速度撮影が可能と記載されているセンサーを利用しており、当方でも [KV260](https://www.amd.com/ja/products/system-on-modules/kria/k26/kv260-vision-starter-kit.html) に接続して 320x320 サイズで 1000fps 撮像が出来ております。


![カメラ外観写真](docs/images/camera_photo.png)


## リポジトリ構成

| ディレクトリ |  説明                                            |
|:------------|:------------------------------------------------|
| mipi_spartan7    | Spartan7 FPGA の載った親基板のプロジェクト |
| sensor_python300 | PYTHON300 イメージセンサーの載った子基板のプロジェクト |
| sensor_mipi      | 親子基板を共取り製造用に結合したプロジェクト |


## 免責事項

本設計データは、研究開発用の試作実験に用するものであり、利用に際して発生した如何なる損害も作者は補償いたしませんので予めご了承ください。

## ライセンス(License)

本設計データは、[クリエイティブ・コモンズ 表示-非営利 4.0 国際 ライセンス](https://creativecommons.org/licenses/by-nc/4.0/deed.ja)の下で提供されています。

製造した本基板の無断での販売や配布を行わない限りは、趣味や研究開発用途でご自由にお使いいただく事が出来ます。

また、商用に製造販売を希望される場合は、別途ライセンス契約を作者までご相談ください。[お問い合わせフォーム](https://rtc-lab.com/contact/)などからお問い合わせ頂けます。


## 作者情報

渕上 竜司(Ryuji Fuchikami)
[リアルタイムコンピューティング研究所](https://rtc-lab.com/)
