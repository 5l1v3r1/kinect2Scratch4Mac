- このバージョンはどこかおかしな所があります。なるべく早く修正します。
- - This version is something wrong.  I'll fix it ASAP.
# English README is [here](https://github.com/mactkg/kinect2Scratch4Mac/blob/master/README_en.md)
# KinectをScratchで使う
MacでもKinectを使ってScratchで遊びたいですよね。作りました。動作確認は10.6の最新版で行なっています。10.7や10.5などでは動作確認していません。ごめんなさい。
もしチャレンジして動くことがあったら、ぜひ教えてください。

## 必要なもの
* Kinect

## 使い方

0. Kinect2Scratch4Macを上のリンクからダウンロードします
1. Kinectをつなげます
2. Scratchを起動します
3. 遠隔センサー接続をオンにします
4. Kinect2Scratch4Macを立ち上げます

Kinectのテストのためにこのプロジェクトとかおすすめです http://scratch.mit.edu/projects/SHowell/1523809


## ビルド方法 - How to build it?


1. openFrameworks(007)を[ここ]("http://openframeworks.cc/download")からダウンロードします
2. 解凍します
3. Kinect2Scratch4Mac（これ）を上部の"ZIP"ってところからダウンロードします
4. 解凍します
5. 2で解凍して出来たフォルダ/apps/examples/の中に4で出来たフォルダをいれます
6. フォルダを入れたら、中にはいってるKinect2Scratch4Mac.xcodeprojを開きます
7. Runボタンをクリックすれば動きます（Kinectをつなげたりするのを忘れないように）

### 遠隔センサー接続オンのやり方
0. Scratchを起動します
1. "調べる"ボタンをクリックします
2. "スライダーセンサーの値"を右クリックします
3. "遠隔センサー接続を有効にする"をクリックします


## ライセンス

MIT License

## Changelogs
* v003 - .dylibファイルを.appにBundleできるようにした
* v002 - UIの追加、接続方式の変更をした
* v001 - 初回リリース
