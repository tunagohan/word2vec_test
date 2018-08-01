# word2vec_test

カンタンに試せるようにしてみました。

### 立ち上げ
```
$ docker-compose up -d
```

### 何かを実行したいとき
```
$ docker-compose run --rm app {コマンド}
```

### コンテナの中で実行するとき(mecabは途中終了ができなくなるためこっち推奨)
```
$ docker exec -it word2vec bin/bash
```


## 作業について

コンテナ内にvimが入っておりますが、
app配下が同期されるようになっているため、そちらをお手持ちのエディタで編集し
コンテナ内実行を行えば実行が可能です
