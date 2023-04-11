# 8087bench
Intel 8087 benchmark

## 説明
Intel 8087のベンチマークテスト。

## ビルド方法
tcc -ml -G -Z -O -ewhet_tcc.exe whetston.c<br>
※memo.txt参照

## 動作環境

### OS
MS-DOS

### 確認環境
NEC PC-9801初代(V30+8087)

## 詳細
コンパイル時にTCCを定義すると、以下の値を表示する。
・変数 _8087
・環境変数 87
・pc98equip関数の戻り値
