# 概要
  AIIT enPiTサイトの開発環境です．

# ソースコードのダウンロード

  gitコマンドでソースコードをダウンロードします．
  wordpressのコードはサブモジュールとしてvagrant/aiit-enpit-wordpresディレクトリに格納されます．

```bash
git clone git@github.com:ychubachi/aiit-enpit-wordpress-vagrant.git
cd aiit-enpit-wordpress-vagrant
git submodule init
git submodule update
```

# 仮想環境の起動

```bash
cd vagrant
vagrant up
```
