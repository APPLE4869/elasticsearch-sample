# ElasticSearchでよく使うクエリ
`customer`インデックスを作成する。
```
PUT /customer?pretty
```

インデックスを確認する。
```
GET /_cat/indices?v
```

```
curl -H "Content-type: application/json" -XPUT http://localhost:9200/customer/external/1?pretty -d '{ "name": "John Doe" }'
```

# 参考資料
あなたの知らないElasticsearch設定トップ5
http://acro-engineer.hatenablog.com/entry/2017/12/05/120000
