# alpine-f
Investigation tools for inside k8s clusters. The image contains curl, psql, etc. 

Commands:

```sh
FROM alpine:3.7
RUN apk add --no-cache curl
RUN apk add --no-cache postgresql-client
ENTRYPOINT ["/bin/ash"]
```

K8sクラスタ内部のデバッグ用として作成。イメージにはcurl、psql、ping、tracerouteなどが含まれる。

コマンド:

```sh
FROM alpine:3.7
RUN apk add --no-cache curl
RUN apk add --no-cache postgresql-client
ENTRYPOINT ["/bin/ash"]
```
