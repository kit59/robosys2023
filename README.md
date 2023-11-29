# plusコマンド
![test](https://github.com/kit59/robosys2023/actions/workflows/test.yml/badge.svg)

標準入力から読み込んだ数字を足す.

## Quick trial
実行例をいくつか紹介する.３を入力すると１+２+３で６を, ６を入力すると同様の処理がされ21が出力される.
```
$ seq 3 | ./plus
6
$ seq 6 | ./plus
21
```

## Install
下記を実行するとリポジトリがクローンされる.
```
$ git clone https://github.com/kit59/robosys2023.git
```

## 必要なソフトウェア
* Python
  * テスト済み: 3.7～3.10

## テスト環境
* Ubuntu 20.04 on Windows

## Licence
* このソフトウェアパッケージは, 3条項BSDライセンスの下, 再頒布および使用が許可されます 
* このパッケージのコードは, 下記のスライド (CC-BY-SA 4.0 by Ryuichi Ueda) のものを, 本人の許可を得て自身の著作としたものです.
    * [ryuichiueda/my_slides robosys_2022 lesson4.md](https://github.com/ryuichiueda/my_slides/blob/master/robosys_2022/lesson4.md)
* © 2023 Kaito Akiyama
