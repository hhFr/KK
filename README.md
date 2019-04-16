# KK
Kana Keyboard character transform.

キーボードのかな刻印に従った文字変換


DKK Dis-KK

KK の逆変換

# Usage

KK [strings]

DKK [strings]

## Description
引数が無ければ標準入力を入力元にする。

## 使用例

$ KK system 

とんとかいも

$ echo system | KK

とんとかいも

$ DKK はにりいと

files

$ echo はにりいと | DKK

files


## インストール
PATHの通ったディレクトリにKKとDKKを配置

実行属性を付与
chmod +x *KK

#EOF
