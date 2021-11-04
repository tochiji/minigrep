# minigrep

Rust で作った小さな grep コマンドです。

## 指定した文字列が含まれる行をファイルから検索します

```console
$ cargo run to poem.txt
Are you nobody, too?
How dreary to be somebody!
```

## 大文字小文字を無視して検索します

```console
$ CASE_INSENSITIVE=1 cargo run to poem.txt
Are you nobody, too?
How dreary to be somebody!
To tell your name the livelong day
To an admiring bog!
```
