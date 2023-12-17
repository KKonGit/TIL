# ディレクトリの作成

- `mkdir` コマンドで作成する


複数の連番ディレクトリを作成したい場合
例えば、dir_1, dir_2, ..., dir_10 という名前のディレクトリを作成する場合
```
mkdir dir_{1..10}
```

これはブレース展開(brace expansion)と呼ばれる。



## 再帰的にディレクトリを作成する場合

- `mkdir -p 再帰的ディレクトリ構造` これで親ディレクトリが無くても配下のディレクトリを作成できる


```
mkdir -p /parent_directory/child_directory/grandchild_directory
```

当然、ブレース展開と合わせることも可能

```
mkdir -p parentdir/childdir{01..100}
```
