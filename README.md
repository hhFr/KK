# KK/DKK
Kana Keyboard character transform.

キーボードのかな刻印に従った文字変換

DKK:Dis-KK	
KK の逆変換


# 動作環境

BSD系 (確認済み:macOS, FreeBSD) (未確認:他のBSD系)

※Linuxは未対応 (tr がマルチバイト文字未対応のため)


# Usage

KK [strings]

DKK [strings]

# Description
引数が無ければ標準入力を入力元にする。

# 使用例

$ KK system 

とんとかいも

$ echo system | KK

とんとかいも

$ DKK はにりいと

files

$ echo はにりいと | DKK

files


# インストール
PATHの通ったディレクトリにKKとDKKを配置

実行属性を付与
chmod +x *KK

#EOF
