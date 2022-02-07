# コンテナ(Pod)の中を見たい場合

```
kubectl exec ポッド名 コマンド
```

例

```
kubectl exec nginx cat /etc/nginx/nginx.conf
```