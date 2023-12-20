# 情報整理用のコマンド

- `grep` ：指定したパターンに一致する行をファイルや標準入力から検索するためのツール
- `wc`   ：キストファイルや標準入力から単語や行数、バイト数をカウントするためのツール
- `sort` ：


### grep
grepは __"Global Regular Expression Print"__ の略で、正規表現を使用してパターンを検索

- オプション
  - `-i` ：大文字小文字を無視して検索
  - `-n` ：一致した行の行番号を表示する

> 例

```
grep -i "pattern" file.txt
```

### wc

- オプション
  - `-l` ： 行数を表示する
  - `-w` ： 単語数を表示する
  - `-c` ： バイト数を表示する

> 例

```
$ cat example.txt
Hello, this is an example text file.
It has multiple lines.
Let's see how wc counts them.

$ wc example.txt
 3  15 104 example.txt

```
