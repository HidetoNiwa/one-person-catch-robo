# one-person-catch-robo

[#１人キャチロボ]() のリポジトリ

## CAD

* 全体.iam：ロボット全体設計（フィールド込み）
* ロボット.iam：ロボット設計

そのほか、構造解析レポートとかもあります。

### 開発ソフトウェア

Autodesk Inventor Professional 2020

学生版ライセンスで使用可能

## KiCAD

* メインボード.pro：メインボードの設計

### 開発ソフトウェア

KiCAD 5.1.3

## 公式提出資料

## YOLO環境構築

### 環境

Jetson Nano

### 方法

https://www.nakasha.co.jp/future/ai/vol2_yolov3nvidia_jetson_nano.html

OpenCVのver.4系だとうまくコンパイル-できなかった

https://pickerlab.net/2018/08/06/darknet-eroor-nvcc/

### 学習用ファイルラベリング「labelimg」

参考；https://symfoware.blog.fc2.com/blog-entry-2420.html

PyQTのバージョン：5.14.1
デフォルトのインストール設定では、5.10.1になっているのを書き換える（pip配布の問題）
