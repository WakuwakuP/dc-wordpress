# dc-wordpress

Docker上でWordpressを立ち上げてちょっと動かす用のdocker-compose。  
セキュリティ対策等をしていないため立ち上げたサイトを公開しないでください。

## install

```
git clone https://github.com/wakuwakup/dc-wordpress.git wordpress
cd wordpress
docker-compose up -d
```

[http://localhost:8000/wp-admin](http://localhost:8000/wp-admin)にアクセスする。