newsgroup ツリー表示プログラム
=================

## 概要
- 暫くC++に触れていなかったので、簡単なプログラムを実装してみた。
- 内容はnewgroupのリストをツリー表示する。

## 開発環境
| Item   | Ver. |備考|
|--------|--------|--------|
| OS     | CentOS7 | |
| GCC    | 4.8.5||

## ビルド
```
git clone https://github.com/hidekuno/newsgroup-viewer.git
cd newsgroup-viewer
make
```

## 動かし方
```
./newgroup.py > group.txt
./treeview -l < group.txt
```
<img src="https://user-images.githubusercontent.com/22115777/66184854-64bd2880-e6b8-11e9-863e-867540098065.png" width=50%>
