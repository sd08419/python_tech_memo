# python_tech_memo

tech_memo


# 概要

下記サイトに記載したpython関連tipsのサンプルコード

https://sd08419ttic.hatenablog.com/

# 動作環境

* Windows 10
* python 3.5 (from Anaconda)

必要ライブラリ

* numpy
* pandas
* cv2
* pdf2image
* google_images_download
* pytube
* animatplot

(pdf2imageは http://blog.alivate.com.au/poppler-windows/ に従い必要なファイルを手動でダウンロードする必要がある)

# 機能説明

### pandasのデータファイル読み込み方法 (フォルダ配下のファイルを一括読み込み)

ReadDataModule.py

https://sd08419ttic.hatenablog.com/entry/2019/02/16/031604

### 画像・動画ファイル読み込み方法 (フォルダ配下の画像/動画/ドキュメントを一括読み込み)

ReadImageModule.py

https://sd08419ttic.hatenablog.com/entry/2019/02/16/031604

### 画像ファイルに対する前処理 (リサイズ/色補正など)

ImagePreProcessing.py

https://sd08419ttic.hatenablog.com/entry/2019/03/02/210830


### 集計データのマージ機能

MergeDataModule.py

https://sd08419ttic.hatenablog.com/entry/2019/02/24/221808

### Google系Webサービスのデータ取得

GetGoogleWebService.py

https://sd08419ttic.hatenablog.com/entry/2019/02/27/005447

### GUI機能の実装(tkinter)

TkinterModule.py

https://sd08419ttic.hatenablog.com/entry/2019/03/16/145938

### pythonスクリプトのexeファイル化 (pyinstaller)

pyinstallerModule.py

https://sd08419ttic.hatenablog.com/entry/2019/03/14/011913

 ### 画像認識①テンプレートマッチング/色に基づく物体認識/エッジ形状に基づく形状認識

SimpleObjectDetectionModule.py

https://sd08419ttic.hatenablog.com/entry/2019/03/31/221358


### キーボード・ジョイスティック操作内容の取得 (pygame) ###

get_joykey.py

https://sd08419ttic.hatenablog.com/entry/2019/06/26/224930

### matplotlibのアニメーション描画 ###

AnimationPlot.py

https://sd08419ttic.hatenablog.com/entry/2020/03/03/000404


### matplotlibによる3Dグラフ描画

3dplot.py

https://sd08419ttic.hatenablog.com/entry/2021/10/17/171900